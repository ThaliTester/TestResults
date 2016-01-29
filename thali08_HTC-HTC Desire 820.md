#### Test 57617811ecc172f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,--------- beginning of /dev/log/main
I/HtcModeClient( 1472): handler message = 4011
E/HtcModeClient( 1472): Check connection and retry 12 times.
E/cutils-trace( 3947): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3947): ====startRecUseTime====
D/htc.customization.log.level( 3947):  is 
W/CustomizationLogLevel( 3947): Level value is invalid, use default level 2
D/CustomizationManager( 3947):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3947): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3947): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3947): Parsing tag category name = system
I/CustomizationCIDLoader( 3947): Parsing tag category name = application
I/CustomizationCIDLoader( 3947): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3947): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3947): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3947): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3947): Parsing tag category name = Settings
D/CustomizationManager( 3947):  Read CID file spent 0.105 (s)
D/CustomizationManager( 3947):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 3947): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3947): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3947): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3947): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3947
D/PMS     (  904): acquireHCC(425c97a8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(42448800): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x66e97510 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1113885528
D/PMS     (  904): acquireWL(422349e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1243): [onPause]
I/FeedProviderManager( 1243): onPause
I/FeedHostManager( 1243): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42038fb8
I/SocialFeedProvider( 1243): +onPause
I/SocialFeedProvider( 1243): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3958 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1243): [trimMemory] 20
W/asset   ( 3958): Copying FileAsset 0x5c87b428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3958): Binding Chromium to main looper Looper (main, tid 1) {41e06458}
I/LibraryLoader( 3958): Expected native library version number "",actual native library version number ""
I/chromium( 3958): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3958): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42737948:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  904): acquireWL(422cf7a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  904): acquireWL(41e92c20): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  904): releaseWL(422cf7a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3958): 1105313424: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3958): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3958): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3958): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3958): Local Branch: 
I/Adreno-EGL( 3958): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3958): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3958):                  aa63bbd948f41d15fc72f585e
W/chromium( 3958): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3958): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3958): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3958): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3958): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3958): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3958): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3958): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3958): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3958): CordovaWebView is running on device made by: HTC
W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/AwContents( 3958): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1243
,W/ResourceType( 3958): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3958): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e4d418, mServedView=org.apache.cordova.engine.SystemWebView{41e131a8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  904): Enable input method client, pid=3958
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3958): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +273ms
,D/PMS     (  904): releaseWL(422349e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3958): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3958): JniHelper::setJavaVM(0x419bf010), pthread_self() = 1662140872
,I/chromium( 3958): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 11.230MB for 323830-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 11.493MB for 485740-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 11.876MB for 728606-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 12.449MB for 1092904-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 13.344MB for 1639352-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 14.719MB for 2459024-byte allocation
,I/dalvikvm-heap( 3958): Grow heap (frag case) to 15.407MB for 2287544-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,D/PMS     (  904): releaseHCC(425c97a8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 3958): Initializing JXcore engine
,W/jxcore-log( 3958): JXcore engine is ready
D/PMS     (  904): releaseHCC(42448800): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3958): Starting JXcore engine
,W/jxcore-log( 3958): Platform android
W/jxcore-log( 3958): 
,W/jxcore-log( 3958): Process ARCH arm
W/jxcore-log( 3958): 
,I/jxcore-log( 3958): JXcore Cordova bridge is ready!
I/jxcore-log( 3958): 
,W/jxcore-log( 3958): JXcore engine is started
,I/jxcore-log( 3958): Toggling radios to true
I/jxcore-log( 3958): 
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  904): checking for enable restriction...
,D/BluetoothManagerService(  904): checkBTEasState, ret=true
,I/BluetoothManagerService(  904): isBluetoothRestricted(): false
D/BluetoothManagerService(  904): enable(): region ID = 6
D/BluetoothManagerService(  904): enable():  mBluetooth =null mBinding = false
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 1
,W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1234
W/Settings:Agent(  904): Process.myUid(): 1000
,W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
,W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  904): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  904): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  904): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3958): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
,W/Settings:Agent(  904): Process.myTid(): 1467
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
,W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): ,	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=3958, uid=10189
,E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  904): isSprintWifiRestricted(): false
,I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 6(ms)
I/ActivityManager(  904): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4005 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3958): disconnect: Base Package Name=com.test.thalitest, uid=10189
,D/WifiManager( 3958): reconnect: Base Package Name=com.test.thalitest, uid=10189
,I/jxcore-log( 3958): Radios toggled
I/jxcore-log( 3958): 
,D/PMS     (  904): acquireWL(4277b838): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
I/jxcore-log( 3958): My device name is: HTC-HTC Desire 820
I/jxcore-log( 3958): 
,D/AdapterServiceConfig( 4005): Adding HeadsetService,
D/AdapterServiceConfig( 4005): Adding A2dpService
D/AdapterServiceConfig( 4005): Adding HidService
D/AdapterServiceConfig( 4005): Adding HealthService
D/AdapterServiceConfig( 4005): Adding PanService
,D/AdapterServiceConfig( 4005): Adding GattService
,W/linker  ( 4005): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 4005): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42602c70:true
,D/BluetoothAdapterState( 4005): make
,I/BluetoothAdapterState( 4005): Entering OffState
,I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 4005): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  904): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  904): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  904): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  904): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1754): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4241b690
,D/BluetoothAdapter( 1754): onBluetoothServiceUp done,
D/BluetoothAdapter( 1217): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ecd910
D/BluetoothAdapter( 1217): onBluetoothServiceUp done
D/BluetoothAdapter( 4005): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41e1ed70
,D/BluetoothAdapter( 4005): onBluetoothServiceUp done
D/BluetoothAdapter( 1228): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f3dd50
,D/BluetoothAdapter( 1228): onBluetoothServiceUp done
,D/BluetoothAdapter(  904): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4264e3b0
,D/BluetoothAdapter(  904): onBluetoothServiceUp done
,D/BluetoothAdapter( 3958): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@424f8dd8
,D/BluetoothAdapter( 3958): onBluetoothServiceUp done
,D/BluetoothAdapter( 1392): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4207e5f8
,D/BluetoothAdapter( 1392): onBluetoothServiceUp done
,D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4224b0e8
D/BluetoothAdapter( 1107): onBluetoothServiceUp done
,D/BluetoothManagerService(  904): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 4005): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4005): Setting state to 11
I/BluetoothAdapterState( 4005): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 4005): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  904): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  904): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  904): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 4005): make
,I/BluetoothBondStateMachine( 4005): StableState(): Entering Off State
,D/HeadsetService( 4005): Received start request. Starting profile...
D/HeadsetStateMachine( 4005): Version 1.6
,D/HeadsetStateMachine( 4005): make
,I/ActivityManager(  904): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4031 uid=10037 gids={50037, 3002, 3001}
,I/HeadsetStateMachine( 4005): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 4005): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 4005): Received start request. Starting profile...
,V/Avrcp   ( 4005): make
,I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/Avrcp   ( 4005): fillIntentFilter()
,D/A2dpStateMachine( 4005): make
,D/A2dpStateMachine( 4005): Enter Disconnected: -2
,D/HidService( 4005): Received start request. Starting profile...
,D/HealthService( 4005): Received start request. Starting profile...
,D/PanService( 4005): Received start request. Starting profile...
,D/BluetoothTethering(  904): supplyMessenger
,D/BluetoothTethering(  904): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  904): got MESSAGE_CONNECT_PANSERVICE, call connect
D/PanService( 4005): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  904): got CMD_CHANNEL_HALF_CONNECTED
,D/HtcBtWidget_BTWidgetProvider( 4031): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4031): updateWidget(context) for widget: 
D/BtGatt.DebugUtils( 4005): handleDebugAction() action=null
D/BtGatt.GattService( 4005): Received start request. Starting profile...
D/BtGatt.GattService( 4005): start()
V/BluetoothPbapService( 4005): Pbap Service onCreate
,V/BluetoothPbapService( 4005): Starting PBAP service
,D/Process (  904): killProcessQuiet, pid=3085
,I/ActivityManager(  904): Killing 3085:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 11
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 11
E/BluetoothMasService( 4005): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 4005): Add permission for SmsProvider.
V/BluetoothMasService( 4005): Starting MAS instances
I/ActivityManager(  904): Recipient 3085
,D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 11
I/MailMessageReceiver( 4005): reg:com.android.bluetooth.btservice.AdapterApp@41e122d8 with com.htc.util.mail.MailMessageReceiver@41e52558
I/MailManager( 4005): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41e52558
V/EmailUtils( 4005): Manager Instance is not NULL
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  904): releaseWL(41e92c20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  904): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4050 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  904): interfaceAdded wlan0
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/Tethering(  904): wlan0 is not a tetherable iface, ignoring
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/Tethering(  904): interfaceAdded p2p0
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/Tethering(  904): p2p0 is not a tetherable iface, ignoring
D/Tethering(  904): interfaceLinkStateChanged p2p0, false
D/Tethering(  904): interfaceStatusChanged p2p0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/PMS     (  904): releaseWL(4277b838): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  904): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 4005): ============NULL aList========
,V/EmailUtils( 4005): <-getEmailAccountIdList
,V/BluetoothMasService( 4005): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 11
V/BluetoothMasService( 4005): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4005): Manager Instance is not NULL
,D/EmailUtils( 4005): ============NULL aList========
,V/EmailUtils( 4005): <-getEmailAccountIdList,
V/BluetoothSapService( 4005): Sap Service onCreate
V/BluetoothSapService( 4005): initBinder
V/BluetoothSapService( 4005): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41e57948
,V/BluetoothSapReceiver( 4005): BluetoothSapReceiver init
,D/BluetoothSapService( 4005): setSapService()
,V/BluetoothSapService( 4005): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4005): state: 12
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 11
D/BluetoothAdapterService( 4005): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4005): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4005): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4005): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 4005): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 4005): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothTethering(  904): got CMD_CHANNEL_FULLY_CONNECTED
D/HeadsetPhoneState( 4005): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterState( 4005): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/Process (  904): killProcessQuiet, pid=3469
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  904): Killing 3469:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/BluetoothMasReceiver( 4005): Bluetooth STATE CHANGED to 11
,I/ActivityManager(  904): Recipient 3469
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  904): Client com.google.android.music (pid 3469): Died!
,I/ActivityManager(  904): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4069 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4074): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,D/WifiMonitor(  904): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  904): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 4086): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4086): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4086): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4086): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4086): Get randomness: len=20 entropy=1
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4069): Received state change = 11
,I/qcom-bluetooth( 4093): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
D/wpa_supplicant( 4086): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4086): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4086): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4086): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4086): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4086): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4086): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4086): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4086): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4086): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4086): update_config=1
D/wpa_supplicant( 4086): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4086): device_name='Android_63cc'
D/wpa_supplicant( 4086): manufacturer='HTC'
D/wpa_supplicant( 4086): model_name='HTC_PHONE'
D/wpa_supplicant( 4086): model_number='1234'
D/wpa_supplicant( 4086): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4086): p2p_oper_reg_class=126
D/wpa_supplicant( 4086): p2p_oper_channel=36
D/wpa_supplicant( 4086): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4086): persistent_reconnect=1
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 3
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 3
,I/ActivityManager(  904): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4089 uid=10048 gids={50048}
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4086): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4086): nl80211: RFKILL status not available
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4086): nl80211: Using driver-based roaming
D/wpa_supplicant( 4086): nl80211: TDLS supported
D/wpa_supplicant( 4086): nl80211: TDLS external setup
D/wpa_supplicant( 4086): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4086): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4086): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4086): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4086): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4086): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4086): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a2d758
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a2d758
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4086): htc_wext_command_init +
E/wpa_supplicant( 4086): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4086): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4086): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4086): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4086): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4086): nl80211: Added 802.11b mode based on 802.11g information
I/qcom-bluetooth( 4100): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/Tethering(  904): interfaceLinkStateChanged p2p0, false
D/Tethering(  904): interfaceStatusChanged p2p0, false
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/Tethering(  904): interfaceLinkStateChang,ed p2p0, false
D/Tethering(  904): interfaceStatusChanged p2p0, false
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,I/qcom-bluetooth( 4104): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/WifiService(  904): New client listening to asynchronous messages
I/qcom-bluetooth( 4106): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
I/qcom-bluetooth( 4107): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 4108): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/Process (  904): killProcessQuiet, pid=3783
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3783:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/HtcWiFiWidget_WiFiWidgetProvider( 4089): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4089): updateWidget(context) for widget: 
,D/Process (  904): killProcessQuiet, pid=3451
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3451:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (3958/10189)
,I/ActivityManager(  904): Recipient 3451
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3783
,D/WifiService(  904): Client connection lost with reason: 4
,I/wpa_supplicant( 4086): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4086):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4086):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4086):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 4086): nl80211: Flush PMKIDs
E/wpa_supplicant( 4086): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4086): State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 4086): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 4086): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4086): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4086): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4086): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4086): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): Using existing control interface directory.
D/wpa_supplicant( 4086): ctrl_iface bind(PF_UNIX) failed: Address already in use,
D/wpa_supplicant( 4086): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
D/wpa_supplicant( 4086): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4086): P2P: Own listen channel: 11
D/wpa_supplicant( 4086): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4086): P2P: Add operating class 81,
,I/wpa_supplicant( 4086): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4086): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4086): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4086): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4086): ctrl_interface='/data/misc/wifi/sockets',
D/wpa_supplicant( 4086): disable_scan_offload=1
D/wpa_supplicant( 4086): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4086): update_config=1
D/wpa_supplicant( 4086): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4086): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4086): manufacturer='HTC'
D/wpa_supplicant( 4086): model_name='HTC Desire 820'
D/wpa_supplicant( 4086): model_number='HTC Desire 820',
D/wpa_supplicant( 4086): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4086): persistent_reconnect=1
D/wpa_supplicant( 4086): p2p_disabled=1
D/wpa_supplicant( 4086): hs20=1
D/wpa_supplicant( 4086): interworking=1
D/wpa_supplicant( 4086): Line: 18 - start of a new network block
D/wpa_supplicant( 4086): key_mgmt: 0x2
D/wpa_supplicant( 4086): priority=1 (0x1),
,D/wpa_supplicant( 4086): signinfail=0 (0x0)
,D/wpa_supplicant( 4086): Priority group 1,
D/wpa_supplicant( 4086):    id=0 ssid='NG700'
I/wpa_supplicant( 4086): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4086): nl80211: RFKILL status not available
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4086): nl80211: Using driver-based roaming
D/wpa_supplicant( 4086): nl80211: TDLS supported
D/wpa_supplicant( 4086): nl80211: TDLS external setup
D/wpa_supplicant( 4086): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4086): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4086): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4086): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4086): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4086): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4086): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a3d718
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4086): htc_wext_command_init +
I/wpa_supplicant( 4086): htc_wext_command_init -
,I/wpa_supplicant( 4086): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4086): Don't set 00 to countryID.conf
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4086): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4086): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4086): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4086): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5490-5710 @ 80 MHz
,D/wpa_supplicant( 4086): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4086): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false,
,I/qcom-bluetooth( 4111): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4112): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 4005): btu_task pending for preload complete event
,I/wpa_supplicant( 4086): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4086):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4086):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4086):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4086): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4086): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4086): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4086): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4086): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4086): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4086): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4086): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4086): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4086): Using existing control interface directory.
,I/wpa_supplicant( 4086): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4086): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4086): Auto country group 1: ch36
I/wpa_supplicant( 4086): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING - ret = 0
V/RegulatoryObserver(  904): uevent:
V/RegulatoryObserver(  904): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  904): Regulatory Country Code:DE
D/wpa_supplicant( 4086): random: Got 18/20 bytes from /dev/random
I/wpa_supplicant( 4086): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_904-2
D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4086): nl80211: Event message available
D/wpa_supplicant( 4086): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4086): nl80211: Regulatory domain change
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4086): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4086): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4086): P2P: Add operating class 81
D/wpa_supplicant( 4086): P2P: Add operating class 115
D/wpa_supplicant( 4086): P2P: Add operating class 116
D/wpa_supplicant( 4086): P2P: Add operating class 117
D/wpa_supplicant( 4086): P2P: Update channel list
D/wpa_supplicant( 4086): p2p0: Updating hw mode
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4086): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4086): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4086): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4086): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4086): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 4086): wpa_supplicant_scan enter
I/wpa_supplicant( 4086): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4086): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4086): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4086): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4086): nl80211: Event message available
,D/wpa_supplicant( 4086): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 4086): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 4086): Get randomness: len=20 entropy=0
D/WifiNative-wlan0(  904): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/wpa_supplicant( 4086): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): set wifi ON
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER MACADDR
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
V/RegulatoryObserver(  904): Start wifi-crda service to run crda.
V/RegulatoryObserver(  904): Country Code is DE
V/RegulatoryObserver(  904): Send broadcast country code message.
I/RegulatoryObserver(  904): Broadcast intent for crda country code: DE
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
,D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED enabled
,D/WirelessDisplayService(  904): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  904): Loading config and enabling all networks
D/HtcWiFiWidget_WiFiWidgetProvider( 4089): onWiFiStateChanged() for widget: 
D/WifiNative-wlan0(  904): doString: LIST_NETWORKS
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): list_network_info: ret=0x1, pos=0xb7a40117 buf=0xb7a400e8
,I/wpa_supplicant( 4086): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4086): 0	NG700	any	
D/HtcWiFiWidget_WiFiWidgetProvider( 4089): updateWidget(context) for widget: 
,D/WifiNative-wlan0(  904):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  904): 0	NG700	any	
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 ssid
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 bssid
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 priority
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
,D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 user_cert_file
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_psk'
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 psk
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='psk'
,D/wpa_supplicant( 4086): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 proto
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  904): Failed to look-up a string: W
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
,D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  904): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 group
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  904): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  904): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  904): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  904): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  904): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  904): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 limited
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 eap
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'eap'
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 phase2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 identity
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 password
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
,D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 engine
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 key_id
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  904): doString: GET_NETWORK 0 private_key
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4086): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  904): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  904): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
,D/wpa_supplicant( 4086): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4086): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET manufacturer HTC
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4086): manufacturer='HTC'
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4086): model_name='HTC Desire 820'
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4086): model_number='HTC Desire 820'
D/WifiNative-wlan0(  904):    returned true
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (3958/10189)
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4086): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET auto_interworking 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4086): auto_interworking=0
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: STATUS
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): SET_SCREEN_ON:On
I/wpa_supplicant( 4086): htc_wext_set_keepalive +
I/wpa_supplicant( 4086): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4086): getPrivFuncNum +	
I/wpa_supplicant( 4086): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: S,ET ps 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4086): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
W/Settings(  904): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  904): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE: field=AIR_MODE id=0
D/libc    (  904): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): SETBAND: 0
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4086): P2P: Add operating class 81
D/wpa_supplicant( 4086): P2P: Add operating class 115
D/wpa_supplicant( 4086): P2P: Add operating class 116
D/wpa_supplicant( 4086): P2P: Add operating class 117
D/wpa_supplicant( 4086): P2P: Update channel list
I/wpa_supplicant( 4086): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4086): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4086): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4086): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4086): p2p_oper_reg_class=126
D/wpa_supplicant( 4086): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4086): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4086): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4086): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4086): p2p_oper_channel=36
E/wpa_supplicant( 4086): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4086): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4086): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4086): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4086): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: BSS_FLUSH 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/WifiMonitor(  904): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  904): doBoolean: SET persistent_reconnect 1
D/WifiP2pService(  904): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnablingState
D/WifiP2pService(  904): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2p socket connection successful
D/WifiP2pService(  904): P2pEnabledState
D/WifiP2pService(  904): sending p2p connection changed broadcast
D/WifiDisplayController(  904): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  904): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  904):    returned false
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/wpa_supplicant( 4086): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4086): persistent_reconnect=1
I/wpa_supplicant( 4086): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-wlan0(  904): doBoolean: SET pno 0
D/WifiNative-p2p0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/WifiNative-p2p0(  904): doBoolean: SET device_name Android_63cc
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4086): wpa_supplicant_scan enter
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4086): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4086): device_name='Android_63cc'
I/wpa_supplicant( 4086): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4086): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4086): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4086): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4086): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4086): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4086): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4086): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4086): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4086): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  904): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4086): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4086): Single channel concurrency preference: sta
I/wpa_supplicant( 4086): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doString: STATUS
W/WifiHW  (  904): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  904): doBoolean: P2P_FLUSH
W/WifiHW  (  904): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4086): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4086): P2P: Stopping find
D/wpa_supplicant( 4086): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4086): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4086): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  904): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/WifiDisplayController(  904): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  904): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiStateMachine(  904): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  904): Send p2p flush in initializeP2pSettings
I/wpa_supplicant( 4086): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4086): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doString: LIST_NETWORKS
W/WifiHW  (  904): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
I/wpa_supplicant( 4086): list_network_info: ret=0x22, pos=0xb7a4010a buf=0xb7a400e8
I/wpa_supplicant( 4086): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4086): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  904):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  904): doBoolean: AP_SCAN 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  904):    returned false
D/WifiNative-p2p0(  904): doBoolean: SET wifi_display 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4086): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4086): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4086): WFD: Update WFD IE
I/wpa_supplicant( 4086): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4086): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  904):    returned true
D/WifiNative-p2p0(  904): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  904): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4086): WFD: Set subelement 0
D/wpa_supplicant( 4086): WFD: Update WFD IE
I/wpa_supplicant( 4086): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4086): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  904):    returned true
V/AudioService(  904): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  904):     Client/Owner: Client
V/AudioService(  904):     GroupId: 
V/AudioService(  904):     Passphrase: 
V/AudioService(  904):     SessionId: 0
V/AudioService(  904):     IP Address: }
D/HtcEffectManagerBase(  904): onEventChanged id=5 status=false
D/HtcEffectManager(  904): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  904): convertEffect before=902
D/HtcEffectManager(  904): convertEffect after=902
D/WifiDisplayController(  904): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  904):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  904):  primary type: 10-0050F204-5
D/WifiDisplayController(  904):  secondary type: null
D/WifiDisplayController(  904):  wps: 0
D/WifiDisplayController(  904):  grpcapab: 0
D/WifiDisplayController(  904):  devcapab: 0
D/WifiDisplayController(  904):  status: 3
D/WifiDisplayController(  904):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  904):  WFD CtrlPort: 0
D/WifiDisplayController(  904):  WFD MaxThroughput: 0
D/WifiP2pService(  904): sending p2p persistent groups changed broadcast
D/WifiP2pService(  904): InactiveState
D/WifiP2pService(  904): InactiveState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  904):  WFD CtrlPort: 7236
D/WifiP2pService(  904):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  904):  WFD CtrlPort: 7236
D/WifiP2pService(  904):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  904): Successfully set WFD info.
I/WifiDisplayController(  904): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
D/WifiDisplayController(  904): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  904):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiDisplayController(  904):  primary type: 10-0050F204-5
D/WifiDisplayController(  904):  secondary type: null
D/WifiDisplayController(  904):  wps: 0
D/WifiDisplayController(  904):  grpcapab: 0
D/WifiDisplayController(  904):  devcapab: 0
D/WifiDisplayController(  904):  status: 3
D/WifiDisplayController(  904):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  904):  WFD CtrlPort: 7236
D/WifiDisplayController(  904):  WFD MaxThroughput: 50
,D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/Tethering(  904): interfaceLinkStateChanged p2p0, false
,D/Tethering(  904): interfaceStatusChanged p2p0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4086): nl80211: Event message available
D/wpa_supplicant( 4086): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4086): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4086): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 4086): nl80211: Survey data missing
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4086): Sorted scan results
I/wpa_supplicant( 4086): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 4086): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 4086): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-49
D/wpa_supplicant( 4086): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 4086): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4086): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4086): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4086): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4086): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4086): wpa_supplicant_pick_network+
I/wpa_supplicant( 4086): Selecting BSS from priority group 1
I/wpa_supplicant( 4086): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4086): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4086): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4086): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4086): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4086):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4086):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-49
I/wpa_supplicant( 4086): Start print parameters
I/wpa_supplicant( 4086): wpa_s->wpa_state is 3
I/wpa_supplicant( 4086): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4086): isConcurrentMode() is 0
I/wpa_supplicant( 4086): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4086): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4086): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4086): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4086): wpa_s->reassociate is 0
I/wpa_supplicant( 4086): wpa_s->is_screen_on 1
I/wpa_supplicant( 4086): wpa_s->ifname wlan0
I/wpa_supplicant( 4086): End print parameters
I/wpa_supplicant( 4086): selected network = 2
D/wpa_supplicant( 4086): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a3e4e8  current_ssid=0x0
D/wpa_supplicant( 4086): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4086): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4086): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4086): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4086): check if in concurrent case
,I/wpa_supplicant( 4086): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4086): wpa_supplicant_associate, 1777
,D/wpa_supplicant( 4086): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4086): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4086): RSN: PMKSA cache search - network_ctx=0xb7a3e4e8 try_opportunistic=0
D/wpa_supplicant( 4086): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4086): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4086): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4086): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4086): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4086): nl80211: Unsubscribe mgmt frames handle 0xb7a3d718 (mode change)
D/wpa_supplicant( 4086): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a3d718
,D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Register frame type=0xd0 nl_handle=0xb7a3d718
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4086): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4086):   * bssid=c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4086):   * freq=2412
D/wpa_supplicant( 4086):   * Auth Type 0
D/wpa_supplicant( 4086):   * WPA Versions 0x2
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4086): nl80211: Connect request send successfully
D/wpa_supplicant( 4086): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4086): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 4086): reply (351) for get BSS: id=0
I/wpa_supplicant( 4086): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4086): freq=5220
I/wpa_supplicant( 4086): level=-48
I/wpa_supplicant( 4086): tsf=0000000093861027
I/wpa_supplicant( 4086): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4086): ssid=NG7005g
I/wpa_supplicant( 4086): ====
I/wpa_supplicant( 4086): id=1
I/wpa_supplicant( 4086): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 4086): freq=2412
I/wpa_supplicant( 4086): level=-49
I/wpa_supplicant( 4086): tsf=0000000093861037
I/wpa_supplicant( 4086): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4086): ssid=01ABC
I/wpa_supplicant( 4086): ====
I/wpa_supplicant( 4086): id=2
I/wpa_supplicant( 4086): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4086): freq=2412
I/wpa_supplicant( 4086): level=-49
I/wpa_supplicant( 4086): tsf=0000000093861041
I/wpa_supplicant( 4086): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4086): ssid=NG700
I/wpa_supplicant( 4086): ####
,D/WirelessDisplayService(  904): getDiscoveryDongleList,
D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (3) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 93861027, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 93861037, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 2412, timestamp: 93861041, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 3 to mScanResults
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4086): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4086): nl80211: Event message available
D/wpa_supplicant( 4086): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4086): nl80211: Connect event
D/wpa_supplicant( 4086): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4086): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4086): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4086): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4086): Add randomness: count=5 entropy=3
I/wpa_supplicant( 4086): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4086): TDLS: Remove peers on association
D/wpa_supplicant( 4086): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 4086): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4086): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4086): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4086): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 4086): Get randomness: len=32 entropy=4
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 B,SSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  904): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Associated
I/wpa_supplicant( 4086): htc_wext_set_keepalive +
I/wpa_supplicant( 4086): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4086): getPrivFuncNum +	
I/wpa_supplicant( 4086): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4086): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/Tethering(  904): [isWifi] getHotspotEnabled: false,
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  904): This record is existed, only update it...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...,
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  904): updateConnectedAP...,
,I/wpa_supplicant( 4086): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a3d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4086):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4086): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4086): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f22b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4086):    broadcast key
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4086): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4086): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4086): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4086): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 4086): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
E/wpa_supplicant( 4086): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4086): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4086): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/wpa_supplicant( 4086): set send_ind_to_ndc = 0
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4086): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4086): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4086): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4086): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4086): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4086): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4086): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4086): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4086): EAPOL authentication completed successfully
I/wpa_supplicant( 4086): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4086): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4086): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4086): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false,
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  904): interfaceStatusChanged wlan0, true,
D/WifiStateMachine(  904): This record is existed, only update it...
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...,
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1754/10178)
,D/WISPrService( 3406): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3406): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 4086): EAPOL: disable timer tick
D/wpa_supplicant( 4086): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4086): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 18
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiService(  904): New client listening to asynchronous messages
,I/HtcModeClient( 1472): handler message = 4011
,E/HtcModeClient( 1472): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1472): Don't start project servcice
,D/HtcModeClient( 1472): setEject: MEDIA_EJECT_STATE = true
D/DhcpStateMachine(  904): [StoppedState] Start DHCP
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/HtcModeClient( 1472): connectState: CONNECTION_READY = false
D/SilentMusic( 1472): call stop
,D/HtcModeClient( 1472): close connection
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
W/HtcModeClient( 1472): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1472): read the terminate packet, so break
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/Process (  904): killProcessQuiet, pid=1472
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  904): doBoolean: MOBILE_TYPE Unknown
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  904):    returned true
I/ActivityManager(  904): Killing 1472:com.htc.bgp/u0a14 (adj 15): empty #17
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): Power_Mode_Type mode = 1
I/wpa_supplicant( 4086): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
,D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED -1 -> 3
D/PMS     (  904): acquireWL(433d1f30): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4388ec80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4388ec80 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1107): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActivityManager(  904): Recipient 1472
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/bt-btu  ( 4005): btu_task received preload complete event
,D/bt-btm  ( 4005): btm_acl_device_down
D/bt-btm  ( 4005): btm_acl_reset_paging
,D/bt-btm  ( 4005): btm_acl_set_discing
,I/bt-btm  ( 4005): btm_reset_complete
,I/bt-btm  ( 4005): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 4005): Start reading local supported commands
,D/bt-btm  ( 4005): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 4005): BTM reads next extended features page (1)
,D/bt-btm  ( 4005): BTM reads next extended features page (2)
D/bt-btm  ( 4005): BTM reached last extended features page (2)
,D/bt-btm  ( 4005): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 4005): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 4005): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 4005): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 4005): btm_read_ble_wl_size 
D/bt-btm  ( 4005): btm_read_white_list_size_complete 
,D/bt-btm  ( 4005): btm_get_ble_buffer_size 
D/bt-btm  ( 4005): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 4005): btm_read_ble_local_supported_features 
D/bt-btm  ( 4005): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 4005): btm_reset_ctrlr_complete: max_page_number: 2
,D/bt-btm  ( 4005): btm_decode_ext_features_page page: 0
D/bt-btm  ( 4005): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 4005): Local supported SCO packet types: 0x038f
,D/bt-btm  ( 4005): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 4005): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 4005):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
,D/bt-btm  ( 4005): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 4005): BTM_SetInquiryMode
I/bt-btm  ( 4005): BTM_SetPageScanType
I/bt-btm  ( 4005): BTM_SetInquiryScanType
,D/bt-btm  ( 4005): btm_decode_ext_features_page page: 1
D/bt-btm  ( 4005): btm_decode_ext_features_page page: 2
,D/bt-btm  ( 4005): BTM_BleLoadLocalKeys
D/bt-btm  ( 4005): BTM_BleLoadLocalKeys
I/bt-btm  ( 4005): BTM_Sec: application registered
E/bt-btm  ( 4005): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fa3941 
,I/bt-btm  ( 4005): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 4005): SMP_Register state=0
,E/bt-btm  ( 4005): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fa3941 
I/bt-btm  ( 4005): BTM_Sec: application registered
D/bt-btm  ( 4005): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 4005): BTM: BTM_WritePageTimeout: Timeout: 8192.
,D/bt-btm  ( 4005): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 4005): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 4005): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 4005): BTM_RegBusyLevelNotif
,I/bt-att  ( 4005): GATT_Register
D/bt-att  ( 4005): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 4005): allocated gatt_if=3
I/bt-att  ( 4005): GATT_StartIf gatt_if=3
D/bt-att  ( 4005): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 4005): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
E/bt-btif ( 4005): Calling BTA_HhEnable
I/bt-btm  ( 4005): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 4005): BTM_AllocateSCN
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 4005): BTM_AllocateSCN
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btm  ( 4005): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4005):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4005):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4005): btif_storage_get_adapter_property service_mask:0x140040
E/bt-btif ( 4005): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btm  ( 4005): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 4005):                : sec: 0x3092,opervice na
I/bt-btm  ( 4005):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4005):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4005):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 4005): AVRC_AddRecord uuid: 110c
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:2 len:6
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 4005): A2D_AddRecord uuid: 110a
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
D/bt-avp  ( 4005): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 4005): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btm  ( 4005): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4005):                : sec: 0x80, service name, [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4005):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4005): BTM_GetHCIConnHandle
I/bt-btm  ( 4005): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 4005): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 4005): GATT_Register
D/BluetoothAdapterProperties( 4005): Address is:80:01:84:8A:B3:68
D/bt-att  ( 4005): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 4005): allocated gatt_if=4
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:1 len:14
I/bt-att  ( 4005): GATT_StartIf gatt_if=4
D/bt-att  ( 4005): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 4005): gatt_find_the_connected_bda found=0 found_idx=7
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 4005): Scan Mode:20
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4005): Discoverable Timeout:120
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapter( 4005): getBluetoothService(): entry
D/BluetoothAdapter( 4005): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 4005): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e62800
D/BluetoothDevice( 4005): getService : Register callback
,D/BluetoothAdapterProperties( 4005): Adding bonded device:B4:CE:F6:AB:A4:6A
,D/BluetoothAdapterProperties( 4005): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 4005): Adding bonded device:34:FC:EF:9D:93:0B
,D/BluetoothAdapterProperties( 4005): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 4005): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 4005): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
,I/bt-btif ( 4005): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4005): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 4005): Remote class is:5898764
I/bt-btif ( 4005): BTA_JvEnable
I/bt-btm  ( 4005): BTM_ReadConnectability
I/bt-btm  ( 4005): BTM_ReadDiscoverability
I/bt-btm  ( 4005): BTM_SetDiscoverability
I/bt-btm  ( 4005): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 4005): br_edr_supported=0x2
I/bt-btm  ( 4005): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4005): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 4005): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4005): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4005): BTM_SetConnectability
I/bt-btm  ( 4005): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4005): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 4005): BTM_SetDiscoverability
I/bt-btm  ( 4005): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4005): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4005): br_edr_supported=0x0
I/bt-btm  ( 4005): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4005): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4005): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 4005): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4005): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 4005): BTM_SetConnectability
I/bt-btm  ( 4005): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4005): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 4005): bta_pan_co_init
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 4005): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4005):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4005):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 4005): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4005):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4005): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4005):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
,I/bt-btif ( 4005): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4005): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4005): ScanMode =  20
D/BluetoothAdapterProperties( 4005): State =  11
I/bt-btm  ( 4005): BTM_SetDiscoverability
I/bt-btm  ( 4005): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4005): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4005): br_edr_supported=0x0
I/bt-btm  ( 4005): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4005): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4005): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4005): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4005): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4005): BTM_SetConnectability
I/bt-btm  ( 4005): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4005): new flag=0x0 cur flag=0x4
D/bt-btm  ( 4005): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 4005): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4005): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4005): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 4005): Setting state to 12
I/bt-btif ( 4005): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 4005): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService( 4005): Broadcasting updateAdapterState() to 1 receivers.
,E/bt_mct  ( 4005): hci lib postload completed
D/BluetoothAdapterProperties( 4005): Scan Mode:21
I/bt-btif ( 4005): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4005): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4005): Discoverable Timeout:120
D/BluetoothManagerService(  904): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  904): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  904): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 4005): Entering On State
,D/BluetoothHeadset( 1217): Proxy object connected
,D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1105314304)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4005): getBondedDevices: length=6
,D/BluetoothHeadset( 1107): Proxy object connected
I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@42111ea0
,D/BluetoothPan(  904): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
,D/BluetoothPan(  904): BluetoothPAN Proxy object connected
,D/BluetoothAdapterService(1105314304)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4005): getBondedDevices: length=6
D/BluetoothHeadset( 1217): Proxy object connected
,D/BluetoothPhoneService( 1217): BluetoothHeadset onServiceConnected
,D/BluetoothAdapter( 1217): 1106615656: getState(). Returning 12
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothHeadset(  904): onBluetoothStateChange: up=true
D/BluetoothA2dp(  904): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  904): Proxy object connected
,D/BluetoothManagerService(  904): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothAdapter(  904): 1114525376: getState(). Returning 12
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,V/BluetoothPbapReceiver( 4005): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 4005): ***********state = 12
,D/BluetoothMasReceiver( 4005): Bluetooth STATE CHANGED to 12
,D/BluetoothA2dp(  904): Proxy object connected
,V/BluetoothSapReceiver( 4005): SapReceiver onReceive 
V/BluetoothSapReceiver( 4005): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 4005):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 4005): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  904): acquireWL(43bcbd08): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3406 1000 null
,W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothAdapter(  904): 1114525376: getState(). Returning 12
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 12
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 12
V/BluetoothMasService( 4005): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4005): Manager Instance is not NULL
,D/HtcBtWidget_BTWidgetProvider( 4031): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4031): updateWidget(context) for widget: 
W/System.err(  904): java.lang.Throwable: stack dump
D/PMS     (  904): releaseWL(43bcbd08): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  904): acquireWL(42eea1b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3406 1000 null
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43514ad8:true
,D/BluetoothManagerService(  904): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  904): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  904): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/LocationAgent( 3406): new LocationAgent instance!!
,D/HtcTagManager( 3406): HtcTagManager construction complete
D/EmailUtils( 4005): ============NULL aList========
,V/EmailUtils( 4005): <-getEmailAccountIdList
,V/BluetoothSapService( 4005): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 4005): state: 12
,D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 12
,W/ContextImpl( 4005): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
,D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,V/BluetoothSapService( 4005): Starting SAP server process
,V/BluetoothPbapService( 4005): Handler(): got msg=1
,V/BluetoothPbapService( 4005): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 4005): Pbap Service initSocket
,V/BluetoothMasService( 4005): handleMessage: mIsEmailEnabledtrue
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3406): BluetoothInputDevice()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 7
D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/BluetoothInputDevice( 3406): BluetoothInputDevice(): Binding service...
D/BluetoothAdapter( 4005): getBluetoothService(): entry
,W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
,V/BtMns   ( 4005): BluetoothMns: isEmailEnabled: true
E/BluetoothServiceJni( 4005): SOCK FLAG = 1 ***********************
I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 4005):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 4005): Succeed to create listening socket 
,V/BluetoothPbapService( 4005): Accepting socket connection...
,D/BluetoothMasService( 4005): Map_prev 1
,W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothPan( 3406): BluetoothPan()
D/BluetoothAdapter( 1107): 1108007968: getState(). Returning 12
D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothAdapter( 4005): getBluetoothService(): entry
D/BluetoothAdapter( 1107): 1108007968: getState(). Returning 12
W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
D/BluetoothPan( 3406): BluetoothPan(): Binding service...
E/BluetoothServiceJni( 4005): SOCK FLAG = 3 ***********************
I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 4005):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/BluetoothManagerService(  904): Registered receivers: 8
,D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothMap( 3406): Create BluetoothMap proxy object
D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  904): Registered receivers: 9
D/BluetoothAdapter( 4005): getBluetoothService(): entry
,W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothMap( 3406): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
E/BluetoothServiceJni( 4005): SOCK FLAG = 3 ***********************
I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 4005):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3406): BluetoothSap() call bindService
,D/BluetoothManagerService(  904): Registered receivers: 10
,D/BluetoothPbap( 3406): BluetoothPbap()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 11
D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/BluetoothPbap( 3406): BluetoothPbap(): Binding service...
W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothA2dp( 3406): BluetoothA2dp()
D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  904): Registered receivers: 12
D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/BluetoothA2dp( 3406): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3406): BluetoothHeadset()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 13
D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/BluetoothHeadset( 3406): BluetoothHeadset(): Binding service...
,W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,D/BluetoothAdapter( 1107): 1108007968: getState(). Returning 12
,D/HtcTagManager( 3406): startProxy
,I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
,W/ContextImpl( 3406): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3406): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
W/ContextImpl( 3406): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
,D/DockEventReceiver( 3406): finishStartingService: stopping service
D/BluetoothPan( 3406): BluetoothPAN Proxy object connected
D/PanProfile( 3406): Bluetooth service connected
D/BluetoothA2dp( 3406): Proxy object connected
,D/A2dpProfile( 3406): Bluetooth service connected
,D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/BluetoothSapService( 4005): Sap_prev 1
,V/BluetoothSapService( 4005): SAP Service startRfcommListenerThread
D/BluetoothHeadset( 3406): Proxy object connected
,V/BluetoothSapService( 4005): Sap Service initRfcommSocket
,D/HeadsetProfile( 3406): Bluetooth service connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4069): onCreate: going to find gatt base service first.
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
V/TAG     ( 4005): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 4005): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41e59088
D/BluetoothAdapter( 4005): getBluetoothService(): entry
,W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 4005): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 4005):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 4005): Succeed to create listening socket 
V/BluetoothSapService( 4005): Accepting socket connection...
,D/BluetoothInputDevice( 3406): Proxy object connected
,D/HidProfile( 3406): Bluetooth service connected
,D/BluetoothAdapter( 3406): 1106925976: getState(). Returning 12
,D/SapServerProfile( 3406): Bluetooth service connected
,D/PMS     (  904): releaseWL(42eea1b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/wpa_supplicant( 4086): EAPOL: startWhen --> 0
D/wpa_supplicant( 4086): EAPOL: disable timer tick
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f6b498:true
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/[HTC_BLE][Constants]( 4069):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4069):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4069):  + discoverServicesOnBonded = false
V/BluetoothPbapService( 4005): Pbap Service onBind
D/BluetoothPbap( 3406): Proxy object connected
D/PbapServerProfile( 3406): Bluetooth service connected
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4069):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4069): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e171c8
D/[HTC_BLE][Constants]( 4069): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4069): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4069): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4069): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4069): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4069): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4069): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/BluetoothFtpService( 4005): Ftp Service onCreate
,D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 12
,D/BluetoothMasReceiver( 4005): Bluetooth STATE CHANGED to 12
,D/HtcTagManager( 3406): onServiceConnected
D/HtcTagProfile( 3406): setup proxy
D/HtcPxpProfile( 3406): setup proxy
,D/HtcFmpProfile( 3406): setup proxy
D/BluetoothAdapter( 4005): getBluetoothService(): entry
,W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothFtpService( 4005): Ftp_prev 1
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4069): Received state change = 12
E/BluetoothServiceJni( 4005): SOCK FLAG = 0 ***********************
,I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 4005):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 4005): Accept thread started.
,D/BluetoothAdapter( 4005): getBluetoothService(): entry
,W/BluetoothAdapter( 4005): getBluetoothService() called with no BluetoothManagerCallback
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4069): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4069): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e171c8
,D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4069): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e171c8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4069): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e171c8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e221b0
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4069): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e171c8
E/BluetoothServiceJni( 4005): SOCK FLAG = 1 ***********************
I/bt-btif ( 4005): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4005): SDP_CreateRecord ok, num_records:16
,I/bt-btm  ( 4005): Write Extended Inquiry Response to controller
,I/bt-btif ( 4005): BTA_JvRfcommStartServer
I/bt-btm  ( 4005): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 4005):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 4005): Run Accept thread
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4005): 1105332480: getState(). Returning 12
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
V/BluetoothMasService( 4005): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4005): Manager Instance is not NULL
,D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425bb710:true
,I/LocationAgent( 3926): new LocationAgent instance!!
D/EmailUtils( 4005): ============NULL aList========
,V/EmailUtils( 4005): <-getEmailAccountIdList
,D/BluetoothMasService( 4005): Map_prev 1
,D/HtcTagManager( 3926): HtcTagManager construction complete
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothInputDevice( 3926): BluetoothInputDevice()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 14
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothInputDevice( 3926): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3926): BluetoothPan()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothPan( 3926): BluetoothPan(): Binding service...
,D/BluetoothManagerService(  904): Registered receivers: 15
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/BluetoothMap( 3926): Create BluetoothMap proxy object
D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothMap( 3926): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  904): Registered receivers: 16
D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothSap( 3926): BluetoothSap() call bindService
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 17
,D/BluetoothPbap( 3926): BluetoothPbap()
D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 18
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothPbap( 3926): BluetoothPbap(): Binding service...
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothA2dp( 3926): BluetoothA2dp()
D/BluetoothManagerService(  904): registerStateChangeCallback+
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  904): Registered receivers: 19
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothA2dp( 3926): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3926): BluetoothHeadset()
,D/BluetoothManagerService(  904): registerStateChangeCallback+
,D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  904): Registered receivers: 20
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothHeadset( 3926): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3926): startProxy
,W/ContextImpl( 3926): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3926): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3926): setBluetoothStateOn
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
D/HtcTagManager( 3926): startProxy
D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
D/BluetoothAdapterService(1105314304)( 4005): Get Bonded Devices being called
D/BluetoothAdapterProperties( 4005): getBondedDevices: length=6
D/BluetoothAdapter( 3926): getBluetoothService(): entry
D/BluetoothAdapter( 3926): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3926): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e5d870
D/BluetoothDevice( 3926): getService : Register callback
E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): addHtcTagProfiles
,D/RingtoneManager( 4069): getExternalStorageState=mounted
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[2]: Feverfew
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[3]: Foxglove
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[4]: Goldenrod
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[8]: Olive
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4069):  + mAlertUri: content://settings/system/alarm_alert
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4069): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4069): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4069): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4069): initScanModeInterface: true
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43898cd0:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4069): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4069):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 4069):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4069):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4069):  + discoverServicesOnBonded = false
,E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4069): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e221b0
,D/HtcTagManager( 3926): addHtcTagProfiles
,E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): addHtcTagProfiles
,E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): addHtcTagProfiles
,E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): addHtcTagProfiles
,E/BluetoothDevice( 3926): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): addHtcTagProfiles
,D/BluetoothInputDevice( 3926): Proxy object connected
D/HidProfile( 3926): Bluetooth service connected
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothPan( 3926): BluetoothPAN Proxy object connected
,D/PanProfile( 3926): Bluetooth service connected
D/SapServerProfile( 3926): Bluetooth service connected
D/BluetoothPbap( 3926): Proxy object connected
D/PbapServerProfile( 3926): Bluetooth service connected
,D/BluetoothA2dp( 3926): Proxy object connected
,D/A2dpProfile( 3926): Bluetooth service connected
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/BluetoothHeadset( 3926): Proxy object connected
,D/HeadsetProfile( 3926): Bluetooth service connected
,D/BluetoothAdapter( 3926): 1105346936: getState(). Returning 12
,D/HtcTagManager( 3926): onServiceConnected
D/HtcTagProfile( 3926): setup proxy
D/HtcPxpProfile( 3926): setup proxy
,D/HtcFmpProfile( 3926): setup proxy
,I/SensorManager(  904): mEventCount = 750
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4086): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
D/PMS     (  904): releaseWL(433d1f30): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): gateway: /192.168.1.1
,D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -48, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20337 delay=15s
,D/WifiWatchdogStateMachine(  904): WAN detection
,D/WISPrService( 3406): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1754/10178)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@42733660
,D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  904): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/PMS     (  904): acquireWL(433e58f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
I/QuickSettingWifi( 1107): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(433e58f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  904): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiNative-wlan0(  904):    returned true
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4186 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  904): Found interface wlan0
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
I/ConnectivityHelper( 1243): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1772/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(42234068): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1754/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3491/10051)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1243/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1392/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (3856/10100)
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =af52 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(4265dee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (3856/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): acquireWL(4287cc10): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 904 1000 WorkSource{10096}
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4203 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  904): releaseWL(4287cc10): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 102
D/libc    (  364): [NET]res_nsend:resplen=104
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/PMS     (  904): acquireWL(439129d0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 904 1000 WorkSource{10096}
,D/PMS     (  904): acquireWL(427a1f20): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 904 1000 WorkSource{10160}
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/MusicStore( 4186): Database version: 95
D/PMS     (  904): releaseWL(4265dee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/ContextImpl( 4186): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/IntentController( 1107): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1533): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1243): updateLastUpdatedTime(in String) LAST UPDATED 11:28
,D/DotMatrix( 1533): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
,W/ContextImpl( 4186): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4186): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(423caee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(423caee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43b0e568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/GpsLocationProvider(  904): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  904): NTP server returned: 1454063376654 (Fri Jan 29 11:29:36 CET 2016) reference: 97439 certainty: 12 system time offset: -73
,D/GpsLocationProvider(  904): [handleMessage] INJECT_NTP_TIME_FINISHED
,D/DelayedSyncController( 4203): Delaying sync.
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3958): 
D/PMS     (  904): releaseWL(43b0e568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(43c96bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(43c96bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  904): releaseWL(42234068): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(440d1f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(439129d0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4186): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4186): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  904): acquireWL(436c79e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 904 1000 WorkSource{10096}
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4229 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(43f45bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{426485b8: PendingIntentRecord{42734408 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454063376751, Int=60000
,D/PMS     (  904): releaseWL(43f45bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4186, uid=10154, userID:0
,D/PMS     (  904): releaseWL(440d1f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(438b47a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/DelayedSyncController( 4203): Delaying sync.
D/PMS     (  904): releaseWL(438b47a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(43f67738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/PMS     (  904): releaseWL(436c79e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  904): releaseWL(43f67738): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43b4af40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/SMSBackup( 4229): SMSBackupAgentService started
,D/SMSBackup( 4229): Checking restore status
D/SMSBackup( 4229): Restore complete
,D/SMSBackup( 4229): cancelCheckAlarm
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
D/PMS     (  904): releaseWL(427a1f20): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/MediaRouterService(  904): Client com.google.android.music (pid 4186): Registered
D/PMS     (  904): releaseWL(43b4af40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
I/MediaRouter( 4186): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/SMSBackup( 4229): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3825
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3825:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3825
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (4186/10154)
,I/NetworkMonitor( 4186): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4246 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4186): getSelectedRoute
,I/NetworkMonitor( 4186): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4186/10154)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/Process (  904): killProcessQuiet, pid=1372
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4186, uid=10154, userID:0
I/ActivityManager(  904): Killing 1372:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 1372
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4246): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4246): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4246): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4246): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4246): Preparing secondary program dexes.
,V/DexLibLoader( 4246): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4246): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4246): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4246): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4246): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4246): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4246): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4246): Dex already copied
D/OdexVerifier( 4246): Odex verification is skipped.
,V/DexLibLoader( 4246): Creating class loader
,V/DexLibLoader( 4246): Finished creating class loader
,V/DexLibLoader( 4246): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4246): Dex already copied
D/OdexVerifier( 4246): Odex verification is skipped.
,V/DexLibLoader( 4246): Creating class loader,
,V/DexLibLoader( 4246): Finished creating class loader
V/DexLibLoader( 4246): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4246): Dex already copied
D/OdexVerifier( 4246): Odex verification is skipped.
,V/DexLibLoader( 4246): Creating class loader
,V/DexLibLoader( 4246): Finished creating class loader
,V/DexLibLoader( 4246): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4246): Dex already copied
,D/OdexVerifier( 4246): Odex verification is skipped.
,V/DexLibLoader( 4246): Creating class loader
,V/DexLibLoader( 4246): Finished creating class loader
,V/DexLibLoader( 4246): Verifying classes from secondary dexes.
,D/DexLibLoader( 4246): DexLibLoader.ensureDexLoaded took 94 ms
,E/BTIF_CORE( 4005): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 4005): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 4005): Wake lock released
,D/WIFI_ICON( 1107): WifiActivity: 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3958): 
,W/dalvikvm( 4246): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4246): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4246): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4246): Verify
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =add2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/23.59.123.86
D/WifiService(  904): New client listening to asynchronous messages,
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4246): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4246): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  904): Disable JIT of com.htc.bgp
,D/Process (  904): killProcessQuiet, pid=3856
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4266 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
I/ActivityManager(  904): Killing 3856:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3856
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4246): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/CalendarProvider2( 4266): Created com.android.providers.calendar.CalendarAlarmManager@41e3e810(com.android.providers.calendar.HtcCalendarProvider@41e26b98)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4246): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/CalendarProvider2( 4266): wait start:true
,W/fb4a(:<default>):UserScope( 4246): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/CalendarProvider2( 4266): wait end:false
D/PMS     (  904): acquireWL(4386b2c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
,D/PMS     (  904): acquireWL(43370050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(4386b2c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2599): Disabling old GoogleServicesFramework version
,I/CheckinService( 2599): Done disabling old GoogleServicesFramework version
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2599, uid=10028, userID:0
,W/ContextImpl( 4246): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/GCM     ( 1335): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1335): [NET] getaddrinfo-, 1
D/libc    ( 1335): [NET] getaddrinfo_proxy+
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  904): acquireWL(43866590): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1335 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c8f2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/PMS     (  904): releaseWL(43370050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  904): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4295 uid=10053 gids={50053, 1023, 3003, 5012}
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 9.960MB for 84664-byte allocation
,E/dalvikvm( 4246): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4246): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 9.975MB for 28144-byte allocation
,E/dalvikvm( 4246): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4246): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4246): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4246): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4246): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4246): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4246): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4246): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4246): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4246): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4246): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4246): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4246): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4246): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4246): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4246): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PluginProvider( 4295): PluginProvider onCreate
,D/PluginProvider( 4295): current plugin count: 19
,D/HtcAppUPService( 4295): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 10.045MB for 39954-byte allocation
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 10.122MB for 79892-byte allocation
,D/AutoSetting( 4295): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Process (  904): killProcessQuiet, pid=3876
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4309 uid=10078 gids={50078, 3003, 5012}
I/ActivityManager(  904): Killing 3876:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (4295/10053)
,D/AutoSetting( 4295): service - onCreate()
,D/AutoSetting( 4295): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4295): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  904): request 422fac08 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4295): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4295): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 4295): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4295): service - handleMessage() setting current location null
D/AutoSetting( 4295): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4295): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (4295/10053)
,D/MobileConnectivityChangeReceiver( 4309): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4309): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4309): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4309): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 10.282MB for 75760-byte allocation
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4309/10078)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4309/10078)
,I/DeviceManagement( 3843): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/PMS     (  904): acquireWL(428c12c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,I/DeviceManagement( 3843): WorkflowService: Starting workflow service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4309/10078)
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43f708f0 u0 ReceiverList{43f707d0 4246 com.facebook.katana/10026/u0 remote:432fb3c8}}
I/DeviceManagement( 3843): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41fd56e8] args=[Bundle[mParcelledData.dataSize=804]]
,I/ActivityManager(  904): Recipient 3876
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4326 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [4][0][0]
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b94248 u0 ReceiverList{43b941e8 4246 com.facebook.katana/10026/u0 remote:4352ef40}}
I/DeviceManagement( 3843): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 3843): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 3843): NetworkChangeWorkflow: ==================================================
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,I/DeviceManagement( 3843): SessionStateController: Checking invariants...
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 267,
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1335): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3843): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 3843): Perf: *** Cache update - start...
,I/DeviceManagement( 3843): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 3843): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 3843): Perf: *** Enabled app cache update - complete: 3 ms
,I/DeviceManagement( 3843): Perf: *** Config cache update - start...
,I/DeviceManagement( 3843): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3843): ConfigCacheController: *** Updating stale config cache entries...
,D/PMS     (  904): acquireWL(432fb7e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2599 10028 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  904): releaseWL(428c12c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4326): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 3843): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 3843): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 3843): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/ContextImpl( 4326): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/CheckinService( 2599): Preparing to send checkin request
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/EventLogService( 2599): Accumulating logs since 1454062821480
,D/ContactMessageStore( 1217): notify MmsSms
D/AccFlag ( 1217): sense_version=6.0
,D/AccFlag ( 1217): sku_id=99
,W/GAV2    ( 4326): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4326): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/PMS     (  904): acquireWL(43fe6508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1392 10028 null
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  904): releaseWL(43fe6508): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4326): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/System.err( 3843): Starting the internal HTTP client
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.reportagent/versions/687983cc-3a99-4a94-8c51-4a06dce9d091/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNzE2Wg
,D/GCoreFlp( 1392): Unknown pending intent to remove.
D/PMS     (  904): acquireWL(43fb1760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1392 10028 null
D/PMS     (  904): releaseWL(43fb1760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/EventLogAggregator( 2599): Unknown tag: install_package_attempt
W/EventLogAggregator( 2599): Unknown tag: snet
,W/EventLogAggregator( 2599): Unknown tag: snet_gcore
,I/GoogleHttpClient( 2599): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2599): Using GMS GoogleHttpClient
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,W/ContextImpl( 4246): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4246): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/DeviceManagement( 3843): DeviceClientResource: Active network...,
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [4][0][0]
,D/BuildInfo( 3843): Created new instance: com.htc.cs.lib.hms.BuildInfo@420f7ad8
,I/DeviceManagement( 3843): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4326/10151)
,V/WebViewChromiumFactoryProvider( 4326): Binding Chromium to main looper Looper (main, tid 1) {41e07e50}
,I/LibraryLoader( 4326): Expected native library version number "",actual native library version number ""
,D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,I/chromium( 4326): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4326): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(43dcf188): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  904): acquireWL(43c7fec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4326): BLUETOOTH permission is missing!
D/PMS     (  904): releaseWL(43dcf188): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2599/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4326): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4326): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4326): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4326): Local Branch: 
I/Adreno-EGL( 4326): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4326): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4326):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2599/10028)
,D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2869 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/NSApplication( 4326): Starting up...
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4326/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4326/10151)
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3649/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3649/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1754/10178)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.test.thalitest (3958/10189)
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 1335): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1335): [NET] getaddrinfo-,err=8
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/AlertReceiver( 3911): beginStartingService
,W/ActivityThread( 1335): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42295818 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 9 2 12
,W/CheckinRequestBuilder( 2599): awaiting user notification for token
D/PMS     (  904): acquireWL(437a9fc8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3911 10013 null
I/ActivityManager(  904): Delaying start of: ServiceRecord{43f7a738 u0 com.htc.calendar/.AlertService}
D/PMS     (  904): acquireWL(427b2e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
D/PMS     (  904): releaseWL(427b2e08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  904): acquireWL(428a8870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  904): releaseWL(428a8870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4380 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4392 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=204
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/GCM     ( 1335): Connected
D/PMS     (  904): acquireWL(427426d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  904): releaseWL(43866590): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,I/MultiDex( 4392): install
,I/MultiDex( 4392): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4392): loading existing secondary dex files
,I/MultiDex( 4392): load found 1 secondary dex files
,I/MultiDex( 4392): install done
,W/WeatherUtility( 4380): can't get weather sync account
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4407 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/PMS     (  904): releaseWL(427426d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/ProviderInstaller( 4392): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/WeatherRequest( 4380): request cur loc, but there is no sys cur
,W/Settings( 4380): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/CalendarProvider2( 4266): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4266): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Process (  904): killProcessQuiet, pid=3893
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3893:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  904): acquireWL(4287fd08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4407 10070 null
D/PMS     (  904): acquireWL(43b0fc08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4407 10070 null
D/PMS     (  904): releaseWL(4287fd08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  904): Recipient 3893
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TodoTaskshortcut( 4407): update TASK shortcut>
,I/ActivityManager(  904): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4424 uid=10090 gids={50090, 3003, 5012, 1028}
D/AppWidgetHostView( 1243): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1243): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1243): com.htc.widget.weatherclock 0 9 17
,I/TodoTaskNotifyService( 4407): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4407): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/GoogleHttpClient( 4392): Falling back to old SSLCertificateSocketFactory
,D/PMS     (  904): releaseWL(43b0fc08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4407): stopSelfResult true
,D/Process (  904): killProcessQuiet, pid=3676
,I/WorldClock.Global( 4424): isHtcDevice = true
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3676:com.google.android.gm/u0a107 (adj 15): empty #17
,I/WorldClock.Global( 4424): isHtcDevice = true
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4424): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  904): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4440 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4424): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4424): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1107): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/libc    ( 4392): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4392): [NET] getaddrinfo-,err=8
D/libc    ( 4392): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4392): [NET] getaddrinfo-, 1
D/libc    ( 4392): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3cf8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 233
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4392): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  904): Recipient 3676
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43f84f08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1335 10028 null
,D/Process (  904): killProcessQuiet, pid=3611
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 4440): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454063380051
I/ActivityManager(  904): Killing 3611:com.android.vending/u0a73 (adj 15): empty #17
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/Process (  904): killProcessQuiet, pid=4089
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4089:com.htc.widget.process2/u0a48 (adj 15): empty #17
D/GCM     ( 1335): Message class mpf
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
I/ActivityManager(  904): Delay finish: com.google.android.gms/.gcm.ServiceAutoStarter
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1335/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
I/ActivityManager(  904): Recipient 4089
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  904): releaseWL(43f84f08): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(4387cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
D/PMS     (  904): releaseWL(4387cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3611
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [22][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/libc    ( 4392): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4392): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4285c4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  904): releaseWL(4285c4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 3843): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3843): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3843): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3843): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 3843): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3843): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 3843): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 3843): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3843): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
,W/dalvikvm( 3843): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3843): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 3843): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 3843): isCompatible false
I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [21][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =52c8 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/AlertService( 3911): start to updateAlertNotification!
D/AlertService( 3911): No fired or scheduled alerts
,D/HtcAlertUtils( 3911): -- cancelReminderNotification --
,D/HtcAlertUtils( 3911): broadcastExistReminder!
,D/PMS     (  904): releaseWL(437a9fc8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3911): stopSelfResult true
,D/Process (  904): killProcessQuiet, pid=4031
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 4031:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4462 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  904): Recipient 4031
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
,I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,E/dalvikvm( 4462): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4462): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/Babel   ( 4462): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4462): MmsConfig.loadMmsSettings
,E/dalvikvm( 4462): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4462): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4462): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4392/10028)
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  904): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4485 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [9][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c258 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4462, uid=10111, userID:0
,W/Settings( 4462): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4485): onCreate
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4462, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4462, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4462, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4462, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4462, uid=10111, userID:0
,D/MmsCustomizationProvider( 4485): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4485): GetPrviateResource
,V/GetPrviateResource( 4485): GetPrviateResource
,I/ProviderInstaller( 4462): Installed default security provider GmsCore_OpenSSL
,D/MmsCustomizationProvider( 4485): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4462): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4462): MmsConfig.loadFromDatabase
I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,E/Babel   ( 4462): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4462): MmsConfig.loadFromResources
,E/Babel   ( 4462): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4462): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (4462/10111)
,D/Process (  904): killProcessQuiet, pid=4050
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  904): Killing 4050:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (4462/10111)
,W/Settings( 4392): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/MessageCustFlag( 4485): sense_version=6.0
,D/BTAccessoryUtil( 4485): createReceiver
,D/BTAccessoryUtil( 4485): registerReceiver return intent = null
D/MessageCustFlag( 4485): sku_id=99
,W/SystemReader( 4485): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4485): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4485): networkCode: 
,D/MessageCustFlag( 4485): sku_id=99
D/MmsConfig( 4485): SIE smsPri: null
,D/MmsConfig( 4485): networkCode: 
,D/HtcTelephonyCapability( 4485): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4485): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4485): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4485): Cannot find qct_8960_interface, use default value instead
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4462): UserRecoverableAuthException.
,E/Babel   ( 4462): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4462): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4462): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4462): Error getting auth token
,E/Babel   ( 4462): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4462): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4462): Account registration failedRedacted-21
E/Babel   ( 4462): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4462): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4462): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4462): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (4462/10111)
,I/ActivityManager(  904): Recipient 4050
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{422c8240 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/Babel   ( 4462): Unexpected exception while authenticating.
,I/RemoteViews.Performance( 1107): com.google.android.gms 2 8 2 12
,E/Babel   ( 4462): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4462): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4462): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4462): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4462): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4462): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4462): 	at java.lang.Thread.run(Thread.java:864)
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
W/fb4a(:<default>):UserScope( 4246): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4246): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
,I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/CheckinTask( 2599): Sending checkin request (9395 bytes)
W/ActivityThread( 2599): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2599): [NET] getaddrinfo-,err=8
D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2599): [NET] getaddrinfo-, 1
D/libc    ( 2599): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4c4 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/fb4a(:<default>):LocalFbBroadcastManager( 4246): Called registerBroadcastReceiver twice.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 142
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2599): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [6][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8cb0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/libc    ( 4246): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4246): [NET] getaddrinfo-,err=8
D/libc    ( 4246): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4246): [NET] getaddrinfo-, 1
,D/libc    ( 4246): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f31a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 32
D/libc    (  364): [NET]res_nsend:resplen=74
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4246): [NET] getaddrinfo_proxy-, success
I/global  ( 4246): call createSocket() return a new socket.
D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2599): [NET] getaddrinfo-,err=8
D/libc    ( 4246): [NET] getaddrinfo+,hn 10(0x33312e31332e36),sn(),family 0,flags 4
,D/libc    ( 4246): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4246): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4246): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4246): Grow heap (frag case) to 10.998MB for 32784-byte allocation
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [41][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [ScoreAP] + current TXpacket:129, mTXpacketCount:0, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  904): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
,I/System.out( 3843): isCompatible false
I/System.out( 3843): createObjectMapper
,I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,D/PMS     (  904): acquireWL(4405b9b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  904): releaseWL(4405b9b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,I/CheckinResponseProcessor( 2599): From server: 9 gservices updates and 1 deletes
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4246/10026)
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=14 [7][1][0]
D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3b95 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/PMS     (  904): releaseWL(43c7fec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CertBlacklister(  904): Certificate blacklist changed, updating...
,I/CertBlacklister(  904): Certificate blacklist updated
,I/GservicesProvider( 1335): main difference update completed
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4309/10078)
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2599/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2599/10028)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [4][0][0]
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2599): awaiting user notification for token
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e24540 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 7 2 12
,I/CheckinTask( 2599): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2599): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/PMS     (  904): releaseWL(432fb7e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2599): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4204c7e8 that was originally bound here
E/ActivityThread( 2599): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4204c7e8 that was originally bound here
E/ActivityThread( 2599): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2599): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2599): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2599): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2599): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2599): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2599): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2599): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2599): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2599): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2599): 	at bks.a(SourceFile:298)
E/ActivityThread( 2599): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2599): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2599): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2599): 	at java.lang.Thread.run(Thread.java:864)
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=16 [6][1][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =93ee +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,D/Messaging( 4485): mNeedToUpdateDate2 start
,D/MmsConfig( 4485): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4485): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4485): 
D/MmsAsyncWorkHandler( 4485): HM tk = 20001
D/ReportIndicatorCache( 4485): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4485): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e0d5e8
,I/Messaging( 4485): mccmnc> 
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4485): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4485): [DraftCache/1] refresh
,D/MmsConfig( 4485): networkCode: 
,D/Messaging( 4485): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4485): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4485): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4485): createReceiver
,D/MessageCustFlag( 4485): sense_version=6.0
,D/Jerry   ( 4485): start to preload cursor >>>>>>>
D/TelephUtils( 1217): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1217): Update uri=content://mms, match=0
,V/MmsProvider( 1217): selection=st=129 AND m_type!=134
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1217): sku_id=99
D/Messaging( 4485): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4485): TransactionService is going to be woken up.
,I/ActivityManager(  904): Delaying start of: ServiceRecord{440a4990 u0 com.htc.sense.mms/.transaction.TransactionService}
D/DraftCache( 4485): [DraftCache/463] rebuildCache
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/Messaging( 4485): mNeedToUpdateDate2: false
D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4485): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/Jerry   ( 1217): URI_DRAFT
D/Messaging( 4485): ViewCache CreatePreload
D/Messaging( 4485): ViewCache CreatePreloadOnlyMultipleOpsList
D/Cust_MMSMS( 4485): _has_set_default_values_2=true
D/DraftCache( 4485): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4485): [DraftCache/463] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4485): 
D/MmsAsyncWorkHandler( 4485): HM tk = 20002
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MsgPreferenceUtils( 4485): def_index: 0
D/AccFlag ( 1217): sku_id=99
D/MsgPreferenceUtils( 4485): globalIndex = 1
D/MsgPreferenceUtils( 4485): phone state: true
D/MsgPreferenceUtils( 4485): sd state: false
D/MsgPreferenceUtils( 4485): vIndex = 0
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/AccFlag ( 1217): sku_id=99
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
,I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [13][0][0]
D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =627 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
,I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=11 [17][2][0]
D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
,D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6a5d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,I/jxcore-log( 3958): Test app app.js loaded
I/jxcore-log( 3958): 
,W/dalvikvm( 3958): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3958): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3958): BLE advertisement is supported
I/jxcore-log( 3958): 
,I/chromium( 3958): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV2    ( 4326): Thread[GAThread,5,main]: No campaign data found.
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
,I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false,
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
D/PMS     (  904): acquireWL(42f28ea0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1392 10028 null
D/PMS     (  904): acquireWL(43b6b4c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1392 10028 null
D/PMS     (  904): releaseWL(42f28ea0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  904): releaseWL(43b6b4c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/DeviceManagement( 3843): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,I/DeviceManagement( 3843): DeviceClientResource: Active network...
I/DeviceManagement( 3843):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (3843/10098)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=9 [11][1][0]
D/libc    ( 3843): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3843): [NET] getaddrinfo-,err=8
D/libc    ( 3843): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3843): [NET] getaddrinfo-, 1
D/libc    ( 3843): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a2c2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3843): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3843): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3843): DeviceClientResourceController: handleDirectives: []
I/System.out( 3843): isCompatible false
I/System.out( 3843): createObjectMapper
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
I/System.out( 3843): isCompatible false
,I/System.out( 3843): isCompatible false
,I/DeviceManagement( 3843): ConfigCacheController: *** Update config cache: updating 9 entries...
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [18][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,I/DeviceManagement( 3843): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3843): AlarmController: Scheduling TTL alarm for: 2016.01.30 at 11:29:45.175 CET (due to: com.htc.launcher)
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3843, uid=10098, userID:0
,I/DeviceManagement( 3843): Perf: *** Config cache update - complete: 6152 ms
,I/DeviceManagement( 3843): Perf: *** Cache update - complete: 6159 ms
,I/DeviceManagement( 3843): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41fd56e8]
,I/DeviceManagement( 3843): WorkflowService: Stopping workflow service
,V/TransactionService( 4485): 1-Creating TransactionService
,V/TransactionService( 4485): onStartCommand: 1
,D/MmsSystemEventReceiver( 4485): unRegisterForConnectionStateChanges
V/TransactionService( 4485): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4485): Loading previous transactions.
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1217): device_type: 1
,D/TransactionService( 4485): Force set service start id to 1
,V/TransactionService( 4485): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4485): unRegisterForConnectionStateChanges
,V/TransactionService( 4485): Destroying TransactionService
,D/TransactionService( 4485): stopSelfResult: true, mLastHandledServiceId: 1
,D/Process (  904): killProcessQuiet, pid=3406
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Killing 3406:com.android.settings/1000 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1335): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/TransactionService( 4485): 4-Handling incoming message: { when=-8ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/ProviderChangeReceiver( 3911): ---------------------------------------------------
,D/ProviderChangeReceiver( 3911): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3911): start to updateAlertNotification!
I/ActivityManager(  904): Resuming delayed broadcast
W/ContextImpl( 3926): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3911): No fired or scheduled alerts
,D/HtcAlertUtils( 3911): -- cancelReminderNotification --
,D/HtcAlertUtils( 3911): broadcastExistReminder!
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  904): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4277a870): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4407 10070 null
,D/PMS     (  904): acquireWL(43f3b438): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4407 10070 null
,D/PMS     (  904): acquireWL(43701e38): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4407 10070 null
,D/PMS     (  904): releaseWL(4277a870): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  904): Delay finish: com.htc.task/.notification.NotifyReceiver
,D/PMS     (  904): acquireWL(43f3b438): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4407 10070 null
,E/TodoTaskNotifyService( 4407): java.lang.NullPointerException
W/System.err( 4407): java.lang.NullPointerException
,W/System.err( 4407): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4407): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4407): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4407): stopSelfResult false
E/TodoTaskNotifyService( 4407): java.lang.NullPointerException
,W/System.err( 4407): java.lang.NullPointerException
W/System.err( 4407): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 4407): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4407): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4407): mStartingService is null
D/PMS     (  904): releaseWL(43701e38): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  904): releaseWL(43f3b438): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,W/NotifyReceiver( 4407): stopSelfResult true
I/ActivityManager(  904): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4565 uid=10038 gids={50038}
I/ActivityManager(  904): Recipient 3406
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
,D/SMSBackup( 4229): Got a database change event
,D/PMS     (  904): acquireWL(427bb9b0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4186 10154 null
,I/ActivityManager(  904): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 4186): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4186): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4186, uid=10154, userID:0
,D/PMS     (  904): releaseWL(427bb9b0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4186): Conditions not met for autocaching.
,I/MusicLeanback( 4186): Stop autocaching.
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4583 uid=10016 gids={50016, 3003, 5012, 2001}
,D/Process (  904): killProcessQuiet, pid=4246
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4246:com.facebook.katana/u0a26 (adj 15): empty #17
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4583): Update started
,I/ActivityManager(  904): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
E/UpdateRequestReceiver( 4583): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4583): Update started
I/ActivityManager(  904): Recipient 4246
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
D/PMS     (  904): acquireWL(438a1ab8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2527 10021 WorkSource{10016}
,I/DownloadManager( 2527): Download 235 starting
I/ActivityManager(  904): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
W/ActivityThread( 2527): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
E/UpdateRequestReceiver( 4583): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4583): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4583): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Process (  904): killProcessQuiet, pid=4309
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4309:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.analytics.internal.GServicesChangedReceiver
I/ActivityManager(  904): Recipient 4309
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/GA-SERVICE( 2599): Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2599, uid=10028, userID:0
I/ActivityManager(  904): Resuming delayed broadcast
,D/libc    ( 2527): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2527): [NET] getaddrinfo-,err=8
D/libc    ( 2527): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2527): [NET] getaddrinfo-, 1
,D/libc    ( 2527): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a0e2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2527): [NET] getaddrinfo_proxy-, success
,D/PMS     (  904): acquireWL(440aee28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
,I/DownloadManager( 2527): Download 236 starting
D/PMS     (  904): acquireWL(4409fb08): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2527 10021 WorkSource{10016}
I/ActivityManager(  904): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
D/PMS     (  904): acquireWL(4405b9b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2599 10028 null
D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
D/PMS     (  904): releaseWL(440aee28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2527): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2527): [NET] getaddrinfo-,err=8
D/libc    ( 2527): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2527): [NET] getaddrinfo-, 1
D/libc    ( 2527): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] +++++ res_nsend xid =ebb3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2527): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): releaseWL(4405b9b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/SystemUpdateService( 2599): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  904): acquireWL(43f93598): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2599 10028 null
I/ActivityManager(  904): Delay finish: com.google.android.gms/.update.SystemUpdateService$Receiver
,I/SystemUpdateService( 2599): cancelUpdate (empty URL)
,I/SystemUpdateService( 2599): active receiver: disabled
I/SystemUpdateService( 2599): cancelUpdate (empty URL)
,I/SystemUpdateService( 2599): active receiver: disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2599, uid=10028, userID:0
,D/GCM     ( 1335): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): releaseWL(43f93598): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 null
I/ActivityManager(  904): Delay finish: com.google.android.gms/.icing.service.SystemEventReceiver
D/PMS     (  904): acquireWL(43c7fec0): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(43c7fec0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
I/GCM     ( 1335): GCM config loaded
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.security.snet.SnetReceiver
,D/SystemEventReceiver( 2599): Received GSERVICES_CHANGED broadcast
I/ActivityManager(  904): Resuming delayed broadcast
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@424b7fd0
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  904): pid=904, uid=1000
,W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@424b7fd0, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42019620
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@428e8028
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  904): Going to sleep due to screen timeout...
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,I/OcrUtils( 2599): Updating ocr activity enabled=false
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/GCoreUlr( 1392): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
W/PMS     (  904): mWirelessDisplayManager is null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2599, uid=10028, userID:0
D/PMS     (  904): acquireWL(421e41f8): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 1392 10028 null
,I/GCoreUlr( 1392): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4627 uid=10031 gids={50031, 3003, 5012}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4462, uid=10111, userID:0
,D/Process (  904): killProcessQuiet, pid=4203
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4203:com.android.chrome/u0a96 (adj 15): empty #17
,I/GCoreUlr( 1392): Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotSelected'}]}
,D/GCoreFlp( 1392): Unknown pending intent to remove.
,I/GCoreUlr( 1392): Unbound from all location providers
D/PMS     (  904): acquireWL(43907e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1392 10028 null
I/ActivityManager(  904): Recipient 4203
D/PMS     (  904): releaseWL(43907e28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  904): releaseWL(421e41f8): PARTIAL_WAKE_LOCK  UlrDispatchingService 0x1 null
,I/DownloadManager( 2527): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2527): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [11][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
,D/Process (  904): killProcessQuiet, pid=3843
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 3843:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  904): Recipient 3843
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 389ms
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PMS     (  904): nativeSetInteractive:false
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
D/NfcService( 1228): ScreenObserver: OFF
,D/NfcService( 1228): applyRouting - 0
,D/NfcService( 1228): applyRouting -2
V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@423b14c8)
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
D/PMS     (  904): acquireWL(42902848): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  904): releaseWL(42902848): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=3958
D/PMN     (  904): wakingUp
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
W/ResourceType( 3958): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3958): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e131a8 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): acquireWL(428b5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/MtpService( 2527): [MTP][onReceive]+android.intent.action.USER_PRESENT
I/BatteryService(  904): n_update end
D/PMN     (  904): onScreenOn
D/PMS     (  904): releaseWL(428b5110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
,D/MtpService( 2527): [MTP][onReceive]-
,D/NfcService( 1228): applyRouting - 0
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1228): applyRouting -2
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20338 delay=15s
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): acquireWL(429c8ce0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1228 1027 null
D/PMS     (  904): releaseWL(429c8ce0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PowerUI ( 1107): closing low battery warning: level=100
,I/DownloadManager( 2527): Download 235 finished with status SUCCESS
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(438a1ab8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ClockThread( 1107): stop update clock
I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,I/HtcPowerSaver(  904): << updateStatus
I/wpa_supplicant( 4086): SET_SCREEN_ON:On
I/wpa_supplicant( 4086): htc_wext_set_keepalive +
I/wpa_supplicant( 4086): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4086): getPrivFuncNum +	
I/wpa_supplicant( 4086): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4086): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/DownloadManager( 2527): Download 236 finished with status SUCCESS
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [15][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4086): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/PMS     (  904): releaseWL(4409fb08): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/NetworkPolicy(  904): updateScreenOn: false
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(42861de0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,D/PMS     (  904): releaseWL(42861de0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4627, uid=10031, userID:0
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42880688): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(42880688): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/PMS     (  904): acquireWL(428c9a80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
D/PMS     (  904): releaseWL(428c9a80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4069): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4069): onScreenOn: 1454063386753
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4069): onScreenOn: 1454063386753
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42019620
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42019620, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@428e8028
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(43a150c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
D/PMS     (  904): acquireWL(43f637c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
D/PMS     (  904): releaseWL(43a150c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4657 uid=10078 gids={50078, 3003, 5012}
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20338 mDataStallAlarmIntent=PendingIntent{436bdd60: PendingIntentRecord{42874720 android broadcastIntent}}
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4086): SET_SCREEN_ON:Off
I/wpa_supplicant( 4086): htc_wext_set_keepalive +
I/wpa_supplicant( 4086): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4086): getPrivFuncNum +	
I/wpa_supplicant( 4086): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4086): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4086): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4086): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 4086): htc_wext_set_keepalive - ret = 0
D/PMS     (  904): releaseWL(43f637c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  904): acquireWL(4283d540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
D/PMS     (  904): releaseWL(4283d540): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  904): acquireWL(4284b520): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  904): updateScreenOn: false
D/PMS     (  904): acquireWL(43fb1f40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
,D/PMS     (  904): releaseWL(43fb1f40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/wpa_supplicant( 4086): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  904):    returned true
,D/ContactMessageStore( 1217): start background delete task...
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
D/PMS     (  904): releaseWL(4284b520): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(428797d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
,D/PMS     (  904): releaseWL(428797d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  904): acquireWL(43bb9fb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
,D/PMS     (  904): releaseWL(43bb9fb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/Process (  904): killProcessQuiet, pid=4326
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4326:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,E/PhoneMonitor( 4657): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4657): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] getTotalRam: 1873 Mb
,D/Process (  904): killProcessQuiet, pid=3649
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2675): canRun() : Opted Out
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4657/10078)
I/ActivityManager(  904): Killing 3649:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/PMS     (  904): acquireWL(429ac0f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
D/PMS     (  904): releaseWL(429ac0f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4657/10078)
,I/Search.GservicesUpdateTask( 2675): Updating Gservices keys
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4069): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4069): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4069): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4069): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4069): onScreenOff
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4657/10078)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3649
D/AutoSetting( 4295): service - mHandler: cancel location update
D/AutoSetting( 4295): service -           changes count: 0
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  904): acquireWL(43535018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
,D/PMS     (  904): acquireWL(4352e118): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(43535018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/GCM     ( 1335): GCM config loaded
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/PMS     (  904): releaseWL(4352e118): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  904): Recipient 4326
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AdsMeasurementBroadcastReceiver( 2599): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2599): Unauthorized to start the main service
,I/GStaticConfiguration( 2675): #getNewConfigurationUrl [pref=2015_09_15_14_04_18, gservice=2016_01_27_20_58_17
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4679 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/libc    ( 2675): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2675): [NET] getaddrinfo-,err=8
D/libc    ( 2675): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2675): [NET] getaddrinfo-, 1
,D/libc    ( 2675): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =db18 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2675): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.googlequicksearchbox (2675/10085)
,W/ContextImpl( 4679): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4679): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(43c972c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4679 1000 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 4295): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  904): releaseWL(43c972c0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
D/SmartSyncUtils( 4679): getMobilePolicyEnabled, result = true
,D/AutoSetting( 4295): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=4699 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  904): killProcessQuiet, pid=4380
,I/ActivityManager(  904): Killing 4380:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4380
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 4699): -onCreate()
,V/Settings:HtcSettingsApplication( 4699): [4699/4699] onCreate()
,D/TetherSettings( 4699): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4699): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4699): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4699): Cust_ConnectToPC   : spcsc>false
D/        ( 4699): Cust_ConnectToPC   : IPT>true
,D/        ( 4699): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4699): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4699): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4699): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4699): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4699): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4699): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4699): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4699):  defaultType:0
W/ContextImpl( 4699): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,W/ContextImpl( 4679): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4699): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4699): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4699): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4699): Cust_ConnectToPC   : spcsc>false
D/        ( 4699): Cust_ConnectToPC   : IPT>true
,D/        ( 4699): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4699): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4699): Index of the first 1 = -1
W/ContextImpl( 4699): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4699): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4699): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4699): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4699): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4699): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4699): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  904): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
,I/DownloadManager( 2527): Download 237 starting
D/PMS     (  904): acquireWL(43c96020): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2527 10021 WorkSource{10016}
D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [14][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  904): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,D/libc    ( 2675): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2675): [NET] getaddrinfo-,err=8
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
,W/ContextImpl( 4679): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/DownloadManager( 2527): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2527): Download 238 starting
D/PMS     (  904): acquireWL(440cfe98): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2527 10021 WorkSource{10016}
,D/ConnectivityService(  904): getAllNetworkInfo called by  (2527/10021)
,D/SmartSyncUtils( 4679): isEpsOn(), nState = 0
D/SmartSyncUtils( 4679): getMobilePolicyEnabled, result = true
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [36][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4679): isEpsOn(), nState = 0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiService(  904): New client listening to asynchronous messages
,I/DownloadManager( 2527): Ignoring Content-Length since Transfer-Encoding is also defined
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
I/ContactAccountLoggerTas( 2675): canRun() : Opted Out
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
I/ContactAccountLoggerTas( 2675): canRun() : Opted Out
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  904): killProcessQuiet, pid=4424
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4424:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428e8028
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428e8028, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428e8028, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428e8028
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  904): Recipient 4424
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428a35c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428a35c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2527/10021)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/GLSUser ( 1335): GoogleAccountDataService.getToken()
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/googlenow
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/Search.LoginHelper( 2675): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41f3b9a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/Search.LoginHelper( 2675): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 2675): canRun() : Opted Out
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 9 3 12
,I/DownloadManager( 2527): Download 237 finished with status SUCCESS
D/PMS     (  904): releaseWL(43c96020): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/DownloadManager( 2527): Download 238 finished with status SUCCESS
D/PMS     (  904): releaseWL(440cfe98): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4583): Update downloaded, starting installation
,I/UpdateFetcherService( 4583): Started installation
,W/ContextImpl( 4583): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4583): Update downloaded, starting installation
,I/UpdateFetcherService( 4583): Started installation
,I/ConfigUpdateInstallReceiver(  904): Not installing, new version is <= current version
,D/Process (  904): killProcessQuiet, pid=3491
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3491:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3491
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{428d0430 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1243): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/PackageManager(  904):   Scheme: "smsto"
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.htc.cs.dm
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/Launcher( 1243): Deferring update until onResume
D/Launcher( 1243): waitUntilResume // bindAppsUpdated
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,D/PackageBroadcastService( 2599): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/[PluginManager]RegisterService( 4295): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4295): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(43f7b190): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4737 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
,I/PeopleContactsSync( 2599): CP2 sync disabled
D/PMS     (  904): releaseWL(43f7b190): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2599, uid=10028, userID:0
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4737, uid=10073, userID:0
,D/Finsky  ( 4737): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (4737/10073)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (4737/10073)
,D/Finsky  ( 4737): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4737): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4737): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4737, uid=10073, userID:0
,W/PackageManager(  904): Unable to load service info ResolveInfo{42f8ad60 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/Finsky  ( 4737): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4737): [1] 2.run: Finished loading 1 libraries.
,D/Process (  904): killProcessQuiet, pid=4440
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4440:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2675): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  904): Recipient 4440
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4770 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Finsky  ( 4737): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4737): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/IcingCorporaProvider( 2675): UpdateCorporaTask done [took 78 ms] updated apps [took 78 ms] 
,D/PMS     (  904): acquireWL(43859030): PARTIAL_WAKE_LOCK  AsyncService 0x1 4770 10160 null
,D/PackageBroadcastService( 2599): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
D/PMS     (  904): releaseWL(43859030): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/[PluginManager]RegisterService( 4295): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 4295): handle notify Blinkfeed plugin client changed
,I/PeopleContactsSync( 2599): CP2 sync disabled
D/PMS     (  904): acquireWL(437659b0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4770 10160 null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2599, uid=10028, userID:0
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/PMS     (  904): acquireWL(42bf2620): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4770 10160 null
D/PMS     (  904): releaseWL(437659b0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): acquireWL(4381a168): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4770/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4770/10160)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
D/PMS     (  904): releaseWL(4381a168): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4086): environment dirty rate=0 [0][0][0]
,W/PackageManager(  904): Unable to load service info ResolveInfo{435e47f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2675): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,D/PMS     (  904): acquireWL(43c68598): PARTIAL_WAKE_LOCK  AsyncService 0x1 4770 10160 null
,D/PMS     (  904): releaseWL(43c68598): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  904): releaseWL(42bf2620): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=4462
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  904): Killing 4462:com.google.android.talk/u0a111 (adj 15): empty #17
,I/IcingCorporaProvider( 2675): UpdateCorporaTask done [took 58 ms] updated apps [took 57 ms] 
,D/Settings:HtcWirelessFeatureFlags( 4699): id/is att sku: 99/false
,W/SystemReader( 4699): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4699): Cannot find support_harman, use default value instead
,W/SystemReader( 4699): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4699): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4699): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4699): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4699): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]support         :false
,I/ActivityManager(  904): Recipient 4462
,W/FingerprintManager( 4699): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4699): isSupportVoWifi: null
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4699): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4699): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4699): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4699): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]support         :false
,W/FingerprintManager( 4699): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4699): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4699): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4699): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4699): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4699): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4699): [supportHomeButton]support         :false
,W/FingerprintManager( 4699): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4699): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4699): Failed to find provider info for com.htc.vowifi
,D/PMS     (  904): acquireWL(4405b9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{436d3a18: PendingIntentRecord{427ded20 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454063397081, Int=0
,D/PMS     (  904): releaseWL(4405b9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1243): loadItems() com.htc.launcher.pageview.WidgetManager@41e92ff0 +
,I/Prism.WidgetManager( 1243): onLoadItems() +
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,D/AutoSetting( 4295): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4295): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4295): service - requestNLP() NetworkLocationProvider not enabled
W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,W/GLSActivity( 1335): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1335): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1335): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1335): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1335): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1335): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{421aadb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4737): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4737): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4737): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4737): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4737): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4737): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4737): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4737): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1107): com.google.android.gms 3 10 4 12
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
D/libc    ( 4737): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4737): [NET] getaddrinfo-,err=8
D/libc    ( 4737): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4737): [NET] getaddrinfo-, 1
D/libc    ( 4737): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5687 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4737): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4737): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 298
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4737): [NET] getaddrinfo_proxy-, success
I/global  ( 4737): call createSocket() return a new socket.
D/libc    ( 4737): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4737): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4737): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4737): [NET] getaddrinfo-,err=8
,W/asset   ( 1243): Copying FileAsset 0x68470ce0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1243): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1243): onLoadItems() -
,I/Prism.ItemManager( 1243): loadItems() com.htc.launcher.pageview.WidgetManager@41e92ff0 -
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4737): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4737): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4737): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/Finsky  ( 4737): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.vending (4737/10073)
,D/Finsky  ( 4737): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1243): loadItems() com.htc.launcher.pageview.WidgetManager@41e92ff0 +
,I/Prism.WidgetManager( 1243): onLoadItems() +
,E/Prism.WidgetManager( 1243): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1243): onLoadItems() -
,I/Prism.ItemManager( 1243): loadItems() com.htc.launcher.pageview.WidgetManager@41e92ff0 -
,D/PMS     (  904): acquireWL(42913c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{425afcc0: PendingIntentRecord{425aa188 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120786, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42913c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(440d0168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{420b5ea8: PendingIntentRecord{42792718 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=127431, Int=0
,D/PMS     (  904): acquireWL(4380f800): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/PMS     (  904): releaseWL(440d0168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(434c7218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4380f800): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(434c7218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4295): service - mHandler: update timezone
,D/AutoSetting( 4266): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4266): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 4266): service - onCreate()
,D/AutoSetting( 4266): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4266): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4266): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 4266): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4266): service - mHandler: update timezone
,D/AutoSetting( 4266): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4266): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4266): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4266): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1107): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42268ab0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.htclocationservice 2 11 3 11
,D/PMS     (  904): acquireWL(43f6bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(43f6bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(428a3af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{428cdc60: PendingIntentRecord{428cdc28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454063412333, Int=0
,D/PMS     (  904): releaseWL(428a3af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4737): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43f4f5e0): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(43f4f5e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(434de650): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(434de650): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42830b68): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(42830b68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(43c68bc8): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,D/PMS     (  904): releaseWL(43c68bc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/AutoSetting( 4295): service - handleMessage() stop self
,D/AutoSetting( 4295): service - handleMessage() quit looper
,D/AutoSetting( 4295): service - onDestroy() END
,D/PMS     (  904): acquireWL(428e6e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42662a88: PendingIntentRecord{42864f60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137682, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{42087258: PendingIntentRecord{42647f98 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141715, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{43732ed0: PendingIntentRecord{42d53528 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454063412749, Int=563223000
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1335/10028)
,D/PMS     (  904): acquireWL(4393aa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  904): releaseWL(4393aa10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(43f692c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): acquireWL(43f7b148): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2599 10028 null
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =35e4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  904): releaseWL(428e6e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  904): acquireWL(43b5b748): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2599 10028 null
D/PMS     (  904): releaseWL(43f7b148): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,I/CheckinService( 2599): Preparing to send checkin request
,I/EventLogService( 2599): Accumulating logs since 1454063379450
,W/EventLogAggregator( 2599): Unknown tag: install_package_attempt
W/EventLogAggregator( 2599): Unknown tag: snet
,W/EventLogAggregator( 2599): Unknown tag: snet_gcore
,I/GoogleHttpClient( 2599): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2599): Using GMS GoogleHttpClient
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2599/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2599/10028)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=4 [24][1][0]
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2599): awaiting user notification for token
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41f49a90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 11 3 12
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4392/10028)
,W/Settings( 4392): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4392): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4392): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4392): Local Branch: 
I/Adreno-EGL( 4392): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4392): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4392):                  aa63bbd948f41d15fc72f585e
,I/CheckinTask( 2599): Sending checkin request (9015 bytes)
,D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2599): [NET] getaddrinfo-,err=8
D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2599): [NET] getaddrinfo-, 1
,D/libc    ( 2599): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f4ac +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2599): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2599): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2599): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(43b0f208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1335 10028 null
,D/PMS     (  904): releaseWL(43b0f208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2599/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4086): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2599/10028)
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4086): nl80211: survey data missing!
E/wpa_supplicant( 4086): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4086): environment dirty rate=3 [60][2][0]
,W/GLSUser ( 1335): GoogleAccountDataService.getToken()
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1335): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1335): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2599): awaiting user notification for token
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1107): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{421c60b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.google.android.gms 1 9 4 12
,I/CheckinTask( 2599): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2599): Unable to close GMS GoogleHttpClient
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  904): releaseWL(43b5b748): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2599): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4202f7b0 that was originally bound here
E/ActivityThread( 2599): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@4202f7b0 that was originally bound here
E/ActivityThread( 2599): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2599): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2599): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2599): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2599): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2599): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2599): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2599): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2599): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2599): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2599): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2599): 	at bks.a(SourceFile:298)
E/ActivityThread( 2599): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2599): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2599): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2599): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1335): GCM config loaded
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43d60b58 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  904): releaseWL(43f692c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/AutoSetting( 4266): service - handleMessage() stop self
,D/AutoSetting( 4266): service - onDestroy() END
,D/AutoSetting( 4266): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4485
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4485:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4485
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2599/10028)
,D/PMS     (  904): acquireWL(43af9290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43af9290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(42e3ec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{425afcc0: PendingIntentRecord{425aa188 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180786, Int=0
,D/PMS     (  904): releaseWL(42e3ec30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43b798a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43b798a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(428096e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{438a4df0: PendingIntentRecord{43a71f50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=220151, Int=0
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4830 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{4264e3c0: PendingIntentRecord{42742c40 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454063488181, Int=10800000
,D/PMS     (  904): releaseWL(428096e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10047}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4830/10047)
,D/Process (  904): killProcessQuiet, pid=3911
,I/ActivityManager(  904): Killing 3911:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3911
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43526bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43526bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438a9968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{425afcc0: PendingIntentRecord{425aa188 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240786, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(438a9968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43f3e590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(43f3e590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 3958): --= Surplus to requirements =--
I/jxcore-log( 3958): 
I/jxcore-log( 3958): ****TEST TOOK:  ms ****
I/jxcore-log( 3958): 
,I/jxcore-log( 3958): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3958): 
,E/cutils-trace( 4853): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4853): ====startRecUseTime====
D/htc.customization.log.level( 4853):  is 
,W/CustomizationLogLevel( 4853): Level value is invalid, use default level 2
,D/CustomizationManager( 4853):  Read ACC file spent 0.121 (s)
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4853): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4853): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4853): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4853): Parsing tag category name = system
,I/CustomizationCIDLoader( 4853): Parsing tag category name = application
I/CustomizationCIDLoader( 4853): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 4853): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4853): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4853): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4853): Parsing tag category name = Settings
D/CustomizationManager( 4853):  Read CID file spent 0.178 (s)
,D/CustomizationManager( 4853):  All configurations done spent 0.178 (s)
,W/HtcNativeFlag( 4853): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4853): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4853): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4853): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4853, uid=2000 user=0
,I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  904): killProcessQuiet, pid=3958
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  904): Killing 3958:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
I/ActivityManager(  904):   Force finishing activity ActivityRecord{422f2518 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  904): Copying FileAsset 0x6c07f6b0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1182): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 3958 uid 10189
,I/ActivityManager(  904): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/acms    ( 1772): Unregistering com.test.thalitest
,E/acms    ( 1772): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,W/GeofencerStateMachine( 1392): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(43f44860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1392 10028 null
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  904): WIN DEATH: Window{420212a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  904): Client connection lost with reason: 4
D/PMS     (  904): releaseWL(43f44860): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/VoicemailCleanupService( 1272): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
D/PackageBroadcastService( 2599): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Launcher( 1243): Deferring update until onResume
,D/Launcher( 1243): waitUntilResume // bindAppsRemoved
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4868 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  904):   Scheme: "mmsto"
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,I/MultiDex( 4868): install
,I/MultiDex( 4868): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
,I/MultiDex( 4868): loading existing secondary dex files
,I/MultiDex( 4868): load found 1 secondary dex files
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/MultiDex( 4868): install done
,I/ActivityManager(  904): Delaying start of: ServiceRecord{43fdb220 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ProviderInstaller( 4868): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 2599): CP2 sync disabled
,I/Icing   ( 2599): doRemovePackageData com.test.thalitest
D/PMS     (  904): acquireWL(427e39b8): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2599, uid=10028, userID:0
,D/PMS     (  904): releaseWL(427e39b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4886 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4886): install
,I/MultiDex( 4886): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4886): loading existing secondary dex files
,I/MultiDex( 4886): load found 1 secondary dex files
,I/MultiDex( 4886): install done
,I/ProviderInstaller( 4886): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  904): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 4295): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 4295): handle notify Blinkfeed plugin client changed
,D/Process (  904): killProcessQuiet, pid=3926
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1243): action: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  904): Killing 3926:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3926
,I/IcingCorporaProvider( 2675): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/BluetoothSapService( 4005): onUnbind: android.bluetooth.IBluetoothSap
D/WifiService(  904): Client connection lost with reason: 4
,I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4907 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  904): acquireWL(437dbc18): PARTIAL_WAKE_LOCK  Icing 0x1 2599 10028 null
,W/PackageManager(  904): Unable to load service info ResolveInfo{428bf398 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteLog( 4868): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4868): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca17470
,E/DriveAsyncService( 4868): disk I/O error (code 3850)
E/DriveAsyncService( 4868): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4868): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4868): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4868): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4868): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4868): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4868): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4868): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/IcingCorporaProvider( 2675): UpdateCorporaTask done [took 168 ms] updated apps [took 167 ms] 
,E/SQLiteLog( 4868): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4868): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca17470
,E/DocListDatabase( 4868): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4868): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4868): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4868): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4868): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4868): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4868): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4868): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4868): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4868): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4868): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4868): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4868): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4868): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4868): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4868): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4868): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4868): threadid=1: thread exiting with uncaught exception (group=0x419d0e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 4868): killProcess, pid=4868
D/Process ( 4868): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4868): FATAL EXCEPTION: main
E/AndroidRuntime( 4868): Process: com.google.android.gms.drive, PID: 4868
E/AndroidRuntime( 4868): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4868): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4868): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4868): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4868): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4868): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4868): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4868): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4868): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4868): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4868): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4868): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4868): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4868): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4868): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4868): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4868): 	... 10 more
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
,I/ActivityManager(  904): Recipient 4868
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4868) has died.
,W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,E/SQLiteDatabase( 4907): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4907): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4907): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4907): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4907): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4907): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4907): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4907): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4907): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4907): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4907): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4907): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4907): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4907): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4907): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4907): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4907): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4907): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4907): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4907): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4907): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4907): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4907): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4907): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4907): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4907): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4907): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4907): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4907): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4907): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4907): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4907): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4907): Opened ClientFlag.db in read-only mode
,W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/SQLiteDatabase( 4907): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4907): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4907): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4907): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4907): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4907): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4907): threadid=11: thread exiting with uncaught exception (group=0x419d0e30)
,E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4907): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4907): Process: com.google.android.apps.docs, PID: 4907
E/AndroidRuntime( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4907): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4907): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4907): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4907): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4907): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
,D/Process ( 4907): killProcess, pid=4907
,D/Process ( 4907): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4928 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  904): Recipient 4907
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=4407
,I/ActivityManager(  904): Killing 4407:com.htc.task/u0a70 (adj 15): empty #17
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4907) has died.
,I/ActivityManager(  904): Recipient 4407
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4928): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4928): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4928): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4928): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4928): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4928): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4928): threadid=10: thread exiting with uncaught exception (group=0x419d0e30)
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4941 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/ActivityManager(  904): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4928): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4928): Process: com.android.keychain, PID: 4928
E/AndroidRuntime( 4928): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4928): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4928): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4928): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4928): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4928): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4928): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4928): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4928): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4928): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4928): killProcess, pid=4928
,D/Process ( 4928): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454063565992.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
,D/AppTag  ( 4941): getInstance(Context context)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4928
,I/ActivityManager(  904): Process com.android.keychain (pid 4928) has died.
,W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10700ms
,D/AppTag  ( 4941): getInstance(Context context)
,D/AppTag  ( 4941): onCreate()
,D/PMS     (  904): acquireWL(437db550): PARTIAL_WAKE_LOCK  AsyncService 0x1 4770 10160 null
,D/PMS     (  904): releaseWL(437db550): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4959 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4959): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4959 dbg=false s=true
,I/DeviceManagement( 4959): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4959): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4959): WorkflowService: Starting workflow service
I/DeviceManagement( 4959): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e37468] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4959): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4959): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4959): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4959): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4973 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4959): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4959): SessionStateController: Checking invariants...
,D/Documents( 4973): Loading roots for com.android.providers.downloads.documents
,D/Documents( 4973): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 4973): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4973): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4973): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4973): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4973): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4973): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4973): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4973): threadid=1: thread exiting with uncaught exception (group=0x419d0e30)
,D/Process (  904): killProcessQuiet, pid=4565
E/AndroidRuntime( 4973): FATAL EXCEPTION: main
E/AndroidRuntime( 4973): Process: com.android.documentsui, PID: 4973
E/AndroidRuntime( 4973): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4973): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4973): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4973): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4973): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4973): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4973): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4973): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4973): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4973): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4973): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4973): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4973): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4973): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4973): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4973): 	... 10 more
,I/ActivityManager(  904): Killing 4565:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  904): Recipient 4565
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ActivityManager(  904): App crashed! Process: com.android.documentsui
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4987 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4973): killProcess, pid=4973
,D/Process ( 4973): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454063566286.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
,D/Process (  904): killProcessQuiet, pid=4229
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  904): Killing 4229:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Recipient 4973
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.documentsui (pid 4973) has died.
,D/GCM     ( 1335): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  904): Recipient 4229
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ExternalStorage( 4987): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4959): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5003 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/DeviceManagement( 4959): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4959): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4959): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4959): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4959): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4959): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4959): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e37468]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4959): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4959): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4959): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4959): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4959): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4959): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4959): WorkflowService: Stopping workflow service
,E/SQLiteDatabase( 5003): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5003): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5003): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5003): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5003): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5003): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 5003): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 5003): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 5003): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 5003): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5003): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5003): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5003): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 5003): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 5003): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5003): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5003): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5003): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5003): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 5003): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 5003): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 5003): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 5003): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 5003): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5003): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5003): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 5003): Opened MyDB.db in read-only mode
,D/Process (  904): killProcessQuiet, pid=4186
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4186:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/Prism.ItemManager( 1243): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1243): loadItems() com.htc.launcher.pageview.WidgetManager@41e92ff0 +
,I/Prism.WidgetManager( 1243): onLoadItems() +
,I/ActivityManager(  904): Recipient 4186
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  904): Client com.google.android.music (pid 4186): Died!
,I/Icing   ( 2599): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox

```
