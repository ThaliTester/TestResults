#### Test 506502784dae475_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
,V/LightsService(  906): setLight #0: color=#3f
V/LightsService(  906): setLight #0: color=#3b
V/LightsService(  906): setLight #0: color=#35
V/LightsService(  906): setLight #0: color=#2e
V/LightsService(  906): setLight #0: color=#27
V/LightsService(  906): setLight #0: color=#21
V/LightsService(  906): setLight #0: color=#1a
V/LightsService(  906): setLight #0: color=#14
--------- beginning of /dev/log/main
E/cutils-trace( 3879): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3879): ====startRecUseTime====
D/htc.customization.log.level( 3879):  is 
W/CustomizationLogLevel( 3879): Level value is invalid, use default level 2
D/CustomizationManager( 3879):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3879): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3879): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3879): Parsing tag category name = system
I/CustomizationCIDLoader( 3879): Parsing tag category name = application
I/CustomizationCIDLoader( 3879): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3879): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3879): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3879): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3879): Parsing tag category name = Settings
D/CustomizationManager( 3879):  Read CID file spent 0.094 (s)
D/CustomizationManager( 3879):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 3879): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3879): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3879): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3879): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3879
D/PMS     (  906): acquireHCC(424cf4d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(42395398): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x68344090 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113014344
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f97190
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
D/PMS     (  906): acquireWL(42241470): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3890 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1249): [trimMemory] 20
W/asset   ( 3890): Copying FileAsset 0x5c8a2428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3890): Binding Chromium to main looper Looper (main, tid 1) {41e2dd30}
I/LibraryLoader( 3890): Expected native library version number "",actual native library version number ""
I/chromium( 3890): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3890): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42601248): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  906): acquireWL(42293750): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42076548:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3890): 1105481296: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): releaseWL(42601248): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3890): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3890): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3890): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3890): Local Branch: 
I/Adreno-EGL( 3890): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3890): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3890):                  aa63bbd948f41d15fc72f585e
W/chromium( 3890): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3890): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3890): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3890): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3890): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3890): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3890): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3890): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3890): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3890): CordovaWebView is running on device made by: HTC
,W/AwContents( 3890): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +247ms
I/InputMethodManagerService(  906): Disable input method client, pid=1249
,I/InputMethodManagerService(  906): Enable input method client, pid=3890
W/ResourceType( 3890): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3890): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e763d8, mServedView=org.apache.cordova.engine.SystemWebView{41e3c168 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 3890): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(42241470): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3890): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3890): JniHelper::setJavaVM(0x419ed010), pthread_self() = 1663642568
,D/JX-Cordova( 3890): jxcore cordova android initializing
,W/dalvikvm( 3890): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 11.585MB for 95956-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 11.639MB for 143930-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 11.746MB for 215890-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 12.192MB for 485740-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 13.193MB for 1092904-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 14.054MB for 1639352-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 15.436MB for 2459024-byte allocation
,I/dalvikvm-heap( 3890): Grow heap (frag case) to 17.449MB for 3688532-byte allocation
,W/jxcore-log( 3890): Initializing JXcore engine
,W/jxcore-log( 3890): JXcore engine is ready
,W/jxcore-log( 3890): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(424cf4d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(42395398): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3890): Platform android
W/jxcore-log( 3890): 
,W/jxcore-log( 3890): Process ARCH arm
W/jxcore-log( 3890): 
,I/jxcore-log( 3890): JXcore Cordova bridge is ready!
I/jxcore-log( 3890): 
,W/jxcore-log( 3890): JXcore engine is started
,I/chromium( 3890): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3890): Toggling radios to true
I/jxcore-log( 3890): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): checking for enable restriction...
D/BluetoothManagerService(  906): checkBTEasState, ret=true
,I/BluetoothManagerService(  906): isBluetoothRestricted(): false
D/BluetoothManagerService(  906): enable(): region ID = 6
,D/BluetoothManagerService(  906): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 1
W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1338
,W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  906): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3890): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1245
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=3890, uid=10389
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  906): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3938 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/PMS     (  906): acquireWL(43b480a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiManager( 3890): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 3890): reconnect: Base Package Name=com.test.thalitest, uid=10389
I/jxcore-log( 3890): Radios toggled
I/jxcore-log( 3890): 
,D/AdapterServiceConfig( 3938): Adding HeadsetService
D/AdapterServiceConfig( 3938): Adding A2dpService
D/AdapterServiceConfig( 3938): Adding HidService
D/AdapterServiceConfig( 3938): Adding HealthService
D/AdapterServiceConfig( 3938): Adding PanService
,D/AdapterServiceConfig( 3938): Adding GattService
,W/linker  ( 3938): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3938): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43449330:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3938): make
,I/BluetoothAdapterState( 3938): Entering OffState
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3938): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  906): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter( 3890): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e28af0
,D/BluetoothAdapter( 3890): onBluetoothServiceUp done
,D/BluetoothAdapter( 1198): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42251368
,D/BluetoothAdapter( 1198): onBluetoothServiceUp done
,D/BluetoothAdapter( 1107): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4219a300
,D/BluetoothAdapter( 1107): onBluetoothServiceUp done
,D/BluetoothAdapter( 1215): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e75af0
D/BluetoothAdapter( 1215): onBluetoothServiceUp done
D/BluetoothAdapter(  906): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@43456778
,D/BluetoothAdapter(  906): onBluetoothServiceUp done
D/BluetoothAdapter( 1230): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f609e8
,D/BluetoothAdapter( 1230): onBluetoothServiceUp done
D/BluetoothAdapter( 3938): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41e47d30
D/BluetoothAdapter( 3938): onBluetoothServiceUp done
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3938): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3938): Setting state to 11
I/BluetoothAdapterState( 3938): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3938): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  906): +onBluetoothStateChange prev=10 new=11
,D/BluetoothBondStateMachine( 3938): make
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3938): StableState(): Entering Off State
,I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3938): Received start request. Starting profile...
D/PMS     (  906): acquireWL(43451868): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
,D/PMS     (  906): releaseWL(43451868): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/HeadsetStateMachine( 3938): Version 1.6
D/HeadsetStateMachine( 3938): make
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3964 uid=10040 gids={50040, 3002, 3001}
,I/HeadsetStateMachine( 3938): setCurrentDevice, the latest mCurrentDevice is:null
,I/BluetoothAdapterState( 3938): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3938): Received start request. Starting profile...
V/Avrcp   ( 3938): make
,D/Avrcp   ( 3938): fillIntentFilter()
,D/A2dpStateMachine( 3938): make
,D/A2dpStateMachine( 3938): Enter Disconnected: -2
,D/HidService( 3938): Received start request. Starting profile...
,D/HealthService( 3938): Received start request. Starting profile...
,D/HtcBtWidget_BTWidgetProvider( 3964): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3964): updateWidget(context) for widget: 
,D/PanService( 3938): Received start request. Starting profile...
,D/BluetoothTethering(  906): supplyMessenger
D/BluetoothTethering(  906): supplyMessenger mAsyncChannel is null
,D/BluetoothTethering(  906): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  906): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 3938): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/Process (  906): killProcessQuiet, pid=3336
,I/ActivityManager(  906): Killing 3336:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/BtGatt.DebugUtils( 3938): handleDebugAction() action=null
D/BtGatt.GattService( 3938): Received start request. Starting profile...
D/BtGatt.GattService( 3938): start()
V/BluetoothPbapService( 3938): Pbap Service onCreate
V/BluetoothPbapService( 3938): Starting PBAP service
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 11
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 11
E/BluetoothMasService( 3938): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3938): Add permission for SmsProvider.
V/BluetoothMasService( 3938): Starting MAS instances
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 11
I/MailMessageReceiver( 3938): reg:com.android.bluetooth.btservice.AdapterApp@41e3b298 with com.htc.util.mail.MailMessageReceiver@41e7b6d0
I/MailManager( 3938): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41e7b6d0
V/EmailUtils( 3938): Manager Instance is not NULL
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3983 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  906): interfaceAdded wlan0
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): wlan0 is not a tetherable iface, ignoring
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): interfaceAdded p2p0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): p2p0 is not a tetherable iface, ignoring
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/ActivityManager(  906): Recipient 3336
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43b480a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3938): ============NULL aList========
,V/EmailUtils( 3938): <-getEmailAccountIdList
,V/BluetoothMasService( 3938): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 11
V/BluetoothMasService( 3938): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3938): Manager Instance is not NULL
D/EmailUtils( 3938): ============NULL aList========
,V/EmailUtils( 3938): <-getEmailAccountIdList
V/BluetoothSapService( 3938): Sap Service onCreate
,V/BluetoothSapService( 3938): initBinder
V/BluetoothSapService( 3938): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41e80ac0
,V/BluetoothSapReceiver( 3938): BluetoothSapReceiver init
,D/BluetoothSapService( 3938): setSapService()
V/BluetoothSapService( 3938): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3938): state: 12
,D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 11
D/BluetoothAdapterService( 3938): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3938): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3938): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3938): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3938): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 3938): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3938): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  906): got CMD_CHANNEL_FULLY_CONNECTED
,D/HeadsetPhoneState( 3938): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/Process (  906): killProcessQuiet, pid=3600
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 3938): Bluetooth STATE CHANGED to 11
I/ActivityManager(  906): Killing 3600:com.google.android.talk/u0a111 (adj 15): empty #17
,I/qcom-bluetooth( 4001): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  906): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4005 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4019): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4020): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4022): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4023): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4024): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4005): Received state change = 11
,I/qcom-bluetooth( 4025): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/PMS     (  906): releaseWL(42293750): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiService(  906): New client listening to asynchronous messages
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3698
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1339): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  906): Killing 3698:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3600
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3698
,I/wpa_supplicant( 4030): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4030): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4030): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4030): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4030): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4030): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4030): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4030): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4030): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4030): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4030): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4030): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4030): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4030): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4030): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4030): update_config=1
D/wpa_supplicant( 4030): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4030): device_name='Android_1950'
D/wpa_supplicant( 4030): manufacturer='HTC'
D/wpa_supplicant( 4030): model_name='HTC_PHONE'
D/wpa_supplicant( 4030): model_number='1234'
D/wpa_supplicant( 4030): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4030): p2p_oper_reg_class=126
D/wpa_supplicant( 4030): p2p_oper_channel=36
D/wpa_supplicant( 4030): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4030): persistent_reconnect=1
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 3
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4030): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4030): nl80211: RFKILL status not available
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4030): nl80211: Using driver-based roaming
D/wpa_supplicant( 4030): nl80211: TDLS supported
D/wpa_supplicant( 4030): nl80211: TDLS external setup
D/wpa_supplicant( 4030): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4030): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4030): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4030): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4030): nl80211: interface p2p0 in phy phy0
,D/wpa_supplicant( 4030): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4030): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73cb758
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73cb758
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4030): htc_wext_command_init +
E/wpa_supplicant( 4030): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4030): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4030): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4030): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4030): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4030): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  906): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  906): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4031 uid=10050 gids={50050}
,I/wpa_supplicant( 4030): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4030):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4030):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4030):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): nl80211: Flush PMKIDs
E/wpa_supplicant( 4030): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4030): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4043): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4044): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4031): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4031): updateWidget(context) for widget: 
,D/Process (  906): killProcessQuiet, pid=1307
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  906): Killing 1307:com.htc.sense.hsp/u0a55 (adj 15): empty #17
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/bt-btu  ( 3938): btu_task pending for preload complete event
,D/wpa_supplicant( 4030): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4030): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4030): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4030): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 4030): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4030): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4030): Using existing control interface directory.
D/wpa_supplicant( 4030): ctrl_iface bind(PF_UNIX) failed: Address already in use
,D/wpa_supplicant( 4030): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4030): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
,D/wpa_supplicant( 4030): P2P: Own listen channel: 11
D/wpa_supplicant( 4030): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4030): P2P: Add operating class 81
,I/wpa_supplicant( 4030): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4030): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4030): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4030): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 4030): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4030): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4030): disable_scan_offload=1
D/wpa_supplicant( 4030): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4030): update_config=1
D/wpa_supplicant( 4030): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4030): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4030): manufacturer='HTC',
D/wpa_supplicant( 4030): model_name='HTC Desire 820'
D/wpa_supplicant( 4030): model_number='HTC Desire 820'
D/wpa_supplicant( 4030): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4030): persistent_reconnect=1
D/wpa_supplicant( 4030): p2p_disabled=1
D/wpa_supplicant( 4030): hs20=1
D/wpa_supplicant( 4030): interworking=1
D/wpa_supplicant( 4030): Line: 18 - start of a new network block
D/wpa_supplicant( 4030): key_mgmt: 0x2,
D/wpa_supplicant( 4030): priority=1 (0x1)
,D/wpa_supplicant( 4030): signinfail=0 (0x0)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 1307
,D/wpa_supplicant( 4030): Priority group 1
D/wpa_supplicant( 4030):    id=0 ssid='NG700'
I/wpa_supplicant( 4030): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4030): nl80211: RFKILL status not available
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4030): nl80211: Using driver-based roaming
D/wpa_supplicant( 4030): nl80211: TDLS supported
D/wpa_supplicant( 4030): nl80211: TDLS external setup
D/wpa_supplicant( 4030): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4030): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4030): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4030): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4030): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4030): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4030): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73db718
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4030): htc_wext_command_init +
I/wpa_supplicant( 4030): htc_wext_command_init -
I/wpa_supplicant( 4030): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4030): Don't set 00 to countryID.conf
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4030): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4030): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4030): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4030): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4030): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,I/wpa_supplicant( 4030): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4030):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4030):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4030):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4030): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4030): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4030): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4030): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4030): TDLS: Driver uses external link setup
D/wpa_supplicant( 4030): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4030): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4030): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4030): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4030): Using existing control interface directory.
I/wpa_supplicant( 4030): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4030): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4030): Auto country group 1: ch36
I/wpa_supplicant( 4030): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4030): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 4030): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  906): uevent:
V/RegulatoryObserver(  906): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  906): Regulatory Country Code:DE
V/RegulatoryObserver(  906): Start wifi-crda service to run crda.
V/RegulatoryObserver(  906): Country Code is DE
V/RegulatoryObserver(  906): Send broadcast country code message.
I/RegulatoryObserver(  906): Broadcast intent for crda country code: DE
D/wpa_supplicant( 4030): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4030): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_906-2
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4030): nl80211: Event message available
D/wpa_supplicant( 4030): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4030): nl80211: Regulatory domain change
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4030): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4030): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4030): P2P: Add operating class 81
D/wpa_supplicant( 4030): P2P: Add operating class 115
D/wpa_supplicant( 4030): P2P: Add operating class 116
D/wpa_supplicant( 4030): P2P: Add operating class 117
D/wpa_supplicant( 4030): P2P: Update channel list
D/wpa_supplicant( 4030): p2p0: Updating hw mode
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4030): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4030): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4030): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4030): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4030): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): set wifi ON
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER MACADDR
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiConfigStore(  906): Loading config and enabling all networks
D/WifiNative-wlan0(  906): doString: LIST_NETWORKS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): list_network_info: ret=0x1, pos=0xb73de117 buf=0xb73de0e8
I/wpa_supplicant( 4030): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4030): 0	NG700	any	
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiNative-wlan0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  906): 0	NG700	any	
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 bssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 priority
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 psk
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4030): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 proto
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  906): Failed to look-up a string: W
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_mgmt
I/wpa_supplicant( 4030): wpa_supplicant_scan enter
I/wpa_supplicant( 4030): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4030): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4030): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4030): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4030): nl80211: Event message available
D/wpa_supplicant( 4030): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 group
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
I/IntentController( 1107): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 limited
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 eap
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 phase2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/WIFI_ICON( 1107): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 password
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/HtcWiFiWidget_WiFiWidgetProvider( 4031): onWiFiStateChanged() for widget: 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/HtcWiFiWidget_WiFiWidgetProvider( 4031): updateWidget(context) for widget: 
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 private_key
W/Wi,fiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4030): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  906): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  906): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4030): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4030): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET manufacturer HTC
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4030): manufacturer='HTC'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4030): model_name='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4030): model_number='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4030): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET auto_interworking 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4030): auto_interworking=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): SET_SCREEN_ON:On
I/wpa_supplicant( 4030): htc_wext_set_keepalive +
I/wpa_supplicant( 4030): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4030): getPrivFuncNum +	
I/wpa_supplicant( 4030): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
I/wpa_supplicant( 4030): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET ps 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4030): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
W/Settings(  906): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  906): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): SETBAND: 0
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4030): P2P: Add operating class 81
D/wpa_supplicant( 4030): P2P: Add operating class 115
D/wpa_supplicant( 4030): P2P: Add operating class 116
D/wpa_supplicant( 4030): P2P: Add operating class 117
D/wpa_supplicant( 4030): P2P: Update channel list
I/wpa_supplicant( 4030): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4030): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4030): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4030): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4030): p2p_oper_reg_class=126
D/wpa_supplicant( 4030): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4030): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4030): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4030): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4030): p2p_oper_channel=36
E/wpa_supplicant( 4030): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4030): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4030): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4030): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4030): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: BSS_FLUSH 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 4030): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4030): wpa_supplicant_scan enter
D/WifiNative-wlan0(  906):    returned true
D/WifiMonitor(  906): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  906): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4030): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4030): persistent_reconnect=1
I/wpa_supplicant( 4030): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET device_name Android_1950
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/WifiStateMachine(  906): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiP2pService(  906): P2pEnablingState
D/WifiP2pService(  906): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2p socket connection successful
D/WifiP2pService(  906): P2pEnabledState
D/WifiP2pService(  906): sending p2p connection changed broadcast
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  906): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  906): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 4030): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4030): device_name='Android_1950'
I/wpa_supplicant( 4030): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4030): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4030): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4030): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4030): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4030): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4030): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4030): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4030): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4030): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4030): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4030): Single channel concurrency preference: sta
I/wpa_supplicant( 4030): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "STATUS"
I/QuickSettingWifi( 1107): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  906): doBoolean: P2P_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4030): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4030): P2P: Stopping find
D/wpa_supplicant( 4030): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4030): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4030): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4030): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4030): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: LIST_NETWORKS
W/WifiHW  (  906): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4030): list_network_info: ret=0x22, pos=0xb73de10a buf=0xb73de0e8
I/wpa_supplicant( 4030): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4030): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  906): doBoolean: AP_SCAN 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  906):    returned false
D/WifiNative-p2p0(  906): doBoolean: SET wifi_display 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4030): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4030): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4030): WFD: Update WFD IE
I/wpa_supplicant( 4030): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4030): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  906):    returned true
D/WifiP2pService(  906): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  906): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  906):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  906):  primary type: 10-0050F204-5
D/WifiDisplayController(  906):  secondary type: null
D/WifiDisplayController(  906):  wps: 0
D/WifiDisplayController(  906):  grpcapab: 0
D/WifiDisplayController(  906):  devcapab: 0
D/WifiDisplayController(  906):  status: 3
D/WifiDisplayController(  906):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  906):  WFD CtrlPort: 0
D/WifiDisplayController(  906):  WFD MaxThroughput: 0
D/WifiP2pService(  906): sending p2p persistent groups changed broadcast
D/WifiP2pService(  906): InactiveState
D/WifiP2pService(  906): InactiveState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0(  906): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  906): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4030): WFD: Set subelement 0
D/wpa_supplicant( 4030): WFD: Update WFD IE
I/wpa_supplicant( 4030): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4030): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  906):    returned true
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  906): convertEffect before=902
D/HtcEffectManager(  906): convertEffect after=902
D/WifiDisplayController(  906): Successfully set WFD info.
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  906):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  906):  primary type: 10-0050F204-5
D/WifiDisplayController(  906):  secondary type: null
D/WifiDisplayController(  906):  wps: 0
D/WifiDisplayController(  906):  grpcapab: 0
D/WifiDisplayController(  906):  devcapab: 0
D/WifiDisplayController(  906):  status: 3
D/WifiDisplayController(  906):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  906):  WFD CtrlPort: 7236
D/WifiDisplayController(  906):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4030): nl80211: Event message available
D/wpa_supplicant( 4030): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4030): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4030): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 4030): nl80211: Survey data missing
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4030): Sorted scan results
I/wpa_supplicant( 4030): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 4030): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4030): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 4030): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 4030): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 4030): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4030): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4030): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4030): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4030): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4030): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4030): wpa_supplicant_pick_network+
I/wpa_supplicant( 4030): Selecting BSS from priority group 1
I/wpa_supplicant( 4030): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4030): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4030): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4030): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4030):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4030):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 4030): Start print parameters
I/wpa_supplicant( 4030): wpa_s->wpa_state is 3
I/wpa_supplicant( 4030): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4030): isConcurrentMode() is 0
I/wpa_supplicant( 4030): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4030): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4030): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4030): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4030): wpa_s->reassociate is 0
I/wpa_supplicant( 4030): wpa_s->is_screen_on 1
I/wpa_supplicant( 4030): wpa_s->ifname wlan0
I/wpa_supplicant( 4030): End print parameters
I/wpa_supplicant( 4030): selected network = 1
D/wpa_supplicant( 4030): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73dc4e8  current_ssid=0x0
D/wpa_supplicant( 4030): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4030): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4030): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4030): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4030): check if in concurrent case
,I/wpa_supplicant( 4030): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 4030): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4030): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4030): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4030): RSN: PMKSA cache search - network_ctx=0xb73dc4e8 try_opportunistic=0
D/wpa_supplicant( 4030): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4030): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4030): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4030): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4030): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4030): nl80211: Unsubscribe mgmt frames handle 0xb73db718 (mode change)
D/wpa_supplicant( 4030): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73db718
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Register frame type=0xd0 nl_handle=0xb73db718
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4030): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4030):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4030):   * freq=2412
D/wpa_supplicant( 4030):   * Auth Type 0
D/wpa_supplicant( 4030):   * WPA Versions 0x2
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4030): nl80211: Connect request send successfully
D/wpa_supplicant( 4030): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 S,SID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4030): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 4030): reply (489) for get BSS: id=0
I/wpa_supplicant( 4030): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4030): freq=5220
I/wpa_supplicant( 4030): level=-51
I/wpa_supplicant( 4030): tsf=0000000104850966
I/wpa_supplicant( 4030): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4030): ssid=NG7005g
I/wpa_supplicant( 4030): ====
I/wpa_supplicant( 4030): id=1
I/wpa_supplicant( 4030): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4030): freq=2412
I/wpa_supplicant( 4030): level=-50
I/wpa_supplicant( 4030): tsf=0000000104850957
I/wpa_supplicant( 4030): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4030): ssid=NG700
I/wpa_supplicant( 4030): ====
I/wpa_supplicant( 4030): id=2
I/wpa_supplicant( 4030): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 4030): freq=2412
I/wpa_supplicant( 4030): level=-51
I/wpa_supplicant( 4030): tsf=0000000104850972
I/wpa_supplicant( 4030): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4030): ssid=01ABC
I/wpa_supplicant( 4030): ====
I/wpa_supplicant( 4030): id=3
I/wpa_supplicant( 4030): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4030): freq=2427
I/wpa_supplicant( 4030): level=-78
I/wpa_supplicant( 4030): tsf=0000000104850976
I/wpa_supplicant( 4030): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4030): ssid=Gonzos
I/wpa_supplicant( 4030): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 104850966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 104850957, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiManager( 1198): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 104850972, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 104850976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/bt-btu  ( 3938): btu_task received preload complete event
,D/bt-btm  ( 3938): btm_acl_device_down
D/bt-btm  ( 3938): btm_acl_reset_paging
,D/bt-btm  ( 3938): btm_acl_set_discing
,I/bt-btm  ( 3938): btm_reset_complete
,I/bt-btm  ( 3938): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4030): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4030): nl80211: Event message available
D/wpa_supplicant( 4030): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4030): nl80211: Connect event
D/wpa_supplicant( 4030): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4030): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4030): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4030): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4030): Add randomness: count=6 entropy=4
I/wpa_supplicant( 4030): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4030): TDLS: Remove peers on association
D/wpa_supplicant( 4030): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4030): EAPOL: SUPP_PAE entering state CONNECTING
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 4030): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4030): htc_wext_set_keepalive +
I/wpa_supplicant( 4030): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4030): getPrivFuncNum +	
I/wpa_supplicant( 4030): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 4030): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4030): Get randomness: len=32 entropy=5
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48,
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Setting MAC Address to c0:ff:d4:d3:aa:48,
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database,
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/bt-btm  ( 3938): Start reading local supported commands
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/bt-btm  ( 3938): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 3938): BTM reads next extended features page (1)
,D/bt-btm  ( 3938): BTM reads next extended features page (2)
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 4030): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb73db9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4030):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4030): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4030): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f60b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4030):    broadcast key
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4030): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4030): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 4030): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4030): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4030): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 4030): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4030): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4030): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4030): set send_ind_to_ndc = 0
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4030): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4030): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4030): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4030): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4030): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4030): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4030): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4030): EAPOL authentication completed successfully
I/wpa_supplicant( 4030): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4030): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4030): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4030): nl80211: if_removed already cleared - ignore event
D/bt-btm  ( 3938): BTM reached last extended features page (2)
,D/bt-btm  ( 3938): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/bt-btm  ( 3938): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/bt-btm  ( 3938): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/wpa_supplicant( 4030): EAPOL: disable timer tick
D/wpa_supplicant( 4030): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4030): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 18
D/bt-btm  ( 3938): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 3938): btm_read_ble_wl_size 
D/bt-btm  ( 3938): btm_read_white_list_size_complete 
,D/bt-btm  ( 3938): btm_get_ble_buffer_size 
D/bt-btm  ( 3938): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3938): btm_read_ble_local_supported_features 
D/bt-btm  ( 3938): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3938): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3938): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3938): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3938): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3938): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3938): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3938): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3938): BTM_SetInquiryMode
I/bt-btm  ( 3938): BTM_SetPageScanType
I/bt-btm  ( 3938): BTM_SetInquiryScanType
D/bt-btm  ( 3938): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3938): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3938): BTM_BleLoadLocalKeys
D/bt-btm  ( 3938): BTM_BleLoadLocalKeys
I/bt-btm  ( 3938): BTM_Sec: application registered
E/bt-btm  ( 3938): BTM_SecRegister:p_cb_info->p_le_callback == 0x61fff941 
I/bt-btm  ( 3938): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3938): SMP_Register state=0
E/bt-btm  ( 3938): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61fff941 
I/bt-btm  ( 3938): BTM_Sec: application registered
D/bt-btm  ( 3938): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3938): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3938): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3938): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3938): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3938): BTM_RegBusyLevelNotif
,I/bt-att  ( 3938): GATT_Register
D/bt-att  ( 3938): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3938): allocated gatt_if=3
I/bt-att  ( 3938): GATT_StartIf gatt_if=3
D/bt-att  ( 3938): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3938): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3938): Calling BTA_HhEnable
E/bt-btif ( 3938): Calling BTA_HhEnable
I/bt-btm  ( 3938): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3938): BTM_AllocateSCN
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3938): BTM_AllocateSCN
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btm  ( 3938): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3938):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3938):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3938): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3938): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
D/bt-avp  ( 3938): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3938): AVRC_AddRecord uuid: 110e
,I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btm  ( 3938): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3938):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: f8:95:c7:87:3c:51
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3938): GATT_Register
D/bt-att  ( 3938): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3938): allocated gatt_if=4
I/bt-att  ( 3938): GATT_StartIf gatt_if=4
D/bt-att  ( 3938): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3938): gatt_find_the_connected_bda found=0 found_idx=7
D/WifiApDatabaseHandler(  906): updateConnectedAP...
E/bt-btif ( 3938): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3938): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3938): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:1 len:14
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3938): BTM_GetHCIConnHandle
I/bt-btm  ( 3938): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
,D/bt-btm  ( 3938): BTM_SecAddDevice : rmt_io_caps is 0 
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3938): Scan Mode:20
I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3938): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:8 len:66
,D/BluetoothAdapter( 3938): getBluetoothService(): entry
,D/BluetoothAdapter( 3938): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3938): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e8b9b8
,D/BluetoothDevice( 3938): getService : Register callback
,D/BluetoothAdapterProperties( 3938): Adding bonded device:B0:C5:59:3F:75:69
,D/BluetoothAdapterProperties( 3938): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3938): Adding bonded device:80:01:84:8A:B3:68
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/BluetoothAdapterProperties( 3938): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/BluetoothAdapterProperties( 3938): Adding bonded device:14:B4:84:21:3B:49
,D/BluetoothAdapterProperties( 3938): Adding bonded device:F8:95:C7:87:3C:51
D/BluetoothAdapterProperties( 3938): Adding bonded device:08:EC:A9:50:76:27
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/BluetoothAdapterProperties( 3938): Adding bonded device:7C:F9:0E:34:8A:A0
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/BluetoothAdapterProperties( 3938): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 3938): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3938): Adding bonded device:38:94:96:B5:06:DC
,I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/WISPrService( 3302): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/WISPrService( 3302): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BluetoothRemoteDevices( 3938): Remote class is:5898764
,I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiService(  906): New client listening to asynchronous messages
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 3938): Remote class is:5898764
,I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4030): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/WifiStateMachine(  906): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  906):    returned true
,D/BluetoothRemoteDevices( 3938): Remote class is:5898764
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): Power_Mode_Type mode = 1
,I/wpa_supplicant( 4030): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(429a6108): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  906):    returned null
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BluetoothRemoteDevices( 3938): Remote class is:5898764
,I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43aae788 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43aae788 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
I/QuickSettingWifi( 1107): receive.wifiConnect:false wifiAPname:null elapse:0
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
I/bt-btif ( 3938): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3938): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothRemoteDevices( 3938): Remote class is:5898764
I/bt-btif ( 3938): BTA_JvEnable
I/bt-btm  ( 3938): BTM_ReadConnectability
I/bt-btm  ( 3938): BTM_ReadDiscoverability
I/bt-btm  ( 3938): BTM_SetDiscoverability
I/bt-btm  ( 3938): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3938): br_edr_supported=0x2
I/bt-btm  ( 3938): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3938): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3938): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3938): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3938): BTM_SetConnectability
I/bt-btm  ( 3938): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3938): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3938): BTM_SetDiscoverability
I/bt-btm  ( 3938): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3938): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3938): br_edr_supported=0x0
I/bt-btm  ( 3938): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3938): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3938): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3938): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3938): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3938): BTM_SetConnectability
I/bt-btm  ( 3938): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3938): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3938): bta_pan_co_init
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3938): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3938):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3938):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3938): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3938):        ,        : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3938): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3938):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
E/bt_mct  ( 3938): hci lib postload completed
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3938): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3938): ScanMode =  20
D/BluetoothAdapterProperties( 3938): State =  11
I/bt-btm  ( 3938): BTM_SetDiscoverability
I/bt-btm  ( 3938): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
I/bt-btif ( 3938): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3938): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3938): br_edr_supported=0x0
I/bt-btm  ( 3938): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3938): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3938): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3938): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3938): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3938): BTM_SetConnectability
I/bt-btm  ( 3938): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3938): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3938): btm_ble_update_adv_flag new=0x0
I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:7 len:4
D/bt-btm  ( 3938): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3938): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3938): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3938): Scan Mode:21
I/bt-btif ( 3938): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3938): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3938): Discoverable Timeout:120
D/BluetoothAdapterProperties( 3938): Setting state to 12
I/BluetoothAdapterState( 3938): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3938): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1215): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3938): Entering On State
D/BluetoothHeadset( 1215): Proxy object connected
D/BluetoothAdapterService(1105482176)( 3938): Get Bonded Devices being called
D/BluetoothHeadset( 1215): onBluetoothStateChange: up=true
D/BluetoothPhoneService( 1215): BluetoothHeadset onServiceConnected
W/BluetoothHeadset( 1215): Proxy not attached to service
D/BluetoothAdapterProperties( 3938): getBondedDevices: length=11
D/BluetoothHeadset( 1107): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1215): Proxy object connected
D/BluetoothHeadset( 1107): Proxy object connected
I/QuickSettingMiniLite( 1107): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@42140840
D/BluetoothA2dp(  906): onBluetoothStateChange: up=true
D/BluetoothHeadset(  906): onBluetoothStateChange: up=true
D/BluetoothPan(  906): onBluetoothStateChange(on) call bindService
W/ContextImpl(  906): Calling a method in the system process ,without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset(  906): Proxy object connected
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  906): 1114777368: getState(). Returning 12
I/IntentController( 1107): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3938): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3938): ***********state = 12
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/PMS     (  906): acquireWL(43b87110): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/PMS     (  906): releaseWL(43b87110): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  906): acquireWL(427f8098): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3302 1000 null
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothMasReceiver( 3938): Bluetooth STATE CHANGED to 12
D/BluetoothA2dp(  906): Proxy object connected
D/BluetoothAdapter(  906): 1114777368: getState(). Returning 12
D/HtcBtWidget_BTWidgetProvider( 3964): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3964): updateWidget(context) for widget: 
V/BluetoothSapReceiver( 3938): SapReceiver onReceive 
V/BluetoothSapReceiver( 3938): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3938):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3938): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 12
D/PMS     (  906): releaseWL(427f8098): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  906): acquireWL(428386d8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3302 1000 null
D/BluetoothPan(  906): BluetoothPAN Proxy object connected
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 12
D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
V/BluetoothMasService( 3938): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3938): Manager Instance is not NULL
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e11500:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3302): new LocationAgent instance!!
D/HtcTagManager( 3302): HtcTagManager construction complete
D/BluetoothAdapterService(1105482176)( 3938): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3938): getBondedDevices: length=11
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
D/EmailUtils( 3938): ============NULL aList========
V/EmailUtils( 3938): <-getEmailAccountIdList
V/BluetoothSapService( 3938): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3938): state: 12
D/BluetoothInputDevice( 3302): BluetoothInputDevice()
D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 12
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
D/BluetoothInputDevice( 3302): BluetoothInputDevice(): Binding service...
,W/ContextImpl( 3938): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
,D/BluetoothPan( 3302): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 8
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
,D/BluetoothPan( 3302): BluetoothPan(): Binding service...
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
V/BluetoothSapService( 3938): Starting SAP server process
V/BluetoothPbapService( 3938): Handler(): got msg=1
V/BluetoothPbapService( 3938): Pbap Service startRfcommSocketListener
D/BluetoothMap( 3302): Create BluetoothMap proxy object
V/BluetoothPbapService( 3938): Pbap Service initSocket
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/BluetoothMap( 3302): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothSap( 3302): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 10
D/BluetoothAdapter( 3938): getBluetoothService(): entry
,W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3938): SOCK FLAG = 1 ***********************
D/BluetoothAdapter( 1107): 1108198944: getState(). Returning 12
,I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
I/bt-btm  ( 3938): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3938):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/BluetoothPbap( 3302): BluetoothPbap()
V/BluetoothPbapService( 3938): Succeed to create listening socket 
,V/BluetoothPbapService( 3938): Accepting socket connection...
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 11
,D/BluetoothAdapter( 1107): 1108198944: getState(). Returning 12
,W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
D/BluetoothPbap( 3302): BluetoothPbap(): Binding service...
I/QuickSettingBluetooth( 1107): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1107): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothA2dp( 3302): BluetoothA2dp()
V/BluetoothMasService( 3938): handleMessage: mIsEmailEnabledtrue
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 12
,V/BtMns   ( 3938): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
,D/BluetoothA2dp( 3302): BluetoothA2dp(): Binding service...
,D/BluetoothMasService( 3938): Map_prev 1
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothAdapter( 3938): getBluetoothService(): entry
W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 3302): BluetoothHeadset()
D/BluetoothManagerService(  906): registerStateChangeCallback+
E/BluetoothServiceJni( 3938): SOCK FLAG = 3 ***********************
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
I/bt-btm  ( 3938): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3938):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
D/BluetoothHeadset( 3302): BluetoothHeadset(): Binding service...
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3938): getBluetoothService(): entry
,W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3938): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
,I/bt-btm  ( 3938): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3938):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3302): startProxy
,W/ContextImpl( 3302): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3302): LocalBluetoothProfileManager construction complete
,D/BluetoothSapService( 3938): Sap_prev 1
,V/BluetoothSapService( 3938): SAP Service startRfcommListenerThread
V/BluetoothSapService( 3938): Sap Service initRfcommSocket
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/DockEventReceiver( 3302): finishStartingService: stopping service
D/BluetoothPan( 3302): BluetoothPAN Proxy object connected
D/PanProfile( 3302): Bluetooth service connected
D/BluetoothA2dp( 3302): Proxy object connected
D/A2dpProfile( 3302): Bluetooth service connected
D/BluetoothAdapter( 3938): getBluetoothService(): entry
W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
E/BluetoothServiceJni( 3938): SOCK FLAG = 3 ***********************
I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
I/bt-btm  ( 3938): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3938):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3938): Succeed to create listening socket 
V/BluetoothSapService( 3938): Accepting socket connection...
D/BluetoothHeadset( 3302): Proxy object connected
D/HeadsetProfile( 3302): Bluetooth service connected
D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
D/BluetoothAdapter( 1107): 1108198944: getState(). Returning 12
D/BluetoothInputDevice( 3302): Proxy object connected
D/HidProfile( 3302): Bluetooth service connected
I/QuickSettingMiniLite( 1107): updateLiteState:no connect device!
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4005): onCreate: going to find gatt base service first.
,D/BluetoothAdapter( 3302): 1107089080: getState(). Returning 12
,V/TAG     ( 3938): android.bluetooth.IBluetoothSap
,V/BluetoothSapService( 3938): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41e82200
,V/BluetoothPbapService( 3938): Pbap Service onBind
,D/PMS     (  906): releaseWL(428386d8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a964d0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/SapServerProfile( 3302): Bluetooth service connected
D/BluetoothPbap( 3302): Proxy object connected
D/PbapServerProfile( 3302): Bluetooth service connected
D/[HTC_BLE][Constants]( 4005):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4005):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4005):  + discoverServicesOnBonded = false
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3938): getBluetoothService(): entry
,W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
,I/BluetoothFtpService( 3938): Ftp Service onCreate
,D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 12
,D/BluetoothMasReceiver( 3938): Bluetooth STATE CHANGED to 12
,E/BluetoothServiceJni( 3938): SOCK FLAG = 0 ***********************
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4005):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4005): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e4b1a8
I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/[HTC_BLE][Constants]( 4005): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4005): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4005): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4005): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4005): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4005): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
I/bt-btm  ( 3938): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3938):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 3938): Accept thread started.
,D/BluetoothFtpService( 3938): Ftp_prev 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4005): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3938): getBluetoothService(): entry
,W/BluetoothAdapter( 3938): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3938): SOCK FLAG = 1 ***********************
I/bt-btif ( 3938): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3938): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3938): Write Extended Inquiry Response to controller
I/bt-btif ( 3938): BTA_JvRfcommStartServer
I/bt-btm  ( 3938): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 3938):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3938): Run Accept thread
,D/BluetoothAdapter( 3938): 1105500352: getState(). Returning 12
V/BluetoothMasService( 3938): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3938): Manager Instance is not NULL
,D/HtcTagManager( 3302): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4005): Received state change = 12
D/HtcTagProfile( 3302): setup proxy
D/HtcPxpProfile( 3302): setup proxy
,D/HtcFmpProfile( 3302): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4005): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4005): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41e4b1a8
,D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4005): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e4b1a8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4005): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e4b1a8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e56190
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4005): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41e4b1a8
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43badb18:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,D/EmailUtils( 3938): ============NULL aList========
V/EmailUtils( 3938): <-getEmailAccountIdList
,D/BluetoothMasService( 3938): Map_prev 1
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3822): new LocationAgent instance!!
,D/HtcTagManager( 3822): HtcTagManager construction complete
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothInputDevice( 3822): BluetoothInputDevice()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothInputDevice( 3822): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  906): Registered receivers: 14
,D/BluetoothPan( 3822): BluetoothPan()
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/wpa_supplicant( 4030): EAPOL: startWhen --> 0
D/wpa_supplicant( 4030): EAPOL: disable timer tick
D/BluetoothManagerService(  906): Registered receivers: 15
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothPan( 3822): BluetoothPan(): Binding service...
,D/BluetoothMap( 3822): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/RingtoneManager( 4005): getExternalStorageState=mounted
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
,E/BluetoothMap( 3822): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothSap( 3822): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 17
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3822): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 18
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothPbap( 3822): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3822): BluetoothA2dp()
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[1]: Daisy
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/BluetoothA2dp( 3822): BluetoothA2dp(): Binding service...
D/BluetoothManagerService(  906): Registered receivers: 19
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[11]: Thalia
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4005):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothHeadset( 3822): BluetoothHeadset()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 20
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothHeadset( 3822): BluetoothHeadset(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4005): BleProfilesStateMachine is initialized...
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4005): Enter IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4005): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4005): initScanModeInterface: true
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429346d0:true
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4005): loadDeviceConfiguration() init =true
D/HtcTagManager( 3822): startProxy
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4005):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 4005):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4005):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4005):  + discoverServicesOnBonded = false
,W/ContextImpl( 3822): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3822): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/LocalBluetoothProfileManager( 3822): setBluetoothStateOn
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/HtcTagManager( 3822): startProxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4005): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41e56190
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/BluetoothAdapterService(1105482176)( 3938): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3938): getBondedDevices: length=11
D/BluetoothAdapter( 3822): getBluetoothService(): entry
D/BluetoothAdapter( 3822): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3822): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41e857e8
D/BluetoothDevice( 3822): getService : Register callback
E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,E/BluetoothDevice( 3822): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): addHtcTagProfiles
,D/BluetoothInputDevice( 3822): Proxy object connected
,D/HidProfile( 3822): Bluetooth service connected
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/AuthorizationBluetoothService( 1339): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
,D/BluetoothPan( 3822): BluetoothPAN Proxy object connected
D/PanProfile( 3822): Bluetooth service connected
D/SapServerProfile( 3822): Bluetooth service connected
D/BluetoothPbap( 3822): Proxy object connected
D/PbapServerProfile( 3822): Bluetooth service connected
D/BluetoothA2dp( 3822): Proxy object connected
,D/A2dpProfile( 3822): Bluetooth service connected
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/BluetoothHeadset( 3822): Proxy object connected
,D/HeadsetProfile( 3822): Bluetooth service connected
,D/BluetoothAdapter( 3822): 1105510696: getState(). Returning 12
,D/HtcTagManager( 3822): onServiceConnected
D/HtcTagProfile( 3822): setup proxy
D/HtcPxpProfile( 3822): setup proxy
,D/HtcFmpProfile( 3822): setup proxy
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4030): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(429a6108): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4030): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20468 delay=15s
,I/IntentController( 1107): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1107): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WISPrService( 3302): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@427add98
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(428fdca8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,I/QuickSettingWifi( 1107): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(428fdca8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4118 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/PMS     (  906): acquireWL(4281ef08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3732/10100)
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
I/ConnectivityHelper( 1249): [onReceive] WIFI(1): CONNECTED
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =be42 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1249/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3377/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3732/10100)
D/PMS     (  906): acquireWL(423618f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42908ba0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): acquireWL(428fbdb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 9
D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(427f4338): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): acquireWL(428e6df8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/MusicStore( 4118): Database version: 95
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 4118): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42a3e360): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ActivityManager(  906): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4144 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  906): releaseWL(423618f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1107): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1525): [EventService] EVENT_RESET_THEME_TIMESTAMP
,D/DotMatrix( 1525): [EventService] isTheSameDay:false,timestamp is early than today:true
,I/FeedActionBar( 1249): updateLastUpdatedTime(in String) LAST UPDATED 13:35
,D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,W/ContextImpl( 4118): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(429ad6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(429ad6c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(441c3678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(441c3678): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4441f378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4441f378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(429b1648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  906): NTP server returned: 1449751008027 (Thu Dec 10 13:36:48 CET 2015) reference: 106849 certainty: 12 system time offset: -81
,D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME_FINISHED
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  906): releaseWL(429b1648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1964): Failed to find provider info for com.android.contacts.metadata
D/PMS     (  906): releaseWL(4281ef08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(427497c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4118): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24991, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  906): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 106943, reason: UserStart
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(428e6df8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
W/dalvikvm( 1964): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNati,ve-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(427497c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(428dcb40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4247c7a8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4247c7a8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423b8338
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42743508
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/PMS     (  906): Going to sleep due to screen timeout...
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
E/ExternalAccountType( 1322): Unsupported attribute readOnly
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4118): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/PMS     (  906): mWirelessDisplayManager is null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 4118): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4118, uid=10154, userID:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
E/Auth.Api.Credentials( 1964): [CredentialSyncAdapter] Unknown sync event.
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(428dcb40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43b43f88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(428fbdb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42960830): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
I/IntentController( 1107): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43b43f88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(44380a40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(44380a40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42af81c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/DelayedSyncController( 4144): Delaying sync.
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42908ba0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(44397200): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42af81c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43833f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43833f38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42a2bbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42a3e360): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0,
D/PhoneStatusBar( 1107): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a2bbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43bc4c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43bc4c60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42ca5e18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42960830): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42c92300): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/PMS     (  906): releaseWL(42ca5e18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4438f0a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44397200): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43a2b318): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
D/PMS     (  906): releaseWL(4438f0a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d64060): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d64060): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4144): Delaying sync.
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d5f290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42d5f290): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43a41860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43a2b318): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 317ms
D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
D/PMS     (  906): acquireWL(43976880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(43a41860): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=3890
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42aa9990)
D/PMN     (  906): wakingUp
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/NfcService( 1230): applyRouting -2
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): acquireWL(43f85fb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  906): acquireWL(42accfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43f85fb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(42accfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43fc7ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2450): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2450): [MTP][onReceive]-
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(43fc7ba8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MediaRouterService(  906): Client com.google.android.music (pid 4118): Registered
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1198): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/NfcService( 1230): applyRouting - 0
,D/NfcService( 1230): applyRouting -2
D/PMS     (  906): acquireWL(438ba178): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43968ba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): releaseWL(438ba178): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20469 delay=15s
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,I/MediaRouter( 4118): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(42c92300): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): SET_SCREEN_ON:On
I/wpa_supplicant( 4030): htc_wext_set_keepalive +
I/wpa_supplicant( 4030): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4030): getPrivFuncNum +	
I/wpa_supplicant( 4030): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4030): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43968ba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WIFI_ICON( 1107): WifiActivity: 3
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  374): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/NetworkMonitor( 4118): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,W/DriveInitializer( 1964): Awaiting to be initialized
W/DriveInitializer( 1964): Background init thread started
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1107): stop update clock
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4118/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2450/10021)
I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,W/ContextImpl( 1964): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4030): WiFioffload: SignalStrength: =97
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4190 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/NetworkPolicy(  906): updateScreenOn: false
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/MediaRouter( 4118): getSelectedRoute
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4118): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4118/10154)
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4118, uid=10154, userID:0
D/WIFI_ICON( 1107): updateWifiState: RSSI_CHANGED 3 -> 3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/StatusBar.NetworkController( 1107): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  906): acquireWL(42c67998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42c67998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43eaf368): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43eaf368): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43afe350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43afe350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4005): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4005): onScreenOn: 1449751008694
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4005): onScreenOn: 1449751008694
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423b8338
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423b8338, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42743508
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  906): goingToSleep
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42c6be88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20469 mDataStallAlarmIntent=PendingIntent{436a7d98: PendingIntentRecord{427532d0 android broadcastIntent}}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4030): SET_SCREEN_ON:Off
I/wpa_supplicant( 4030): htc_wext_set_keepalive +
I/wpa_supplicant( 4030): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4030): getPrivFuncNum +	
I/wpa_supplicant( 4030): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4030): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4030): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4030): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4030): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,W/DriveInitializer( 1964): Background init thread ended
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
D/PMS     (  906): acquireWL(437f1d10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42c2e1d8: PendingIntentRecord{42bb93b8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360107543 win=-1 tElapsed=315360107543 maxElapsed=551880107542 interval=0 standalone=false
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  374): ParamSet string: screen_state=off
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1215): start background delete task...
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
D/ContactMessageStore( 1215): size: 0 , 0
,D/ContactMessageStore( 1215): Background delete complete
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,D/NetworkPolicy(  906): updateScreenOn: false
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ACRA    ( 4190): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4190): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4190): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/wpa_supplicant( 4030): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(437f1d10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(429e5378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  906): killProcessQuiet, pid=3732
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(427f4338): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,I/ActivityManager(  906): Killing 3732:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] getTotalRam: 1873 Mb
,W/SystemClassLoaderAdder( 4190): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
D/PMS     (  906): acquireWL(4297d130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42c031c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): releaseWL(4297d130): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,V/DexLibLoader( 4190): Preparing secondary program dexes.
V/DexLibLoader( 4190): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4190): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4190): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4190): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4190): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4190): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4190): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4190): Dex already copied
D/OdexVerifier( 4190): Odex verification is skipped.
,V/DexLibLoader( 4190): Creating class loader
D/PMS     (  906): releaseWL(429e5378): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): acquireWL(4297a758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(437a5e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(437a5e78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4297a758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/DexLibLoader( 4190): Finished creating class loader
V/DexLibLoader( 4190): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4190): Dex already copied
D/OdexVerifier( 4190): Odex verification is skipped.
,V/DexLibLoader( 4190): Creating class loader
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4005): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4005): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4005): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4005): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4005): onScreenOff
,V/DexLibLoader( 4190): Finished creating class loader
V/DexLibLoader( 4190): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4190): Dex already copied
D/OdexVerifier( 4190): Odex verification is skipped.
,V/DexLibLoader( 4190): Creating class loader
,V/DexLibLoader( 4190): Finished creating class loader
V/DexLibLoader( 4190): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4190): Dex already copied
D/OdexVerifier( 4190): Odex verification is skipped.
,V/DexLibLoader( 4190): Creating class loader
,V/DexLibLoader( 4190): Finished creating class loader
,V/DexLibLoader( 4190): Verifying classes from secondary dexes.
I/ActivityManager(  906): Recipient 3732
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DexLibLoader( 4190): DexLibLoader.ensureDexLoaded took 129 ms
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(44384af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43976880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  906): releaseWL(44384af8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43b80d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c031c8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1107): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(43b80d50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1107): removeIcon slot=sync_active index=7 viewIndex=0
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{42659b08 u0 com.test.thalitest/.MainActivity t2}
,W/dalvikvm( 4190): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d222 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4190): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4190): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4190): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,E/BTIF_CORE( 3938): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3938): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3938): Wake lock released
,W/fb4a(:<default>):StaticBindingVerifier( 4190): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4190): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4190): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  906): Disable JIT of com.htc.bgp
,I/ActivityManager(  906): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4228 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  906): killProcessQuiet, pid=3752
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3752:com.htc.backup/1000 (adj 15): empty #17
,I/CalendarProvider2( 4228): Created com.android.providers.calendar.CalendarAlarmManager@41e66ca8(com.android.providers.calendar.HtcCalendarProvider@41e4f030)
,D/CalendarProvider2( 4228): wait start:true
,W/fb4a(:<default>):UserScope( 4190): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4190): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/CalendarProvider2( 4228): wait end:false
,W/fb4a(:<default>):UserScope( 4190): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Recipient 3752
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4246 uid=10055 gids={50055, 1023, 3003, 5012}
,E/dalvikvm( 4190): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4190): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4190): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4190): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4190): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4190): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4190): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4190): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4190): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4190): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4190): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;,
W/dalvikvm( 4190): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4190): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4190): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4190): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4190): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4190): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4190): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PMS     (  906): acquireWL(43effaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029}
,V/AlarmManager(  906): sending alarm PendingIntent{43a0bbc0: PendingIntentRecord{43a72f80 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
,D/ContactMessageStore( 1215): notify MmsSms
D/AccFlag ( 1215): sense_version=6.0
,D/AccFlag ( 1215): sku_id=99
D/PMS     (  906): releaseWL(43effaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1215): sku_id=99
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 9.924MB for 39954-byte allocation
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1215): sku_id=99
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 10.000MB for 79892-byte allocation
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1215): sku_id=99
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1215): sku_id=99
,D/PluginProvider( 4246): PluginProvider onCreate
,D/PluginProvider( 4246): current plugin count: 18
,D/HtcAppUPService( 4246): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 10.070MB for 84664-byte allocation
D/PMS     (  906): acquireWL(43b34938): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 10.089MB for 28144-byte allocation
,D/AutoSetting( 4246): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4262 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4246/10055)
,D/AutoSetting( 4246): service - onCreate()
,D/AutoSetting( 4246): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  906): request 4263cc30 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 4246): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4246): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 4246): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4246): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4246/10055)
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/MobileConnectivityChangeReceiver( 4262): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4262): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4262): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4262): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/PMS     (  906): acquireWL(4394b0e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4279 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e3cde8 u0 ReceiverList{42e526c0 4190 com.facebook.katana/10027/u0 remote:43aa0c10}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4262/10079)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{427c57d8 u0 ReceiverList{427c5d30 4190 com.facebook.katana/10027/u0 remote:42a310c0}},
,D/PMS     (  906): acquireWL(425ce840): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4394b0e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1964): Checkin interval check for package: unspecified last checkin: 1449748648350 min interval config: 0 actual interval: 2362717
I/CheckinService( 1964): Checking schedule, now: 1449751011075 next: 1449748678322
,I/CheckinService( 1964): active receiver: enabled
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1964, uid=10029, userID:0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,I/CheckinService( 1964): Preparing to send checkin request
,I/EventLogService( 1964): Accumulating logs since 1449749546572
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4279): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4279): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4279): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4279): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  906): acquireWL(42806bd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): releaseWL(42806bd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4279): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4190): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4190): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/WifiService(  906): New client listening to asynchronous messages
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4190): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4279/10151)
,V/WebViewChromiumFactoryProvider( 4279): Binding Chromium to main looper Looper (main, tid 1) {41e2ea90}
,I/LibraryLoader( 4279): Expected native library version number "",actual native library version number ""
,I/chromium( 4279): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4279): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4279): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43f24570): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  906): acquireWL(43b42cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  906): releaseWL(43f24570): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4279): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4279): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4279): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4279): Local Branch: 
I/Adreno-EGL( 4279): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4279): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4279):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4279): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4279/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4279/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3501/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3501/10160)
,D/Process (  906): killProcessQuiet, pid=3718
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3718:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1964/10029)
I/ActivityManager(  906): Recipient 3718
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1964, uid=10029, userID:0
V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 1964): SYNC; picasa accounts
,D/NetworkLogImpl( 1964): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,I/iu.Environment( 1964): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1964): num queued entries: 0
,I/iu.UploadsManager( 1964): num updated entries: 0
,I/iu.SyncManager( 1964): NEXT; no task
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/AlertReceiver( 3808): beginStartingService
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/PMS     (  906): acquireWL(43e23958): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3808 10013 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/libc    ( 1339): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1339): [NET] getaddrinfo-,err=8
D/libc    ( 1339): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1339): [NET] getaddrinfo-, 1
D/libc    ( 1339): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8cd9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
I/ActivityManager(  906): Delaying start of: ServiceRecord{437f17e8 u0 com.htc.calendar/.AlertService}
D/PMS     (  906): acquireWL(43b1d138): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4331 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 188
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1339): [NET] getaddrinfo_proxy-, success
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4343 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/libc    ( 1339): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1339): [NET] getaddrinfo-,err=8
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4358 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
W/WeatherUtility( 4331): can't get weather sync account
,W/WeatherRequest( 4331): request cur loc, but there is no sys cur
,W/Settings( 4331): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/dalvikvm( 4343): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4343): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4343): install
,I/MultiDex( 4343): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/libc    ( 1339): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1339): [NET] getaddrinfo-,err=8
,I/MultiDex( 4343): loading existing secondary dex files
,I/MultiDex( 4343): load found 3 secondary dex files
,D/PMS     (  906): acquireWL(42c9e808): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4358 10071 null
I/MultiDex( 4343): install done
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/GCM     ( 1339): GCM config loaded
,D/TodoTaskshortcut( 4358): update TASK shortcut>
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4375 uid=10090 gids={50090, 3003, 5012, 1028}
I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 2 10 17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,W/dalvikvm( 4343): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4343): VFY: unable to resolve instance field 36
,I/CalendarProvider2( 4228): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
W/ContentResolver( 4228): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/dalvikvm( 4343): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 4343): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Process (  906): killProcessQuiet, pid=3771
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3771:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3771
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4375): isHtcDevice = true
,D/Process (  906): killProcessQuiet, pid=3579
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3579:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3579
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WorldClock.Global( 4375): isHtcDevice = true
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4375): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4395 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4375): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4375): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,D/PMS     (  906): acquireWL(43ac0a90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4358 10071 null
,I/IntentController( 1107): receive(android.intent.action.ALARM_CHANGED,1,false)
D/PMS     (  906): acquireWL(4441f3d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4343): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  906): Delaying start of: ServiceRecord{44413250 u0 com.htc.task/.notification.NotifyService}
,D/PMS     (  906): releaseWL(42c9e808): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,D/TimeService( 4395): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751011828
,D/Process (  906): killProcessQuiet, pid=3528
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/PMS     (  906): releaseWL(43b1d138): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Killing 3528:com.android.vending/u0a74 (adj 15): empty #17
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Process (  906): killProcessQuiet, pid=3861
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1339/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
I/ActivityManager(  906): Killing 3861:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/PMS     (  906): releaseWL(4441f3d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/dalvikvm( 4343): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4343): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4343): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4343): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/PMS     (  906): acquireWL(43fcec38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1339/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/PMS     (  906): acquireWL(43fba7f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3861
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1339/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  906): releaseWL(43fba7f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,I/CheckinService( 1964): Checkin interval check for package: unspecified last checkin: 1449748648350 min interval config: 0 actual interval: 2363525
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
D/PMS     (  906): releaseWL(43fcec38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1964): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 1964): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  906): releaseWL(43b34938): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,D/AlertService( 3808): start to updateAlertNotification!
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,I/ActivityManager(  906): Recipient 3528
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  374): Level3 Library Nov 20 2013 18:09:31
,D/PMS     (  906): acquireWL(43b37a88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1964 10029 null
D/AlertService( 3808): No fired or scheduled alerts
D/HtcAlertUtils( 3808): -- cancelReminderNotification --
W/WVCdm   (  374): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
D/HtcAlertUtils( 3808): broadcastExistReminder!
,I/WVCdm   (  374): CdmEngine::OpenSession
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): acquireWL(43b35eb0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  374): CdmEngine::QueryKeyControlInfo
,W/AlertReceiver( 3808): stopSelfResult true
,I/WVCdm   (  374): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4343): Install completed successfully. count=14 extracted=0
D/PMS     (  906): releaseWL(43e23958): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
D/PMS     (  906): releaseWL(43b37a88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  906): releaseWL(43b35eb0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/TodoTaskNotifyService( 4358): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 4358): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4358): stopSelfResult true
D/PMS     (  906): releaseWL(43ac0a90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/WVCdm   (  374): PrepareKeyRequest: nonce=3159991212
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4416 uid=10041 gids={50041}
,D/Process (  906): killProcessQuiet, pid=4031
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 4246): receiver - intent: android.intent.action.USER_PRESENT
,I/ActivityManager(  906): Killing 4031:com.htc.widget.process2/u0a50 (adj 15): empty #17
I/WVCdm   (  374): CdmEngine::CloseSession
D/TetherSettings( 3302): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3302): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3302): Cust_ConnectToPC   : Modem_Link>false,
D/        ( 3302): Cust_ConnectToPC   : spcsc>false
D/        ( 3302): Cust_ConnectToPC   : IPT>true
D/        ( 3302): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3302): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 4246): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
E/SmartNS_Utility( 3302): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3302): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3302): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3302): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
I/SmartNS_PSService( 3302): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3302): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3302):  defaultType:0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4431 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4031
,W/ContextImpl( 4431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(42ed4b60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4431 1000 null
D/SmartSyncUtils( 4431): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(42ed4b60): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartSyncUtils( 4431): getMobilePolicyEnabled, result = true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=3964
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3964:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3964
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/SmartSyncUtils( 4431): isEpsOn(), nState = 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4431): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4431): isEpsOn(), nState = 0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=20 [10][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42743508
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42743508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
D/ProviderChangeReceiver( 3808): ---------------------------------------------------
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
D/ProviderChangeReceiver( 3808): ProviderChangeReceiver onReceive, start to update notification!
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42743508, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/AlertService( 3808): start to updateAlertNotification!
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42743508
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42904b20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42904b20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,I/WVCdm   (  374): CdmEngine::OpenSession
,I/WVCdm   (  374): CdmEngine::QueryKeyControlInfo
W/ContextImpl( 3822): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WVCdm   (  374): CdmEngine::GenerateKeyRequest
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/AlertService( 3808): No fired or scheduled alerts
,D/HtcAlertUtils( 3808): -- cancelReminderNotification --
,D/HtcAlertUtils( 3808): broadcastExistReminder!
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  906): Resuming delayed broadcast
,D/WearableService( 1198): callingUid 10029, callindPid: 1198
,D/LocationInitializer( 1964): Restart initialization of location
,E/MDM     ( 1198): [111] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
,D/WVCdm   (  374): PrepareKeyRequest: nonce=1203663026
,W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1198): location=null
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): acquireWL(43a12168): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43a12168): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4462 uid=10078 gids={50078}
,D/SMSBackup( 4462): Got a database change event
,I/WVCdm   (  374): CdmEngine::CloseSession
,W/Settings( 4343): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  906): acquireWL(429808c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4358 10071 null
D/PMS     (  906): acquireWL(428cf848): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4358 10071 null
E/TodoTaskNotifyService( 4358): java.lang.NullPointerException
W/System.err( 4358): java.lang.NullPointerException
W/System.err( 4358): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4358): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4358): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4358): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4358): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4358): stopSelfResult true
D/PMS     (  906): acquireWL(42812c30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4358 10071 null
D/PMS     (  906): releaseWL(429808c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  906): acquireWL(428cf848): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4358 10071 null
D/PMS     (  906): releaseWL(42812c30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(428cf848): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3983
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3983:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3983
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4118
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4118:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4118
,D/MediaRouterService(  906): Client com.google.android.music (pid 4118): Died!
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/Adreno-EGL( 4343): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4343): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4343): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4343): Local Branch: 
I/Adreno-EGL( 4343): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4343): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4343):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4343): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4343): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4343): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4343): Local Branch: 
I/Adreno-EGL( 4343): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4343): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4343):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4343/10029)
,I/Adreno-EGL( 4343): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4343): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4343): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4343): Local Branch: 
I/Adreno-EGL( 4343): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4343): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4343):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,D/libc    ( 1964): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1964): [NET] getaddrinfo-,err=8
,D/libc    ( 1964): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1964): [NET] getaddrinfo-, 1
,D/libc    ( 1964): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =46e1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1964): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1964): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1964): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/libc    ( 1964): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1964): [NET] getaddrinfo-,err=8
,D/libc    ( 1964): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1964): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4190): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4190): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=33 [9][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
I/CheckinTask( 1964): Sending checkin request (12158 bytes)
,I/jxcore-log( 3890): Test app app.js loaded
I/jxcore-log( 3890): 
,I/Choreographer( 3890): Skipped 543 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 3890): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3890): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e3c168 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 3890): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  906): releaseWL(42c6be88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4190): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4190/10027)
,D/PMS     (  906): releaseWL(43b42cc8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 1964): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1964): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1964/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=27 [18][5][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,I/CheckinRequestBuilder( 1964): Classify the device as Phone.
,I/CheckinTask( 1964): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1964): Checking schedule, now: 1449751014870 next: 1450273951862
,I/CheckinService( 1964): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1964, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,D/CheckinService( 1964): Recording last checkin time for package unspecified as 1449751014893
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,D/PMS     (  906): releaseWL(425ce840): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1964/10029)
,D/GCM     ( 1339): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Process (  906): killProcessQuiet, pid=3377
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3377:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3377
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4279): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4262
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=4190
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4262:com.google.android.setupwizard/u0a79 (adj 15): empty #17
I/ActivityManager(  906): Killing 4190:com.facebook.katana/u0a27 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 4262
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4190
,D/WifiService(  906): Client connection lost with reason: 4
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  906): acquireWL(43b34fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e32638: PendingIntentRecord{41e43d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118822, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b34fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4493 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1249): Deferring update until onResume
,D/Launcher( 1249): waitUntilResume // bindAppsUpdated
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  906):   Scheme: "mms"
,E/ExternalAccountType( 1322): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  906):   Scheme: "mmsto"
,D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4493): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 4493): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4493): MmsConfig.loadMmsSettings
,W/dalvikvm( 4493): VFY: unable to resolve instance field 36
,W/dalvikvm( 4493): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4516 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4493, uid=10111, userID:0
,W/Settings( 4493): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4493, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4493, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4493, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4493, uid=10111, userID:0
,D/MessageFrequencyProvider( 4516): onCreate
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4493, uid=10111, userID:0
,V/GetPrviateResource( 4516): GetPrviateResource
,D/MmsCustomizationProvider( 4516): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4516): GetPrviateResource
D/PMS     (  906): acquireWL(43a0af10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4493 10111 null
,I/ProviderInstaller( 4493): Installed default security provider GmsCore_OpenSSL
,D/MmsCustomizationProvider( 4516): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 4246): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4246): handle notify Blinkfeed plugin client changed
I/Babel   ( 4493): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4493): MmsConfig.loadFromDatabase
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2586): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/Babel   ( 4493): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4493): MmsConfig.loadFromResources
,D/Process (  906): killProcessQuiet, pid=4144
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  906): Killing 4144:com.android.chrome/u0a96 (adj 15): empty #17
E/Babel   ( 4493): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4493): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ActivityManager(  906): Recipient 4144
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43b8c530): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b8c530): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4516): sense_version=6.0
,D/BTAccessoryUtil( 4516): createReceiver
,D/BTAccessoryUtil( 4516): registerReceiver return intent = null
D/MessageCustFlag( 4516): sku_id=99
,W/SystemReader( 4516): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  906): releaseWL(43a0af10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  906): acquireWL(436250a0): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4516): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4516): networkCode: 
D/MessageCustFlag( 4516): sku_id=99
D/MmsConfig( 4516): SIE smsPri: null
,D/MmsConfig( 4516): networkCode: 
,D/HtcTelephonyCapability( 4516): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4516): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4516): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4516): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  906): releaseWL(436250a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(434e99a0): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(43a01a50): PARTIAL_WAKE_LOCK  AsyncService 0x1 3501 10160 null
,D/PMS     (  906): releaseWL(43a01a50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): releaseWL(434e99a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/dalvikvm-heap( 3501): Grow heap (frag case) to 13.530MB for 1821008-byte allocation
,D/AutoSetting( 4246): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4246): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4246): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  906): acquireWL(4441f3d0): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4441f3d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4545 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(4440cd18): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4440cd18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(443c1340): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(443c1340): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(443b7c20): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/PMS     (  906): releaseWL(443b7c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4545, uid=10074, userID:0
,D/PMS     (  906): acquireWL(443a8d28): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(443a8d28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4545): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4545/10074)
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41ec0cd0 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,I/IcingCorporaProvider( 2586): UpdateCorporaTask done [took 1081 ms] updated apps [took 1081 ms] 
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4545/10074)
,D/Finsky  ( 4545): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4545): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4545): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4545, uid=10074, userID:0
,D/Ads     ( 4545): Skipping gmscore version check
,D/Finsky  ( 4545): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4545): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4545): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4545): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4545): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1964): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageBroadcastService( 1964): Null package name or gms related package.  Ignoreing.
,D/PMS     (  906): acquireWL(44255698): PARTIAL_WAKE_LOCK  Icing 0x1 1964 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=4279
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4279:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/Icing   ( 1964): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  906): Recipient 4279
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  906): Unable to load service info ResolveInfo{437557f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/PhoneApp( 1215): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1215): -- N1 =0
,D/PhoneApp( 1215): -- N2 =0
,D/PhoneApp( 1215): -- N3 =0
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41ec0cd0 -
,D/Messaging( 4516): mNeedToUpdateDate2 start
,D/MmsConfig( 4516): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4516): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4516): 
D/MmsAsyncWorkHandler( 4516): HM tk = 20001
D/ReportIndicatorCache( 4516): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4516): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e38590
,I/Messaging( 4516): mccmnc> 
D/DraftCache( 4516): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4516): [DraftCache/1] refresh
,D/MmsConfig( 4516): networkCode: 
,D/Messaging( 4516): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsSmsV2Provider( 1215):  phoneType = -1
,D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1215):  phoneType = -1
,D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4516): sense_version=6.0
D/PhoneStorageUtil( 4516): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4516): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4516): createReceiver
,D/Jerry   ( 4516): start to preload cursor >>>>>>>
,D/TelephUtils( 1215): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
V/MmsProvider( 1215): Update uri=content://mms, match=0
,V/MmsProvider( 1215): selection=st=129 AND m_type!=134
,D/Messaging( 4516): Reset downloading state: 0
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsSystemEventReceiver( 4516): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1215):  phoneType = -1
,D/Messaging( 4516): mNeedToUpdateDate2: false
,D/Messaging( 4516): ViewCache CreatePreload
,D/Messaging( 4516): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4516): 1-Creating TransactionService
,D/Cust_MMSMS( 4516): _has_set_default_values_2=true
V/TransactionService( 4516): onStartCommand: 1
,D/MmsSystemEventReceiver( 4516): unRegisterForConnectionStateChanges
V/TransactionService( 4516): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4516): Loading previous transactions.
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1215): sku_id=99
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1215): device_type: 1
,D/DraftCache( 4516): [DraftCache/454] rebuildCache
D/TransactionService( 4516): Force set service start id to 1
V/TransactionService( 4516): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4516): unRegisterForConnectionStateChanges
,D/MsgPreferenceUtils( 4516): def_index: 0
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MsgPreferenceUtils( 4516): globalIndex = 1
,D/TransactionService( 4516): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4516): Destroying TransactionService
D/MmsSmsV2Provider( 1215):  phoneType = -1
,D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4516): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 4516): phone state: true
D/MsgPreferenceUtils( 4516): sd state: false
,D/MsgPreferenceUtils( 4516): vIndex = 0
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/Jerry   ( 1215): URI_DRAFT
,D/DraftCache( 4516): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4516): [DraftCache/454] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4516): 
D/MmsAsyncWorkHandler( 4516): HM tk = 20002
D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1215):  phoneType = -1
,D/MmsSmsV2Provider( 1215): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4516): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1215): sku_id=99
,D/TelephUtils( 1215): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1215): sku_id=99
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1198): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(43a2a288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43a2a288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
,D/PMS     (  906): acquireWL(428bd088): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42999638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42999638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428bd088): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43dd7e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43dd7e58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/Icing   ( 1964): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1964): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(44255698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(436245d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{43e508d0: PendingIntentRecord{426f7a78 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123951, Int=0
,D/PMS     (  906): releaseWL(436245d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42778090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=28 [7][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42e33a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e33a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42778090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42aa95a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,D/PMS     (  906): releaseWL(42aa95a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4345ab70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43b05a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42887fd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1198): Vacuum at: now=1449751025332 tag=VacuumService
D/PMS     (  906): releaseWL(4345ab70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b05a70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c82a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,D/PMS     (  906): releaseWL(42c82a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42887fd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(44447bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(44447bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(443cd120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,D/PMS     (  906): releaseWL(443cd120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43bad9c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43bad9c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4349f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42f4e908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4349f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f4e908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(443f7678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024406
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024528
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024607
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024612
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024618
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026049
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026064
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028615
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360107543
,D/PMS     (  906): releaseWL(443f7678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{443b10c8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4493): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4331
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4331:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4331
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(43ebf9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ebf9e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43624f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41f46cb0: PendingIntentRecord{428126f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=136861, Int=0
,D/PMS     (  906): acquireWL(42c91b08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(43624f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(443290c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42c91b08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(443290c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(443074f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4213f968: PendingIntentRecord{42f90180 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137667, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1339/10029)
,D/PMS     (  906): releaseWL(443074f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4246): service - mHandler: update timezone
,D/AutoSetting( 4228): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4228): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4228): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4228): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4228): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4228): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4228): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4228): service - mHandler: update timezone
,D/AutoSetting( 4228): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4228): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4228): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4228): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1107): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e5bb08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.htclocationservice 3 18 5 11
,D/AutoSetting( 4246): service - handleMessage() stop self
,D/AutoSetting( 4246): service - handleMessage() quit looper
,D/AutoSetting( 4246): service - onDestroy() END
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(434281d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4268c780: PendingIntentRecord{426d8520 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141912, Int=0
D/PMS     (  906): acquireWL(42cf0280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(434281d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1b6f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 36
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(42cf0280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(43976a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43976a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42998e50 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(443aac50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f46cb0: PendingIntentRecord{428126f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=166879, Int=0
,D/PMS     (  906): acquireWL(429db778): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(443aac50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c912c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=9 [43][4][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4030): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43fd4a48): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 906 1000 WorkSource{10029}
,E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4030): nl80211: survey data missing!
E/wpa_supplicant( 4030): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4030): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(429db778): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42c912c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43f8ab10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43f8ab10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1964): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4298d9f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24972, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  906): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 167252, reason: UserStart
D/PMS     (  906): releaseWL(43fd4a48): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  906): releaseWL(4298d9f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(443c06f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
,D/PMS     (  906): releaseWL(443c06f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1322): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4228): service - handleMessage() stop self
,D/AutoSetting( 4228): service - onDestroy() END
,D/AutoSetting( 4228): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4375
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4375:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4375
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1215): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(43e9bb78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e32638: PendingIntentRecord{41e43d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178822, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43e9bb78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42964820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42964820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42985a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f46cb0: PendingIntentRecord{428126f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=196939, Int=0
,D/PMS     (  906): acquireWL(4299d2e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(42985a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fd4008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4299d2e8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43fd4008): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ClearcutLoggerApiImpl( 1339): disconnect managed GoogleApiClient
,D/PMS     (  906): acquireWL(43af25b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43af25b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(434e7918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e32638: PendingIntentRecord{41e43d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238823, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(434e7918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43fa0528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fa0528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43aaa220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f46cb0: PendingIntentRecord{428126f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=274827, Int=0
,D/PMS     (  906): acquireWL(43fbb078): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43aaa220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42d58740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43fbb078): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42d58740): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(441afc48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e32638: PendingIntentRecord{41e43d68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=298822, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441afc48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4349e9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4349e9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1

```
