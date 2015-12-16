#### Test 50650278dbf8a2a_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Recipient 3362
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3362): Died!
,--------- beginning of /dev/log/main
E/cutils-trace( 3889): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3889): ====startRecUseTime====
D/htc.customization.log.level( 3889):  is 
W/CustomizationLogLevel( 3889): Level value is invalid, use default level 2
D/CustomizationManager( 3889):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3889): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3889): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3889): Parsing tag category name = system
I/CustomizationCIDLoader( 3889): Parsing tag category name = application
I/CustomizationCIDLoader( 3889): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3889): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3889): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3889): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3889): Parsing tag category name = Settings
D/CustomizationManager( 3889):  Read CID file spent 0.106 (s)
D/CustomizationManager( 3889):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 3889): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3889): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3889): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3889): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3889
D/PMS     (  905): acquireHCC(425f0d58): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(434bea48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x68131f70 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1113259896
D/PMS     (  905): acquireWL(440a5f40): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c3a148
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3900 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 3900): Copying FileAsset 0x5c859428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1249): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3900): Binding Chromium to main looper Looper (main, tid 1) {41add018}
I/LibraryLoader( 3900): Expected native library version number "",actual native library version number ""
I/chromium( 3900): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3900): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
D/PMS     (  905): acquireWL(43103d58): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(4352a148): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(43103d58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4353dbd0:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3900): 1101999984: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3900): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3900): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3900): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3900): Local Branch: 
I/Adreno-EGL( 3900): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3900): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3900):                  aa63bbd948f41d15fc72f585e
W/chromium( 3900): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3900): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3900): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3900): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3900): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3900): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3900): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3900): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3900): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3900): CordovaWebView is running on device made by: HTC
,W/AwContents( 3900): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +277ms
W/ResourceType( 3900): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3900): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b244f8, mServedView=org.apache.cordova.engine.SystemWebView{41aea288 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3900): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Disable input method client, pid=1249
I/InputMethodManagerService(  905): Enable input method client, pid=3900
D/PMS     (  905): releaseWL(440a5f40): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3900): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3900): JniHelper::setJavaVM(0x415b5048), pthread_self() = 1663254992
D/JX-Cordova( 3900): jxcore cordova android initializing
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 11.562MB for 96598-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 11.644MB for 144892-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 11.762MB for 217334-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 11.939MB for 325996-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 12.196MB for 488990-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 13.208MB for 1100216-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 14.116MB for 1650320-byte allocation
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 15.460MB for 2475476-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(425f0d58): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(434bea48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3900): Grow heap (frag case) to 17.498MB for 3713210-byte allocation
,W/jxcore-log( 3900): Initializing JXcore engine
,W/jxcore-log( 3900): JXcore engine is ready
,W/jxcore-log( 3900): Starting JXcore engine
,W/jxcore-log( 3900): Platform android
W/jxcore-log( 3900): 
,W/jxcore-log( 3900): Process ARCH arm
W/jxcore-log( 3900): 
,V/LightsService(  905): setLight #0: color=#25
,V/LightsService(  905): setLight #0: color=#21
,V/LightsService(  905): setLight #0: color=#1b
,V/LightsService(  905): setLight #0: color=#14
,I/SensorManager(  905): mEventCount = 1050
,D/PMS     (  905): releaseWL(4352a148): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3900): JXcore Cordova bridge is ready!
I/jxcore-log( 3900): 
,W/jxcore-log( 3900): JXcore engine is started
,I/chromium( 3900): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3900): Toggling radios to true
I/jxcore-log( 3900): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): checking for enable restriction...
,D/BluetoothManagerService(  905): checkBTEasState, ret=true
I/BluetoothManagerService(  905): isBluetoothRestricted(): false
,D/BluetoothManagerService(  905): enable(): region ID = 6
,D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1326
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3900): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1281
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
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=3900, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiManager( 3900): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3900): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/jxcore-log( 3900): Radios toggled
I/jxcore-log( 3900): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3900): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3900): 
I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3947 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/PMS     (  905): acquireWL(43c66ee8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
I/jxcore-log( 3900): Perf Test app loaded loaded
I/jxcore-log( 3900): 
I/Choreographer( 3900): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3900): check test folder
I/jxcore-log( 3900): 
,I/jxcore-log( 3900): found test : ./testFindPeers.js
I/jxcore-log( 3900): 
,I/jxcore-log( 3900): found test : ./testSendData.js
I/jxcore-log( 3900): 
,D/AdapterServiceConfig( 3947): Adding HeadsetService
D/AdapterServiceConfig( 3947): Adding A2dpService
D/AdapterServiceConfig( 3947): Adding HidService
D/AdapterServiceConfig( 3947): Adding HealthService
D/AdapterServiceConfig( 3947): Adding PanService
,D/AdapterServiceConfig( 3947): Adding GattService
,W/linker  ( 3947): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3947): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424e1ce0:true
,D/BluetoothAdapterState( 3947): make
,I/BluetoothAdapterState( 3947): Entering OffState
,I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3947): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapter( 1221): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41da47b8
,D/BluetoothAdapter( 1221): onBluetoothServiceUp done
D/BluetoothAdapter( 1108): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ec1f40
D/BluetoothAdapter( 1108): onBluetoothServiceUp done
D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@435fe018
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
D/BluetoothAdapter( 1198): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41dd44e0
,D/BluetoothAdapter( 1198): onBluetoothServiceUp done
D/BluetoothAdapter( 1233): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c0ffe8
,D/BluetoothAdapter( 1233): onBluetoothServiceUp done
D/BluetoothAdapter( 3947): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41af5f30
,D/BluetoothAdapter( 3947): onBluetoothServiceUp done
D/BluetoothAdapter( 3900): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42629be8
D/BluetoothAdapter( 3900): onBluetoothServiceUp done
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 3947): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3947): Setting state to 11
,I/BluetoothAdapterState( 3947): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3947): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 3947): make
,I/BluetoothBondStateMachine( 3947): StableState(): Entering Off State
D/PMS     (  905): acquireWL(433ea038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
,D/HeadsetService( 3947): Received start request. Starting profile...
D/HeadsetStateMachine( 3947): Version 1.6
,D/HeadsetStateMachine( 3947): make
D/PMS     (  905): releaseWL(433ea038): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3973 uid=10040 gids={50040, 3002, 3001}
,I/HeadsetStateMachine( 3947): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3947): Received start request. Starting profile...
,I/BluetoothAdapterState( 3947): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,V/Avrcp   ( 3947): make
,D/Avrcp   ( 3947): fillIntentFilter()
,I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/HtcBtWidget_BTWidgetProvider( 3973): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3973): updateWidget(context) for widget: 
,I/chromium( 3900): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  905): interfaceAdded wlan0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceAdded p2p0
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): releaseWL(43c66ee8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/A2dpStateMachine( 3947): make
,D/Process (  905): killProcessQuiet, pid=3681
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3681:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/A2dpStateMachine( 3947): Enter Disconnected: -2
,D/HidService( 3947): Received start request. Starting profile...
,D/HealthService( 3947): Received start request. Starting profile...
,D/PanService( 3947): Received start request. Starting profile...
D/BluetoothTethering(  905): supplyMessenger
,D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
D/PanService( 3947): HTC_CUSTOMIZATION_MHS_ENABLE = false
I/ActivityManager(  905): Recipient 3681
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
D/BtGatt.DebugUtils( 3947): handleDebugAction() action=null
D/BtGatt.GattService( 3947): Received start request. Starting profile...
D/BtGatt.GattService( 3947): start()
V/BluetoothPbapService( 3947): Pbap Service onCreate
V/BluetoothPbapService( 3947): Starting PBAP service
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 11
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 11
D/HeadsetPhoneState( 3947): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
E/BluetoothMasService( 3947): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3947): Add permission for SmsProvider.
V/BluetoothMasService( 3947): Starting MAS instances
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 11
I/MailMessageReceiver( 3947): reg:com.android.bluetooth.btservice.AdapterApp@41ae9498 with com.htc.util.mail.MailMessageReceiver@41b2ad30
I/MailManager( 3947): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b2ad30
V/EmailUtils( 3947): Manager Instance is not NULL
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3992 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/wpa_supplicant( 4006): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4006): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4006): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4006): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4006): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4006): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4006): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4006): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4006): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4006): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4006): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4006): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4006): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4006): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4006): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4006): update_config=1
D/wpa_supplicant( 4006): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4006): device_name='Android_1950'
D/wpa_supplicant( 4006): manufacturer='HTC'
D/wpa_supplicant( 4006): model_name='HTC_PHONE'
D/wpa_supplicant( 4006): model_number='1234'
D/wpa_supplicant( 4006): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4006): p2p_oper_reg_class=126
D/wpa_supplicant( 4006): p2p_oper_channel=36
D/wpa_supplicant( 4006): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4006): persistent_reconnect=1
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4006): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4006): nl80211: RFKILL status not available
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4006): nl80211: Using driver-based roaming
D/wpa_supplicant( 4006): nl80211: TDLS supported
D/wpa_supplicant( 4006): nl80211: TDLS external setup
D/wpa_supplicant( 4006): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4006): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4006): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4006): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4006): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4006): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4006): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4006): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8753758
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Re,gister frame type=0xd0 nl_handle=0xb8753758
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4006): htc_wext_command_init +
E/wpa_supplicant( 4006): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4006): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4006): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4006): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4006): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4006): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4006): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/EmailUtils( 3947): ============NULL aList========
V/EmailUtils( 3947): <-getEmailAccountIdList
,V/BluetoothMasService( 3947): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 11
V/BluetoothMasService( 3947): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3947): Manager Instance is not NULL
,D/EmailUtils( 3947): ============NULL aList========
,V/EmailUtils( 3947): <-getEmailAccountIdList
,D/BluetoothAdapterService( 3947): Profile still not running:com.android.bluetooth.hdp.HealthService
V/BluetoothSapService( 3947): Sap Service onCreate
,V/BluetoothSapService( 3947): initBinder
V/BluetoothSapService( 3947): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41b303c0
,V/BluetoothSapReceiver( 3947): BluetoothSapReceiver init
,D/BluetoothSapService( 3947): setSapService()
V/BluetoothSapService( 3947): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3947): state: 12
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 11
D/BluetoothAdapterService( 3947): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3947): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3947): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3947): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 3947): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3947): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  905): killProcessQuiet, pid=3344
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 3344:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/BluetoothMasReceiver( 3947): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 4012): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  905): Recipient 3344
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4014 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4030): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/qcom-bluetooth( 4031): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/qcom-bluetooth( 4033): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4034 uid=10050 gids={50050}
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4014): Received state change = 11
I/qcom-bluetooth( 4039): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4046): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4048): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,D/WifiService(  905): New client listening to asynchronous messages
,I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/Process (  905): killProcessQuiet, pid=3619
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 3619:com.google.android.talk/u0a111 (adj 15): empty #17
D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 4034): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4034): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3716
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 3716:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3716
,I/wpa_supplicant( 4006): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4006):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4006):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4006):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): nl80211: Flush PMKIDs
E/wpa_supplicant( 4006): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4006): State: DISCONNECTED -> INACTIVE
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3619
,D/wpa_supplicant( 4006): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4006): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4006): WPS: Set UUID for interface p2p0
,I/qcom-bluetooth( 4052): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4053): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 4006): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4006): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4006): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): Using existing control interface directory.
D/wpa_supplicant( 4006): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4006): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4006): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4006): P2P: Own listen channel: 1
D/wpa_supplicant( 4006): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4006): P2P: Add operating class 81
I/wpa_supplicant( 4006): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4006): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4006): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4006): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4006): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4006): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4006): disable_scan_offload=1
D/wpa_supplicant( 4006): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4006): update_config=1
D/wpa_supplicant( 4006): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4006): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4006): manufacturer='HTC'
D/wpa_supplicant( 4006): model_name='HTC Desire 820'
D/wpa_supplicant( 4006): model_number='HTC Desire 820'
D/wpa_supplicant( 4006): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4006): persistent_reconnect=1
D/wpa_supplicant( 4006): p2p_disabled=1
D/wpa_supplicant( 4006): hs20=1
D/wpa_supplicant( 4006): interworking=1
D/wpa_supplicant( 4006): Line: 18 - start of a new network block
D/wpa_supplicant( 4006): key_mgmt: 0x2
D/wpa_supplicant( 4006): priority=1 (0x1)
,D/wpa_supplicant( 4006): signinfail=0 (0x0)
,I/bt-btu  ( 3947): btu_task pending for preload complete event
,D/wpa_supplicant( 4006): Priority group 1
D/wpa_supplicant( 4006):    id=0 ssid='NG700'
I/wpa_supplicant( 4006): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4006): nl80211: RFKILL status not available
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4006): nl80211: Using driver-based roaming
D/wpa_supplicant( 4006): nl80211: TDLS supported
D/wpa_supplicant( 4006): nl80211: TDLS external setup
D/wpa_supplicant( 4006): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4006): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4006): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4006): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4006): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4006): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4006): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4006): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8763718
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4006): htc_wext_command_init +
I/wpa_supplicant( 4006): htc_wext_command_init -
I/wpa_supplicant( 4006): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4006): Don't set 00 to countryID.conf
D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4006): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4006): nl80211: Use separate P2P group interface
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4006): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4006): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4006): nl80211: 5170-5250 @ 80 MHz,
D/wpa_supplicant( 4006): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4006): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged wlan0, false,
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4006): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4006):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT ,
D/wpa_supplicant( 4006):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4006):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4006): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4006): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4006): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4006): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4006): TDLS: Driver uses external link setup
D/wpa_supplicant( 4006): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4006): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4006): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4006): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4006): Using existing control interface directory.
,I/wpa_supplicant( 4006): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4006): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4006): Auto country group 1: ch36
I/wpa_supplicant( 4006): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4006): random: Got 18/20 bytes from /dev/random
I/wpa_supplicant( 4006): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4006): nl80211: Event message available
D/wpa_supplicant( 4006): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4006): nl80211: Regulatory domain change
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  905): Regulatory Country Code:DE
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
D/wpa_supplicant( 4006): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4006): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4006): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4006): P2P: Add operating class 81
D/wpa_supplicant( 4006): P2P: Add operating class 115
D/wpa_supplicant( 4006): P2P: Add operating class 116
D/wpa_supplicant( 4006): P2P: Add operating class 117
D/wpa_supplicant( 4006): P2P: Update channel list
D/wpa_supplicant( 4006): p2p0: Updating hw mode
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 95
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4006): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4006): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4006): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 5250-5350 @ 80 MHz,
D/wpa_supplicant( 4006): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4006): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 31,
D/wpa_supplicant( 4006): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4006): random: Got 2/2 bytes from /dev/random
D/wpa_supplicant( 4006): Get randomness: len=20 entropy=0,
D/wpa_supplicant( 4006): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4006): set wifi ON
,D/WifiNative-wlan0(  905):    returned true
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
I/wpa_supplicant( 4006): wpa_supplicant_scan enter
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
I/wpa_supplicant( 4006): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4006): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4006): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4006): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4006): nl80211: Event message available
D/wpa_supplicant( 4006): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  905): Loading config and enabling all networks
,D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): list_network_info: ret=0x1, pos=0xb8766117 buf=0xb87660e8
,I/wpa_supplicant( 4006): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4006): 0	NG700	any	
D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1",
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_psk'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4006): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert",
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='limited',
D/HtcWiFiWidget_WiFiWidgetProvider( 4034): onWiFiStateChanged() for widget: 
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/HtcWiFiWidget_WiFiWidgetProvider( 4034): updateWidget(context) for widget: 
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
,D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4006): CTRL_IFACE: Failed to get network variable 'private_key'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4006): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4006): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'manufacturer'='HTC'
,D/wpa_supplicant( 4006): manufacturer='HTC'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4006): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4006): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4006): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4006): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): SET_SCREEN_ON:On
I/wpa_supplicant( 4006): htc_wext_set_keepalive +
I/wpa_supplicant( 4006): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4006): getPrivFuncNum +	
I/wpa_supplicant( 4006): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4006): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): SETBAND: 0
D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4006): P2P: Add operating class 81
D/wpa_supplicant( 4006): P2P: Add operating class 115
D/wpa_supplicant( 4006): P2P: Add operating class 116
D/wpa_supplicant( 4006): P2P: Add operating class 117
D/wpa_supplicant( 4006): P2P: Update channel list
I/wpa_supplicant( 4006): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4006): set country (DE) from /data/misc/wifi/countryID.conf
,I/wpa_supplicant( 4006): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4006): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4006): p2p_oper_reg_class=126
D/wpa_supplicant( 4006): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4006): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4006): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4006): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4006): p2p_oper_channel=36
E/wpa_supplicant( 4006): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4006): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4006): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
,D/wpa_supplicant( 4006): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4006): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4006): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
,D/WifiP2pService(  905): P2pEnabledState
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4006): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4006): persistent_reconnect=1
I/wpa_supplicant( 4006): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  905):    returned true
,D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_1950
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4006): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4006): device_name='Android_1950'
I/wpa_supplicant( 4006): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_1950
,W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4006): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4006): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4006): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4006): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4006): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,I/wpa_supplicant( 4006): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
,D/wpa_supplicant( 4006): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4006): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4006): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4006): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4006): Single channel concurrency preference: sta
I/wpa_supplicant( 4006): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4006): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4006): P2P: Stopping find
,D/wpa_supplicant( 4006): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4006): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4006): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4006): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4006): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
,W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4006): list_network_info: ret=0x22, pos=0xb876610a buf=0xb87660e8
I/wpa_supplicant( 4006): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4006): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
,D/WifiNative-p2p0(  905):    returned false
D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4006): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4006): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4006): WFD: Update WFD IE
I/wpa_supplicant( 4006): WFD: Update WFD IE - DONE
,I/wpa_supplicant( 4006): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4006): WFD: Set subelement 0
D/wpa_supplicant( 4006): WFD: Update WFD IE
,I/wpa_supplicant( 4006): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4006): Recv Cmd 2: WFD_SUBELEM_SET 0
,D/WifiNative-p2p0(  905):    returned true
,D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  905):  deviceAddress: b6:ce:f6:ad:a4:6b
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
D/WifiP2pService(  905): InactiveState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
,D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  905): Successfully set WFD info.
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  905): convertEffect before=902
,D/HtcEffectManager(  905): convertEffect after=902
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  905):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  905):  primary type: 10-0050F204-5
D/WifiDisplayController(  905):  secondary type: null
D/WifiDisplayController(  905):  wps: 0
D/WifiDisplayController(  905):  grpcapab: 0
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
,D/wpa_supplicant( 4006): EAPOL: disable timer tick
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
,I/bt-btu  ( 3947): btu_task received preload complete event
D/bt-btm  ( 3947): btm_acl_device_down
D/bt-btm  ( 3947): btm_acl_reset_paging
,D/bt-btm  ( 3947): btm_acl_set_discing
,I/bt-btm  ( 3947): btm_reset_complete
,I/bt-btm  ( 3947): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3947): Start reading local supported commands
D/wpa_supplicant( 4006): nl80211: Event message available
D/wpa_supplicant( 4006): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4006): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4006): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 4006): nl80211: Survey data missing
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4006): Sorted scan results
I/wpa_supplicant( 4006): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 4006): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4006): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 4006): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 4006): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 4006): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4006): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4006): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4006): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4006): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4006): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4006): wpa_supplicant_pick_network+
I/wpa_supplicant( 4006): Selecting BSS from priority group 1
I/wpa_supplicant( 4006): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4006): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4006): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4006): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4006): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4006):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4006):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 4006): Start print parameters
I/wpa_supplicant( 4006): wpa_s->wpa_state is 3
I/wpa_supplicant( 4006): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4006): isConcurrentMode() is 0
I/wpa_supplicant( 4006): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4006): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4006): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4006): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4006): wpa_s->reassociate is 0
I/wpa_supplicant( 4006): wpa_s->is_screen_on 1
I/wpa_supplicant( 4006): wpa_s->ifname wlan0
I/wpa_supplicant( 4006): End print parameters
I/wpa_supplicant( 4006): selected network = 2
D/wpa_supplicant( 4006): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87644e8  current_ssid=0x0
D/wpa_supplicant( 4006): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4006): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4006): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4006): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4006): check if in concurrent case
,I/wpa_supplicant( 4006): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/bt-btm  ( 3947): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3947): BTM reads next extended features page (1)
D/wpa_supplicant( 4006): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4006): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4006): wpa_supplicant_associate, 1795
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
D/wpa_supplicant( 4006): RSN: PMKSA cache search - network_ctx=0xb87644e8 try_opportunistic=0
D/wpa_supplicant( 4006): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4006): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4006): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4006): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4006): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4006): nl80211: Unsubscribe mgmt frames handle 0xb8763718 (mode change)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 4006): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8763718
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Register frame type=0xd0 nl_handle=0xb8763718
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4006): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4006):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4006):   * freq=2412
D/wpa_supplicant( 4006):   * Auth Type 0
D/wpa_supplicant( 4006):   * WPA Versions 0x2
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4006): nl80211: Connect request send successfully
D/wpa_supplicant( 4006): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4006),: EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/bt-btm  ( 3947): BTM reads next extended features page (2)
D/bt-btm  ( 3947): BTM reached last extended features page (2)
,D/bt-btm  ( 3947): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4006): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4006): reply (489) for get BSS: id=0
I/wpa_supplicant( 4006): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4006): freq=5220
I/wpa_supplicant( 4006): level=-49
I/wpa_supplicant( 4006): tsf=0000000104120703
I/wpa_supplicant( 4006): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4006): ssid=NG7005g
I/wpa_supplicant( 4006): ====
I/wpa_supplicant( 4006): id=1
I/wpa_supplicant( 4006): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4006): freq=2412
I/wpa_supplicant( 4006): level=-50
I/wpa_supplicant( 4006): tsf=0000000104120727
I/wpa_supplicant( 4006): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4006): ssid=01ABC
I/wpa_supplicant( 4006): ====
I/wpa_supplicant( 4006): id=2
I/wpa_supplicant( 4006): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4006): freq=2412
I/wpa_supplicant( 4006): level=-50
I/wpa_supplicant( 4006): tsf=0000000104120737
I/wpa_supplicant( 4006): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4006): ssid=NG700
I/wpa_supplicant( 4006): ====
I/wpa_supplicant( 4006): id=3
I/wpa_supplicant( 4006): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4006): freq=2427
I/wpa_supplicant( 4006): level=-79
I/wpa_supplicant( 4006): tsf=0000000104120748
I/wpa_supplicant( 4006): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4006): ssid=Gonzos
I/wpa_supplicant( 4006): ####
,D/bt-btm  ( 3947): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/bt-btm  ( 3947): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3947): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3947): btm_read_ble_wl_size 
D/bt-btm  ( 3947): btm_read_white_list_size_complete 
,D/bt-btm  ( 3947): btm_get_ble_buffer_size 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 104120703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 104120727, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 104120737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 104120748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 4 to mScanResults
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/bt-btm  ( 3947): btm_read_ble_buf_size_complete 
D/WifiManager( 1198): getScanResults enter 
D/bt-btm  ( 3947): btm_read_ble_local_supported_features 
D/WifiStateMachine(  905): == begin of scan result ==
D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == (4) end of scan result ==
D/bt-btm  ( 3947): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3947): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3947): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3947): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3947): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3947): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3947): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3947): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3947): BTM_SetInquiryMode
I/bt-btm  ( 3947): BTM_SetPageScanType
I/bt-btm  ( 3947): BTM_SetInquiryScanType
D/bt-btm  ( 3947): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3947): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3947): BTM_BleLoadLocalKeys
D/bt-btm  ( 3947): BTM_BleLoadLocalKeys
I/bt-btm  ( 3947): BTM_Sec: application registered
E/bt-btm  ( 3947): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f96941 
I/bt-btm  ( 3947): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3947): SMP_Register state=0
E/bt-btm  ( 3947): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f96941 
I/bt-btm  ( 3947): BTM_Sec: application registered
D/bt-btm  ( 3947): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3947): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3947): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3947): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3947): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3947): BTM_RegBusyLevelNotif
I/bt-att  ( 3947): GATT_Register
D/bt-att  ( 3947): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3947): allocated gatt_if=3
I/bt-att  ( 3947): GATT_StartIf gatt_if=3
D/bt-att  ( 3947): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3947): gatt_find_the_connected_bda found=0 found_idx=7,
E/bt-btif ( 3947): Calling BTA_HhEnable
E/bt-btif ( 3947): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3947): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:2 len:6
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3947): BTM_AllocateSCN
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3947): BTM_AllocateSCN
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3947):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3947):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3947): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3947): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
D/bt-avp  ( 3947): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3947): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 394,7): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3947):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 08:ec:a9:50:75:41
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: f8:cf:c5:d9:e5:61
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3947): BTM_GetHCIConnHandle
I/bt-btm  ( 3947): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3947): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3947): GATT_Register
D/bt-att  ( 3947): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3947): allocated gatt_if=4
I/bt-att  ( 3947): GATT_StartIf gatt_if=4
D/bt-att  ( 3947): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3947): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3947): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3947): Scan Mode:20
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3947): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:8 len:60
D/BluetoothAdapter( 3947): getBluetoothService(): entry
D/BluetoothAdapter( 3947): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3947): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b39b98
D/BluetoothDevice( 3947): getService : Register callback
D/BluetoothAdapterProperties( 3947): Adding bonded device:7C:F9:0E:51:18:22
D/BluetoothAdapterProperties( 3947): Adding bonded device:80:01:84:8A:B3:68
D/BluetoothAdapterProperties( 3947): Adding bonded device:14:B4:84:21:3B:49
D/BluetoothAdapterProperties( 3947): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 3947): Adding bonded device:08:EC:A9:50:75:41
D/BluetoothAdapterProperties( 3947): Adding bonded device:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3947): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3947): Adding bonded device:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 3947): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3947): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3947): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothRemoteDevices( 3947): Remote class is:5898764
I/bt-btif ( 3947): BTA_JvEnable
I/bt-btm  ( 3947): BTM_ReadConnectability
I/bt-btm  ( 3947): BTM_ReadDiscoverability
I/bt-btm  ( 3947): BTM_SetDiscoverability
I/bt-btm  ( 3947): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3947): br_edr_supported=0x2
I/bt-btm  ( 3947): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3947): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3947): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3947): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3947): BTM_SetConnectability
I/bt-btm  ( 3947): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3947): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3947): BTM_SetDiscoverability
I/bt-btm  ( 3947): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3947): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3947): br_edr_supported=0x0
I/bt-btm  ( 3947): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3947): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3947): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3947): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3947): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3947): BTM_SetConnectability
I/bt-btm  ( 3947): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3947): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3947): bta_pan_co_init
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3947): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3947):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3947):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3947): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3947):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3947): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3947):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3947): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3947): ScanMode =  20
D/BluetoothAdapterProperties( 3947): State =  11
I/bt-btm  ( 3947): BTM_SetDiscoverability
I/bt-btm  ( 3947): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3947): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3947): br_edr_supported=0x0
I/bt-btm  ( 3947): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3947): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3947): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3947): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3947): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3947): BTM_SetConnectability
I/bt-btm  ( 3947): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3947): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3947): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3947): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3947): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3947): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3947): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3947): Scan Mode:21
I/bt-btif ( 3947): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3947): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3947): Discoverable Timeout:120
D/BluetoothAdapterProperties( 3947): Setting state to 12
I/BluetoothAdapterState( 3947): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3947): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3947): Entering On State
E/bt_mct  ( 3947): hci lib postload completed
D/BluetoothAdapterService(1102001088)( 3947): Get Bonded Devices being called
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4006): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/BluetoothAdapterProperties( 3947): getBondedDevices: length=10
D/wpa_supplicant( 4006): nl80211: Event message available
D/wpa_supplicant( 4006): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4006): nl80211: Connect event
D/wpa_supplicant( 4006): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4006): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4006): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4006): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4006): Add randomness: count=6 entropy=4
I/wpa_supplicant( 4006): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4006): TDLS: Remove peers on association
D/wpa_supplicant( 4006): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/BluetoothHeadset( 1108): onBluetoothStateChange: up=true
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4006): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4006): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4006): htc_wext_set_keepalive +
I/wpa_supplicant( 4006): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4006): getPrivFuncNum +	
I/wpa_supplicant( 4006): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4006): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4006): Get randomness: len=32 entropy=5
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/BluetoothHeadset( 1221): Proxy object connected
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/BluetoothHeadset( 1108): Proxy object connected
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
I/QuickSettingMiniLite( 1108): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41df55e0
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 4006): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87639f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4006):    addr=c0:ff:d4:d3:aa:48
D/BluetoothHeadset( 1221): Proxy object connected
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/BluetoothPhoneService( 1221): BluetoothHeadset onServiceConnected
D/WifiStateMachine(  905): This record is existed, only update it...
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4006): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4006): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f3ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4006):    broadcast key
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4006): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4006): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4006): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4006): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4006): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 4006): wlan0: Connect to SSID: NG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 4006): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4006): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4006): set send_ind_to_ndc = 0
I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4006): EAPOL: External notification - portValid=1
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/wpa_supplicant( 4006): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4006): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4006): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4006): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4006): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4006): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4006): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4006): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4006): EAPOL authentication completed successfully
I/wpa_supplicant( 4006): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 79
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4006): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4006): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4006): nl80211: if_removed already cleared - ignore event
D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/BluetoothAdapter( 1221): 1103182672: getState(). Returning 12
D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/BluetoothPan(  905): BluetoothPAN Proxy object connected
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
D/BluetoothHeadset(  905): Proxy object connected
D/BluetoothAdapter(  905): 1111858264: getState(). Returning 12
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothAdapterService(1102001088)( 3947): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3947): getBondedDevices: length=10
D/BluetoothA2dp(  905): Proxy object connected
D/BluetoothAdapter(  905): 1111858264: getState(). Returning 12
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/WifiApDatabaseHandler(  905): updateConnectedAP...
V/BluetoothPbapReceiver( 3947): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3947): ***********state = 12
D/BluetoothMasReceiver( 3947): Bluetooth STATE CHANGED to 12
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/PMS     (  905): acquireWL(4352f938): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1198 10029 null
D/PMS     (  905): acquireWL(425a8de0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3310 1000 null
D/PMS     (  905): releaseWL(4352f938): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothSapReceiver( 3947): SapReceiver onReceive 
V/BluetoothSapReceiver( 3947): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3947):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3947): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/HtcBtWidget_BTWidgetProvider( 3973): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3973): updateWidget(context) for widget: 
D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 12
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  905): releaseWL(425a8de0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  905): acquireWL(432acce0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3310 1000 null
D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 12
V/BluetoothMasService( 3947): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3947): Manager Instance is not NULL
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42645bd0:true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
I/LocationAgent( 3310): new LocationAgent instance!!
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/HtcTagManager( 3310): HtcTagManager construction complete
D/EmailUtils( 3947): ============NULL aList========
V/EmailUtils( 3947): <-getEmailAccountIdList
V/BluetoothSapService( 3947): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3947): state: 12
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 12
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
W/ContextImpl( 3947): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3947): Starting SAP server process
V/BluetoothPbapService( 3947): Handler(): got msg=1
V/BluetoothPbapService( 3947): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3947): Pbap Service initSocket
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3310): BluetoothInputDevice()
D/BluetoothAdapter( 3947): getBluetoothService(): entry
W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
E/BluetoothServiceJni( 3947): SOCK FLAG = 1 ***********************
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
D/BluetoothInputDevice( 3310): BluetoothInputDevice(): Binding service...
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
I/bt-btm  ( 3947):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/BluetoothPan( 3310): BluetoothPan()
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/BluetoothManagerService(  905): registerStateChangeCallback+
V/BluetoothPbapService( 3947): Succeed to create listening socket 
V/BluetoothPbapService( 3947): Accepting socket connection...
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 8
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
V/BluetoothMasService( 3947): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3947): BluetoothMns: isEmailEnabled: true
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
,D/BluetoothPan( 3310): BluetoothPan(): Binding service...
,D/BluetoothAdapter( 1108): 1104719840: getState(). Returning 12
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): WiFioffload: SignalStrength: =97
,D/BluetoothAdapter( 1108): 1104719840: getState(). Returning 12
,D/BluetoothMasService( 3947): Map_prev 1
,D/WifiNative-wlan0(  905):    returned true
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): WiFioffload: update mobile network = Unknown
I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/WifiNative-wlan0(  905):    returned true
,D/PhoneStatusBar( 1108): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/BluetoothMap( 3310): Create BluetoothMap proxy object
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): Power_Mode_Type mode = 1
I/wpa_supplicant( 4006): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
D/BluetoothManagerService(  905): registerStateChangeCallback+
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
D/BluetoothAdapter( 3947): getBluetoothService(): entry
W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothManagerService(  905): Registered receivers: 9
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
,E/BluetoothMap( 3310): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothSap( 3310): BluetoothSap() call bindService
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(42591130): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@435d92b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@435d92b8 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 10
E/BluetoothServiceJni( 3947): SOCK FLAG = 3 ***********************
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3947):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothPbap( 3310): BluetoothPbap()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 11
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
,D/BluetoothPbap( 3310): BluetoothPbap(): Binding service...
D/BluetoothAdapter( 3947): getBluetoothService(): entry
,W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3947): SOCK FLAG = 3 ***********************
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3947):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothSapService( 3947): Sap_prev 1
,V/BluetoothSapService( 3947): SAP Service startRfcommListenerThread
D/BluetoothA2dp( 3310): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,V/BluetoothSapService( 3947): Sap Service initRfcommSocket
D/BluetoothManagerService(  905): Registered receivers: 12
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3947): getBluetoothService(): entry
,W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3947): SOCK FLAG = 3 ***********************
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3947):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3947): Succeed to create listening socket 
,V/BluetoothSapService( 3947): Accepting socket connection...
,D/BluetoothAdapter( 1108): 1104719840: getState(). Returning 12
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
,D/BluetoothA2dp( 3310): BluetoothA2dp(): Binding service...
,I/QuickSettingMiniLite( 1108): updateLiteState:no connect device!
,I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:0
,D/BluetoothHeadset( 3310): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
,D/BluetoothHeadset( 3310): BluetoothHeadset(): Binding service...
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
V/TAG     ( 3947): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3947): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b31b00
D/HtcTagManager( 3310): startProxy
,V/BluetoothPbapService( 3947): Pbap Service onBind
,W/ContextImpl( 3310): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3310): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/BluetoothFtpService( 3947): Ftp Service onCreate
D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 12
D/BluetoothMasReceiver( 3947): Bluetooth STATE CHANGED to 12
D/BluetoothAdapter( 3947): getBluetoothService(): entry
W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothFtpService( 3947): Ftp_prev 1
D/DockEventReceiver( 3310): finishStartingService: stopping service
E/BluetoothServiceJni( 3947): SOCK FLAG = 0 ***********************
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3947):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3947): Accept thread started.
D/WISPrService( 3310): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothPan( 3310): BluetoothPAN Proxy object connected
D/PanProfile( 3310): Bluetooth service connected
D/BluetoothA2dp( 3310): Proxy object connected
D/A2dpProfile( 3310): Bluetooth service connected
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
D/BluetoothAdapter( 3947): getBluetoothService(): entry
W/BluetoothAdapter( 3947): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 3310): Proxy object connected
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
E/BluetoothServiceJni( 3947): SOCK FLAG = 1 ***********************
D/HeadsetProfile( 3310): Bluetooth service connected
I/bt-btif ( 3947): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3947): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3947): Write Extended Inquiry Response to controller
,I/bt-btif ( 3947): BTA_JvRfcommStartServer
I/bt-btm  ( 3947): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4014): onCreate: going to find gatt base service first.
I/bt-btm  ( 3947):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/WISPrService( 3310): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
V/BluetoothFtpService:RfcommSocketAcceptThread( 3947): Run Accept thread
,D/BluetoothAdapter( 3947): 1102019264: getState(). Returning 12
,V/BluetoothMasService( 3947): parseIntent 1: mIsEmailEnabled: true
,D/WifiService(  905): New client listening to asynchronous messages
D/BluetoothInputDevice( 3310): Proxy object connected
V/EmailUtils( 3947): Manager Instance is not NULL
D/HidProfile( 3310): Bluetooth service connected
D/BluetoothAdapter( 3310): 1103590064: getState(). Returning 12
D/SapServerProfile( 3310): Bluetooth service connected
D/BluetoothPbap( 3310): Proxy object connected
,D/PbapServerProfile( 3310): Bluetooth service connected
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43096228:true
,D/PMS     (  905): releaseWL(432acce0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/[HTC_BLE][Constants]( 4014):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4014):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 4014):  + discoverServicesOnBonded = false
D/EmailUtils( 3947): ============NULL aList========
V/EmailUtils( 3947): <-getEmailAccountIdList
D/BluetoothMasService( 3947): Map_prev 1
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4014):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4014): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41af9ce0
D/[HTC_BLE][Constants]( 4014): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4014): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4014): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4014): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4014): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4014): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4014): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3310): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4014): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4014): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4014): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41af9ce0
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4014): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41af9ce0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4014): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41af9ce0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b04cc8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4014): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41af9ce0
D/HtcTagProfile( 3310): setup proxy
D/HtcPxpProfile( 3310): setup proxy
,D/HtcFmpProfile( 3310): setup proxy
,W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431e2160:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3835): new LocationAgent instance!!
,D/HtcTagManager( 3835): HtcTagManager construction complete
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/BluetoothInputDevice( 3835): BluetoothInputDevice()
,D/RingtoneManager( 4014): getExternalStorageState=mounted
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/BluetoothInputDevice( 3835): BluetoothInputDevice(): Binding service...
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3835): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 15
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/BluetoothPan( 3835): BluetoothPan(): Binding service...
,D/BluetoothMap( 3835): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 16
E/BluetoothMap( 3835): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[-1]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[1]: Daisy
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[6]: Lavender
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[8]: Olive
D/BluetoothSap( 3835): BluetoothSap() call bindService
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[9]: Rose
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[11]: Thalia
D/BluetoothManagerService(  905): Registered receivers: 17
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[13]: Wintergreen
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + Available RingingTone[14]: Wisteria
W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4014):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothPbap( 3835): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 18
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/BluetoothPbap( 3835): BluetoothPbap(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4014): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4014): Enter IdleState
D/BluetoothA2dp( 3835): BluetoothA2dp()
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4014): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4014): initScanModeInterface: true
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 19
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423de960:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/BluetoothA2dp( 3835): BluetoothA2dp(): Binding service...
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4014): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4014):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 4014):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4014):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4014):  + discoverServicesOnBonded = false
,D/BluetoothHeadset( 3835): BluetoothHeadset()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 20
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/BluetoothHeadset( 3835): BluetoothHeadset(): Binding service...
W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4014): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b04cc8
,D/HtcTagManager( 3835): startProxy
,W/ContextImpl( 3835): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3835): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3835): setBluetoothStateOn
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/HtcTagManager( 3835): startProxy
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/BluetoothAdapterService(1102001088)( 3947): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3947): getBondedDevices: length=10
D/wpa_supplicant( 4006): EAPOL: startWhen --> 0
D/wpa_supplicant( 4006): EAPOL: disable timer tick
D/BluetoothAdapter( 3835): getBluetoothService(): entry
D/BluetoothAdapter( 3835): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3835): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41b33890
D/BluetoothDevice( 3835): getService : Register callback
E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12,
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,E/BluetoothDevice( 3835): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): addHtcTagProfiles
,D/BluetoothInputDevice( 3835): Proxy object connected
,D/HidProfile( 3835): Bluetooth service connected
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/BluetoothPan( 3835): BluetoothPAN Proxy object connected
D/PanProfile( 3835): Bluetooth service connected
D/SapServerProfile( 3835): Bluetooth service connected
D/BluetoothPbap( 3835): Proxy object connected
D/PbapServerProfile( 3835): Bluetooth service connected
,D/BluetoothA2dp( 3835): Proxy object connected
,D/A2dpProfile( 3835): Bluetooth service connected
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/BluetoothHeadset( 3835): Proxy object connected
,D/HeadsetProfile( 3835): Bluetooth service connected
,D/BluetoothAdapter( 3835): 1102029208: getState(). Returning 12
,D/HtcTagManager( 3835): onServiceConnected
D/HtcTagProfile( 3835): setup proxy
D/HtcPxpProfile( 3835): setup proxy
,D/HtcFmpProfile( 3835): setup proxy
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4006): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/PMS     (  905): releaseWL(42591130): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): WiFi gateway: 0x101a8c0
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=21360 delay=15s
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  905): WAN detection
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 3310): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@4245f858
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): acquireWL(43ee5fb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [3][0][0]
I/QuickSettingWifi( 1108): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43ee5fb0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WIFI_ICON( 1108): WifiActivity: 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4128 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0,
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/PMS     (  905): acquireWL(43c52578): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3385/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3748/10100)
I/ConnectivityHelper( 1249): [onReceive] WIFI(1): CONNECTED
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  365): [NET] +++++ res_nsend xid =55ec +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  365): [NET] NOT IN CACHE,
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1249/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3748/10100)
D/PMS     (  905): acquireWL(435e7700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43fce8f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 136
D/libc    (  365): [NET]res_nsend:resplen=104
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
I/MusicStore( 4128): Database version: 95
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(43c72940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4128): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/IntentController( 1108): receive(android.intent.action.TIME_SET,4,false)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/DotMatrix( 1522): [EventService] EVENT_RESET_THEME_TIMESTAMP
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
I/FeedActionBar( 1249): updateLastUpdatedTime(in String) LAST UPDATED 1:38
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1522): [EventService] isTheSameDay:false,timestamp is early than today:true
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_,recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4128): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(435e7700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c712c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1198): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/PMS     (  905): acquireWL(425d58f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 905 1000 WorkSource{10029}
W/dalvikvm( 1198): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/GoogleURLConnFactory( 1198): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 3900): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3900): 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
D/PMS     (  905): acquireWL(44159140): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4006): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/PMS     (  905): acquireWL(43ffd598): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421a4c38
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421a4c38, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d09670
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4260b4d8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4128): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PMS     (  905): Going to sleep due to screen timeout...
W/BatSI   (  905): Couldn't get kernel wake lock stats
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
D/PMS     (  905): acquireWL(43a4cd40): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,W/PMS     (  905): mWirelessDisplayManager is null
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4162 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  905): releaseWL(43fce8f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  905): NTP server returned: 1450226368416 (Wed Dec 16 01:39:28 CET 2015) reference: 107168 certainty: 11 system time offset: -262
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43786648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43786648): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(41ca3498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4128): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/dalvikvm( 1963): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): releaseWL(41ca3498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,W/ContextImpl( 4128): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  905): acquireWL(42568890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42568890): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(43c52578): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4309b638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4128, uid=10154, userID:0
,D/PMS     (  905): releaseWL(4309b638): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(422f7018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1963): Failed to find provider info for com.android.contacts.metadata
,D/PMS     (  905): releaseWL(425d58f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/Auth.Api.Credentials( 1963): [CredentialSyncAdapter] Unknown sync event.
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1198): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(433d9250): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 905 1000 WorkSource{10029}
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(422f7018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(434add20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25821, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 107562, reason: UserStart
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43ffd598): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
D/libc    ( 1198): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9efe +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
D/PMS     (  905): releaseWL(434add20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43765858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43c712c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PhoneStatusBar( 1108): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
E/ExternalAccountType( 1332): Unsupported attribute readOnly
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2734
D/libc    (  365): [NET]res_nsend:resplen=45
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(4330b0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43765858): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(435da3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(435da3e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43688170): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43688170): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43079bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43079bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNativ,e-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029),
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(434cd928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(433d9250): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(435e8de8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(434cd928): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 333ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1233): ScreenObserver: OFF
D/NfcService( 1233): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43b4b2d8)
,D/NfcService( 1233): applyRouting -2
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4353d8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(42567420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
I/InputMethodManagerService(  905): Disable input method client, pid=3900
D/PMS     (  905): releaseWL(4353d8a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/ResourceType( 3900): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3900): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aea288 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
D/PMS     (  905): releaseWL(42567420): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  905): acquireWL(4238fe30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): releaseWL(4238fe30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMN     (  905): onScreenOn
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/NfcService( 1233): applyRouting - 0
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/MtpService( 2147): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2147): [MTP][onReceive]-
,D/NfcService( 1233): applyRouting -2
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MediaRouterService(  905): Client com.google.android.music (pid 4128): Registered
D/PMS     (  905): acquireWL(4309d3a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1233 1027 null
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): releaseWL(4309d3a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=21361 delay=15s
,I/MediaRouter( 4128): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): SET_SCREEN_ON:On
I/wpa_supplicant( 4006): htc_wext_set_keepalive +
I/wpa_supplicant( 4006): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4006): getPrivFuncNum +	
I/wpa_supplicant( 4006): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 4006): htc_wext_set_TX_TRACKING - ret = 0
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): acquireWL(425a88b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
D/PMS     (  905): releaseWL(4330b0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,I/ClockThread( 1108): stop update clock
,V/SRS_Proc(  372): ParamSet string: screen_state=on
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4006): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  905): updateScreenOn: false
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4128/10154)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
,I/NetworkMonitor( 4128): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(43103a10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4200 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(425a88b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(436b0260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/DelayedSyncController( 4162): Delaying sync.
,D/MediaRouter( 4128): getSelectedRoute
D/PMS     (  905): acquireWL(43ee0ad8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(436b0260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4406a4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43ee0ad8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(434dc4a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4406a4a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43c8ab08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/PMS     (  905): releaseWL(434dc4a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43a4cd40): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4128/10154)
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/NetworkMonitor( 4128): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4014): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4014): onScreenOn: 1450226369204
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4014): onScreenOn: 1450226369204
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4128, uid=10154, userID:0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d09670
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d09670, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4260b4d8
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(4409d6e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43c8ab08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=21361 mDataStallAlarmIntent=PendingIntent{435f6258: PendingIntentRecord{437b1d20 android broadcastIntent}}
D/PMS     (  905): releaseWL(4409d6e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4006): SET_SCREEN_ON:Off
I/wpa_supplicant( 4006): htc_wext_set_keepalive +
I/wpa_supplicant( 4006): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4006): getPrivFuncNum +	
I/wpa_supplicant( 4006): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4006): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4006): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4006): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 4006): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/PMS     (  905): acquireWL(43ba65a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): acquireWL(42ab7658): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  905): updateScreenOn: false
,D/wpa_supplicant( 4006): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4200): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  905): releaseWL(42ab7658): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  905): releaseWL(43ba65a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ACRA    ( 4200): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4200): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  905): acquireWL(4408bd58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43524e10: PendingIntentRecord{43bcfdc0 com.google.android.gms startService}}) : type=2 triggerAtTime=315360108019 win=-1 tElapsed=315360108019 maxElapsed=551880108016 interval=0 standalone=false
D/PMS     (  905): releaseWL(43103a10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/Process (  905): killProcessQuiet, pid=1302
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 1302:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1221): start background delete task...
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/DriveInitializer( 1963): Awaiting to be initialized
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/DriveInitializer( 1963): Background init thread started
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] getTotalRam: 1873 Mb
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/SystemClassLoaderAdder( 4200): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
D/PMS     (  905): acquireWL(440587c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(440587c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43b76798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43b76798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,V/DexLibLoader( 4200): Preparing secondary program dexes.
V/DexLibLoader( 4200): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4200): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4200): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4200): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4200): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4200): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4200): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4200): Dex already copied
D/OdexVerifier( 4200): Odex verification is skipped.
V/DexLibLoader( 4200): Creating class loader
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/PMS     (  905): acquireWL(4369e2e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/PMS     (  905): releaseWL(4408bd58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4162): Delaying sync.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43625990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43625990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4383b950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
V/DexLibLoader( 4200): Finished creating class loader
V/DexLibLoader( 4200): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4200): Dex already copied
D/OdexVerifier( 4200): Odex verification is skipped.
V/DexLibLoader( 4200): Creating class loader
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4014): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4014): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4014): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4014): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4014): onScreenOff
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 1302
D/PMS     (  905): releaseWL(4369e2e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,V/DexLibLoader( 4200): Finished creating class loader
,V/DexLibLoader( 4200): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4200): Dex already copied
D/OdexVerifier( 4200): Odex verification is skipped.
,V/DexLibLoader( 4200): Creating class loader
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(435f9288): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
,V/DexLibLoader( 4200): Finished creating class loader
,V/DexLibLoader( 4200): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4200): Dex already copied
D/OdexVerifier( 4200): Odex verification is skipped.
V/DexLibLoader( 4200): Creating class loader
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4383b950): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(430cc608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(430cc608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
V/DexLibLoader( 4200): Finished creating class loader
V/DexLibLoader( 4200): Verifying classes from secondary dexes.
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43502280): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(435f9288): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43502280): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/BTIF_CORE( 3947): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3947): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3947): Wake lock released
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1198): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43e4dea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/DexLibLoader( 4200): DexLibLoader.ensureDexLoaded took 133 ms
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(435e8de8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43c23318): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/PMS     (  905): releaseWL(43e4dea8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(437c9a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(437c9a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1963): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43a8e350): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/PhenotypeConfigurator( 1198): Server returned 404
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): releaseWL(43c23318): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): acquireWL(440894e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43a8e350): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/PMS     (  905): releaseWL(43c72940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/PMS     (  905): acquireWL(43165028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,W/DriveInitializer( 1963): Background init thread ended
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/PMS     (  905): releaseWL(440894e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(434b7430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43d3a880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): releaseWL(434b7430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44159140): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(44116dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
D/PMS     (  905): acquireWL(43551ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
D/PMS     (  905): releaseWL(43d3a880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(43c4bbe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43165028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44116dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44186928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): releaseWL(44186928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(441842a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): acquireWL(441595b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1198): Vacuum at: now=1450226369888 tag=VacuumService
,D/PMS     (  905): releaseWL(43c4bbe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(44183bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441595b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(441842a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44183bf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44038190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(436521f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43551ea8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(436521f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/PMS     (  905): releaseWL(44038190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43fcfc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/PMS     (  905): releaseWL(43fcfc98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43f8b7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(43f8b7e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PhoneStatusBar( 1108): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 4200): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5f3b +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4200): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4200): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4200): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4200): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4200): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4200): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,W/ActivityManager(  905): Disable JIT of com.htc.bgp
,I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4252 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/Process (  905): killProcessQuiet, pid=3748
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3748:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3748
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4252): Created com.android.providers.calendar.CalendarAlarmManager@41b14da0(com.android.providers.calendar.HtcCalendarProvider@41afd128)
,W/fb4a(:<default>):UserScope( 4200): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/CalendarProvider2( 4252): wait start:true
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4200): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4200): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/CalendarProvider2( 4252): wait end:false
,D/ContactMessageStore( 1221): notify MmsSms
,D/AccFlag ( 1221): sense_version=6.0
,D/AccFlag ( 1221): sku_id=99
,I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4269 uid=10055 gids={50055, 1023, 3003, 5012}
,D/PMS     (  905): acquireWL(437859d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029}
,V/AlarmManager(  905): sending alarm PendingIntent{43542e00: PendingIntentRecord{4259eb98 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
,D/PMS     (  905): releaseWL(437859d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1221): sku_id=99
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1221): sku_id=99
E/dalvikvm( 4200): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4200): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4200): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4200): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4200): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4200): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4200): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4200): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4200): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4200): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4200): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4200): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4200): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4200): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4200): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4200): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4200): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4200): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1221): sku_id=99
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 68
,D/AccFlag ( 1221): sku_id=99
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 9.918MB for 39954-byte allocation
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,D/PMS     (  905): acquireWL(425b6e10): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 9.995MB for 79892-byte allocation
,D/PluginProvider( 4269): PluginProvider onCreate
,D/PluginProvider( 4269): current plugin count: 18
,D/HtcAppUPService( 4269): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 10.063MB for 84664-byte allocation
,D/AutoSetting( 4269): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4286 uid=10079 gids={50079, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3770
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3770:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4269/10055)
,D/AutoSetting( 4269): service - onCreate()
,D/AutoSetting( 4269): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4269): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4269): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  905): request 4228dc60 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4269): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4269): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4269/10055)
,I/dalvikvm-heap( 4200): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/MobileConnectivityChangeReceiver( 4286): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4286): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4286): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4286): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c8b0e8 u0 ReceiverList{43cc4a48 4200 com.facebook.katana/10027/u0 remote:425be9a0}}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4286/10079)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{430e7018 u0 ReceiverList{430f4218 4200 com.facebook.katana/10027/u0 remote:435f81c0}}
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4303 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4286/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4286/10079)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/PMS     (  905): acquireWL(4409a0c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/PMS     (  905): acquireWL(43ffc4c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1963): Checkin interval check for package: unspecified last checkin: 1450203535514 min interval config: 0 actual interval: 22835991
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
,D/PMS     (  905): releaseWL(4409a0c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
,I/CheckinService( 1963): Checking schedule, now: 1450226371512 next: 1450203565454
,I/CheckinService( 1963): active receiver: enabled
I/CheckinService( 1963): Preparing to send checkin request
,I/EventLogService( 1963): Accumulating logs since 1450226310212
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1963, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4303): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4303): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4303): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  905): acquireWL(440f98a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Recipient 3770
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(440f98a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4303): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4303): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4200): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4200): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4200): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4303/10151)
,V/WebViewChromiumFactoryProvider( 4303): Binding Chromium to main looper Looper (main, tid 1) {41adcaf0}
,I/LibraryLoader( 4303): Expected native library version number "",actual native library version number ""
,I/chromium( 4303): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4303): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(4365a990): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4303): BLUETOOTH permission is missing!
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43c737a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(4365a990): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
I/Adreno-EGL( 4303): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4303): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4303): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4303): Local Branch: 
I/Adreno-EGL( 4303): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4303): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4303):                  aa63bbd948f41d15fc72f585e
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 4303): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4303/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4303/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1343): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1343): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1343): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1343): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3548/10160)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=3735
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3548/10160)
,I/ActivityManager(  905): Killing 3735:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1343): [NET] getaddrinfo-, 1
D/libc    ( 1343): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4861 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(43731980): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1963): Checkin interval check for package: unspecified last checkin: 1450203535514 min interval config: 0 actual interval: 22836235
I/ActivityManager(  905): Recipient 3735
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): releaseWL(43731980): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 142
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1343): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/iu.SyncManager( 1963): SYNC; picasa accounts
,D/NetworkLogImpl( 1963): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/iu.Environment( 1963): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
I/iu.UploadsManager( 1963): num queued entries: 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/iu.UploadsManager( 1963): num updated entries: 0
,I/iu.SyncManager( 1963): NEXT; no task
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/AlertReceiver( 3821): beginStartingService
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/PMS     (  905): acquireWL(437128b0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3821 10013 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  905): acquireWL(42646778): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1343): [NET] getaddrinfo-, 1
D/libc    ( 1343): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ebab +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
,D/AlertService( 3821): start to updateAlertNotification!
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4355 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/AlertService( 3821): No fired or scheduled alerts
,D/HtcAlertUtils( 3821): -- cancelReminderNotification --
,D/HtcAlertUtils( 3821): broadcastExistReminder!
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(437128b0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 3821): stopSelfResult true
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 46
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1343): [NET] getaddrinfo_proxy-, success
,W/WeatherRequest( 1108): request cur loc, but there is no sys cur
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4370 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4355): can't get weather sync account
,D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
,W/WeatherRequest( 4355): request cur loc, but there is no sys cur
,W/Settings( 4355): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 5 10 17
,D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,I/GCM     ( 1343): GCM config loaded
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,I/CalendarProvider2( 4252): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4252): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  905): acquireWL(44186928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(441771c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4370 10071 null
,D/PMS     (  905): acquireWL(44159140): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4370 10071 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,I/ActivityManager(  905): Killing 3788:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3788
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=11 [17][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3788
D/PMS     (  905): releaseWL(441771c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): acquireWL(43fdc078): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/TodoTaskshortcut( 4370): update TASK shortcut>
I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4390 uid=10090 gids={50090, 3003, 5012, 1028}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  905): releaseWL(42646778): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1343/10029)
,I/TodoTaskNotifyService( 4370): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43cc4aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43fdc078): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/TodoTaskNotifyService( 4370): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43c7e028): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,W/NotifyReceiver( 4370): stopSelfResult true
,I/WorldClock.Global( 4390): isHtcDevice = true
D/PMS     (  905): releaseWL(44159140): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1343/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/PMS     (  905): releaseWL(44186928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4239a478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=3502
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4403 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1343/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
I/ActivityManager(  905): Killing 3502:com.google.android.gm/u0a107 (adj 15): empty #17
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/WorldClock.Global( 4390): isHtcDevice = true
,I/WorldClock.AlarmUtils( 4390): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
D/PMS     (  905): releaseWL(43cc4aa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
I/WorldClock.AlarmUtils( 4390): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4390): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
D/PMS     (  905): releaseWL(43c7e028): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/IntentController( 1108): receive(android.intent.action.ALARM_CHANGED,1,false)
D/PMS     (  905): releaseWL(4239a478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4378e558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,I/Icing   ( 1963): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,W/dalvikvm( 4403): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/PMS     (  905): releaseWL(4378e558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/MultiDex( 4403): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4403): install
,I/MultiDex( 4403): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4422 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/MultiDex( 4403): loading existing secondary dex files
,I/MultiDex( 4403): load found 3 secondary dex files
,I/MultiDex( 4403): install done
I/ActivityManager(  905): Recipient 3502
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 1963): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
,D/PMS     (  905): releaseWL(425b6e10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=3572
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/TimeService( 4422): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226372445
I/ActivityManager(  905): Killing 3572:com.android.vending/u0a74 (adj 15): empty #17
,W/dalvikvm( 4403): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4403): VFY: unable to resolve instance field 36
,D/Process (  905): killProcessQuiet, pid=3872
,W/dalvikvm( 4403): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3872:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3572
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/JNIHelp ( 4403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PMS     (  905): acquireWL(423b3ac0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Recipient 3872
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(423b3ac0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1963): Checkin interval check for package: unspecified last checkin: 1450203535514 min interval config: 0 actual interval: 22836975
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): acquireWL(41de2150): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1963 10029 null
,D/PMS     (  905): acquireWL(42395d18): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): releaseWL(41de2150): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  905): releaseWL(42395d18): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4439 uid=10041 gids={50041}
,I/ProviderInstaller( 4403): Installed default security provider GmsCore_OpenSSL
,D/Process (  905): killProcessQuiet, pid=4034
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4034:com.htc.widget.process2/u0a50 (adj 15): empty #17
,D/AutoSetting( 4269): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 4269): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 3310): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
I/ActivityManager(  905): Recipient 4034
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/        ( 3310): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3310): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3310): Cust_ConnectToPC   : spcsc>false
D/        ( 3310): Cust_ConnectToPC   : IPT>true
D/        ( 3310): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3310): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3310): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3310): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3310): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3310): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3310):  defaultType:0
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/ActivityManager(  905): Resuming delayed broadcast
,W/dalvikvm( 4403): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4403): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4403): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4403): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4457 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/NativeLibraryUtils( 4403): Install completed successfully. count=14 extracted=0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,D/SmartSyncUtils( 4457): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(43c52640): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4457 1000 null
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/SmartSyncUtils( 4457): getMobilePolicyEnabled, result = true
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  905): releaseWL(43c52640): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=3973
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3973:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3973
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,W/ContextImpl( 4457): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4457): isEpsOn(), nState = 0
D/SmartSyncUtils( 4457): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4457): isEpsOn(), nState = 0
W/dalvikvm( 4403): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4403): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/WifiService(  905): New client listening to asynchronous messages
,W/dalvikvm( 4403): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4403): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260b4d8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260b4d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4260b4d8, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4260b4d8
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(435061b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42693548 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42693548 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/ProviderChangeReceiver( 3821): ---------------------------------------------------
D/ProviderChangeReceiver( 3821): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3821): start to updateAlertNotification!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/GoogleURLConnFactory( 4403): Using platform SSLCertificateSocketFactory
W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/AlertService( 3821): No fired or scheduled alerts
D/HtcAlertUtils( 3821): -- cancelReminderNotification --
D/HtcAlertUtils( 3821): broadcastExistReminder!
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(435061b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  372): PrepareKeyRequest: nonce=803426663
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4480 uid=10078 gids={50078}
,D/libc    ( 4403): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4403): [NET] getaddrinfo-,err=8
D/libc    ( 4403): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4403): [NET] getaddrinfo-, 1
,D/libc    ( 4403): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4282 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/Process (  905): killProcessQuiet, pid=3992
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3992:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/SMSBackup( 4480): Got a database change event
,D/Process (  905): killProcessQuiet, pid=4128
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4128:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3992
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 286
D/libc    (  365): [NET]res_nsend:resplen=86
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4403): [NET] getaddrinfo_proxy-, success
D/PMS     (  905): acquireWL(43b75a58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4370 10071 null
,I/ActivityManager(  905): Recipient 4128
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  372): CdmEngine::CloseSession
D/MediaRouterService(  905): Client com.google.android.music (pid 4128): Died!
D/PMS     (  905): acquireWL(436044c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4370 10071 null
E/TodoTaskNotifyService( 4370): java.lang.NullPointerException
,W/System.err( 4370): java.lang.NullPointerException
W/System.err( 4370): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4370): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4370): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4370): stopSelfResult true
,E/TodoTaskNotifyService( 4370): java.lang.NullPointerException
W/System.err( 4370): java.lang.NullPointerException
W/System.err( 4370): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4370): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4370): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4370): mStartingService is null
,W/NotifyReceiver( 4370): stopSelfResult false
D/PMS     (  905): releaseWL(43b75a58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): acquireWL(43162288): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4370 10071 null
D/PMS     (  905): acquireWL(436044c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4370 10071 null
D/PMS     (  905): releaseWL(43162288): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(436044c0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/WearableService( 1198): callingUid 10029, callindPid: 1198
,D/LocationInitializer( 1963): Restart initialization of location
,E/MDM     ( 1198): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): acquireWL(426149f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1198): location=null
D/PMS     (  905): releaseWL(426149f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/libc    ( 4403): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4403): [NET] getaddrinfo-,err=8
D/libc    ( 4403): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4403): [NET] getaddrinfo-,err=8
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2625094775
,W/fb4a(:<default>):UserScope( 4200): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4200): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [29][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  372): CdmEngine::CloseSession
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4200): Called registerBroadcastReceiver twice.
,I/Adreno-EGL( 4403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4403): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4403): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4403): Local Branch: 
I/Adreno-EGL( 4403): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4403): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4403):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,I/Adreno-EGL( 4403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4403): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4403): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4403): Local Branch: 
I/Adreno-EGL( 4403): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4403): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4403):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4200/10027)
,I/Adreno-EGL( 4403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4403): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4403): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4403): Local Branch: 
I/Adreno-EGL( 4403): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4403): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4403):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4403/10029)
,W/Settings( 4403): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
,D/libc    ( 1963): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1963): [NET] getaddrinfo-,err=8
D/libc    ( 1963): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1963): [NET] getaddrinfo-, 1
D/libc    ( 1963): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e841 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1963): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1963): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1963): [NET] getaddrinfo-,err=8
,D/libc    ( 1963): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1963): [NET] getaddrinfo-,err=8
D/libc    ( 1963): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1963): [NET] getaddrinfo-,err=8
,D/PMS     (  905): releaseWL(43c737a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinTask( 1963): Sending checkin request (12361 bytes)
,I/CheckinResponseProcessor( 1963): From server: 3 gservices updates and 0 deletes
,I/CertBlacklister(  905): Certificate blacklist changed, updating...
,I/CertBlacklister(  905): Certificate blacklist updated
,I/GservicesProvider( 1343): main difference update completed
,I/ActivityManager(  905): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4517 uid=10016 gids={50016, 3003, 5012, 2001}
,I/CheckinRequestBuilder( 1963): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4286/10079)
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1963): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4517): Update started
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4517): Update started
,I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1963/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=15 [20][3][0]
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 2147): Download 211 starting
D/PMS     (  905): acquireWL(441771c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2147 10021 WorkSource{10016}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4517): Received malformed URL while handling Gservices.CHANGED_ACTION
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
W/ActivityThread( 2147): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=4200
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4555 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  905): Killing 4200:com.facebook.katana/u0a27 (adj 15): empty #17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42426400): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2147 10021 WorkSource{10016}
I/DownloadManager( 2147): Download 212 starting
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
,I/CheckinRequestBuilder( 1963): Classify the device as Phone.
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    ( 2147): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2147): [NET] getaddrinfo-,err=8
D/libc    ( 2147): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2147): [NET] getaddrinfo-, 1
,D/libc    ( 2147): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3860 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/libc    ( 2147): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2147): [NET] getaddrinfo-,err=8
D/libc    ( 2147): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2147): [NET] getaddrinfo-, 1
,D/libc    ( 2147): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fd10 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/CheckinTask( 1963): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4555, uid=10032, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4555, uid=10032, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4555, uid=10032, userID:0
,D/PMS     (  905): acquireWL(4250ed90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4555, uid=10032, userID:0
,D/PMS     (  905): releaseWL(4250ed90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1963): Checking schedule, now: 1450226375797 next: 1450749312776
,I/CheckinService( 1963): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1963, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4555, uid=10032, userID:0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 45
D/libc    (  365): [NET]res_nsend:resplen=49
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2147): [NET] getaddrinfo_proxy-, success
D/libc    (  365): [NET]res_nsend:resplen=49
D/libc    (  365): [NET]res_queryN: exit 3, ancount=1
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2147): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 4200
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(4243efe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4243efe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1963): Checking schedule, now: 1450226375842 next: 1450749312776
,I/CheckinService( 1963): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1963, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
,D/PMS     (  905): acquireWL(43c2c940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,D/CheckinService( 1963): Recording last checkin time for package unspecified as 1450226375855
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
D/PMS     (  905): releaseWL(43c2c940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43ffc4c8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/ContactAccountLoggerTas( 2571): canRun() : Opted Out
D/PMS     (  905): acquireWL(42534bf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42534bf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Search.GservicesUpdateTask( 2571): Updating Gservices keys
I/DownloadManager( 2147): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  905): acquireWL(4252dbf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4252dbf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=14 [14][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(4400e170): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4400e170): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43232f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43232f90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4162
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/dalvikvm-heap( 3548): Grow heap (frag case) to 13.624MB for 1821008-byte allocation
I/ActivityManager(  905): Killing 4162:com.android.chrome/u0a96 (adj 15): empty #17
D/PMS     (  905): acquireWL(433d8e50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427a0148): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(433d8e50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2147): Ignoring Content-Length since Transfer-Encoding is also defined
,I/CheckinService( 1963): Checkin interval check for package: unspecified last checkin: 1450226375855 min interval config: 0 actual interval: 166
,I/DownloadManager( 2147): Download 212 finished with status SUCCESS
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3548, uid=10160, userID:0
,I/ContactAccountLoggerTas( 2571): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2571): canRun() : Opted Out
D/PMS     (  905): releaseWL(42426400): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
I/CheckinService( 1963): Checking schedule, now: 1450226376037 next: 1450749312776
,I/CheckinService( 1963): active receiver: disabled
,I/SystemUpdateService( 1963): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1963, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): acquireWL(425d6158): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [3][0][0]
I/ContactAccountLoggerTas( 2571): canRun() : Opted Out
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
I/dalvikvm-heap( 3548): Grow heap (frag case) to 15.319MB for 1821008-byte allocation
,D/SystemUpdateService( 1963): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
,D/SystemUpdateService( 1963): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3548, uid=10160, userID:0
,W/dalvikvm( 1963): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
I/ActivityManager(  905): Recipient 4162
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3548, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3548, uid=10160, userID:0
,I/SystemUpdateService( 1963): cancelUpdate (empty URL)
,I/SystemUpdateService( 1963): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/DownloadManager( 2147): Download 211 finished with status SUCCESS
D/PMS     (  905): releaseWL(441771c8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1343): [NET] getaddrinfo-, 1
,D/libc    ( 1343): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =966c +++++
,D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1343): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
,D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1343): [NET] getaddrinfo-,err=8
,W/SQLiteConnectionPool( 1963): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ContactAccountLoggerTas( 2571): canRun() : Opted Out
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/PMS     (  905): releaseWL(427a0148): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/Process (  905): killProcessQuiet, pid=3385
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3385:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/PMS     (  905): releaseWL(425d6158): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Recipient 3385
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/GAV2    ( 4303): Thread[GAThread,5,main]: No campaign data found.
,D/SystemUpdateService( 1963): onDestroy
,E/DynamiteModule( 1963): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1963): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1963): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1963): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1963): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1963): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1963): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1963): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1963): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1963): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1963): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1963): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 1963): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 1963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 1963): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 1963): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1963): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 1963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 1963): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1963): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1963): Selected local version of com.google.android.gms.flags,
,D/PMS     (  905): acquireWL(439cad90): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,D/SystemEventReceiver( 1963): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1963): Updating ocr activity enabled=false
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1963, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1198, uid=10029, userID:0
,D/PMS     (  905): releaseWL(439cad90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1963): Updating downloaded model state (gservices changed)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43079988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1963, uid=10029, userID:0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/GCM     ( 1343): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(4353e150): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(43079988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4381dc60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4381dc60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1108): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425ebbe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(4353e150): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1108): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(425ebbe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1108): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1198): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1198): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1198): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  905): acquireWL(42568c58): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{426251b8: PendingIntentRecord{43b0e508 com.google.android.gms startService}}) : type=2 triggerAtTime=315360115872 win=-1 tElapsed=315360115872 maxElapsed=551880115870 interval=0 standalone=false
,I/GCoreUlr( 1198): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1198): DispatchingService.onCreate()
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1963/10029)
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/PMS     (  905): acquireWL(42bf5650): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  905): acquireWL(43fdc400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(43fdc400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1198): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
D/PMS     (  905): acquireWL(43530e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43530e70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1198): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  905): releaseWL(42568c58): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
,I/GCoreUlr( 1198): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/DownloadManager( 2147): Download 213 starting
D/PMS     (  905): acquireWL(441842a8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2147 10021 WorkSource{10016}
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2147): Ignoring Content-Length since Transfer-Encoding is also defined
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
,D/PMS     (  905): acquireWL(440eef28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,I/DownloadManager( 2147): Download 214 starting
D/PMS     (  905): acquireWL(4319b8d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2147 10021 WorkSource{10016}
D/PMS     (  905): releaseWL(440eef28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4262f9f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  905): getAllNetworkInfo called by  (2147/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/PMS     (  905): releaseWL(4262f9f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2147): Ignoring Content-Length since Transfer-Encoding is also defined
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2147/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=16 [30][5][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2147): Download 213 finished with status SUCCESS
D/PMS     (  905): releaseWL(441842a8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/GCoreUlr( 1198): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/UpdateFetcherService( 4517): Update downloaded, starting installation
,I/UpdateFetcherService( 4517): Started installation
D/PMS     (  905): acquireWL(43e2f3f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43e2f3f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1198): Unbound from all location providers
,I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  905): releaseWL(42bf5650): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/GCoreUlr( 1198): DispatchingService.onDestroy()
,I/GCoreUlr( 1198): Stopping handler for UlrDispSvcFast
D/PMS     (  905): acquireWL(435ff738): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2147): Download 214 finished with status SUCCESS
,I/GCoreUlr( 1198): Unbound from all location providers
,I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  905): releaseWL(435ff738): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4319b8d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/DownloadManager( 2147): Download 214 already finished; skipping
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4517): Update downloaded, starting installation
,I/UpdateFetcherService( 4517): Started installation
,I/ConfigUpdateInstallReceiver(  905): Not installing, new version is <= current version
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ctxmgr  ( 1198): [WorkManager]Long workInfo: label=RefreshLocationConsentOperation, startTime=2015-12-16 01:39:37.101+0100, stopTime=2015-12-16 01:39:38.427+0100, duration=1326ms
D/PMS     (  905): acquireWL(42b729a0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42b729a0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43c289d8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43c289d8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4303
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4303:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4303
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3548): Grow heap (frag case) to 17.071MB for 1821008-byte allocation
,I/GAV2    ( 3548): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 4269): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4269): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4269): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/PackageSettings(  905): Skipping PackageSetting{42167668 com.example.hello/10397} due to missing metadata
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4639 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Launcher( 1249): Deferring update until onResume
,D/Launcher( 1249): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4639): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4639): MmsConfig.loadMmsSettings
,W/dalvikvm( 4639): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4639): VFY: unable to resolve instance field 36
,W/dalvikvm( 4639): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4639): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4662 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,W/PackageManager(  905): Unable to load service info ResolveInfo{435d4e00 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/MessageFrequencyProvider( 4662): onCreate
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4639, uid=10111, userID:0
V/GetPrviateResource( 4662): GetPrviateResource
D/MmsCustomizationProvider( 4662): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 4662): GetPrviateResource
,D/MmsCustomizationProvider( 4662): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4639): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4639): MmsConfig.loadFromDatabase
,W/Settings( 4639): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4639): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4639): MmsConfig.loadFromResources
,E/Babel   ( 4639): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4639): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4639, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4639, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4639, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4639, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4639, uid=10111, userID:0
,D/PMS     (  905): acquireWL(43bb9650): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4639 10111 null
,I/ProviderInstaller( 4639): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4379a738 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/Process (  905): killProcessQuiet, pid=4355
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/[PluginManager]RegisterService( 4269): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4269): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Killing 4355:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Recipient 4355
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MessageCustFlag( 4662): sense_version=6.0
D/BTAccessoryUtil( 4662): createReceiver
D/BTAccessoryUtil( 4662): registerReceiver return intent = null
D/MessageCustFlag( 4662): sku_id=99
W/SystemReader( 4662): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4662): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4662): networkCode: 
,D/MessageCustFlag( 4662): sku_id=99
D/MmsConfig( 4662): SIE smsPri: null
,D/MmsConfig( 4662): networkCode: 
,D/HtcTelephonyCapability( 4662): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4662): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4662): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4662): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(436254e0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(430d9e60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3548 10160 null
D/PMS     (  905): releaseWL(436254e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(430d9e60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  905): releaseWL(43bb9650): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(440a2d88): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4688 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4390
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4390:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4390
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4688, uid=10074, userID:0
,D/PMS     (  905): releaseWL(440a2d88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4688): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/PMS     (  905): acquireWL(43c0a510): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4688/10074)
,D/PMS     (  905): releaseWL(43c0a510): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(439946a0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1198): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  905): releaseWL(439946a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4361bc08): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43620c18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43620c18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/PMS     (  905): releaseWL(4361bc08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42630df0): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4688/10074)
,D/PMS     (  905): releaseWL(42630df0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Finsky  ( 4688): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4688): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4688): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4688): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4688, uid=10074, userID:0
,D/PMS     (  905): acquireWL(4413c1e8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
,D/PMS     (  905): releaseWL(4413c1e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440f8fc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440eef28): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440b26b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440b26b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440eef28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4408d900): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,D/Ads     ( 4688): Skipping gmscore version check
,D/PMS     (  905): releaseWL(440f8fc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/Finsky  ( 4688): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4688): [1] Libraries$2.run: Finished loading 1 libraries.
,D/PMS     (  905): releaseWL(4408d900): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Finsky  ( 4688): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PMS     (  905): acquireWL(4405a978): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4688): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4688): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/PMS     (  905): releaseWL(4405a978): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4422
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4422:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1963): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4422
,D/PMS     (  905): acquireWL(43eb3c48): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1963): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 516 ms] updated apps [took 516 ms] 
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b6fd38 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b6fd38 -
,I/Icing   ( 1963): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/PhoneApp( 1221): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1221): -- N1 =0
,D/PhoneApp( 1221): -- N2 =0
,D/PhoneApp( 1221): -- N3 =0
,D/Icing   ( 1963): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1963): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(43eb3c48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4662): mNeedToUpdateDate2 start
,D/MmsConfig( 4662): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4662): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4662): 
D/MmsAsyncWorkHandler( 4662): HM tk = 20001
,D/ReportIndicatorCache( 4662): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4662): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ae8148
,I/Messaging( 4662): mccmnc> 
D/DraftCache( 4662): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4662): [DraftCache/1] refresh
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
D/MmsConfig( 4662): networkCode: 
,D/Messaging( 4662): ViewCache CreatePreloadOnlyConversationList
D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4662): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4662): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4662): createReceiver
,D/MessageCustFlag( 4662): sense_version=6.0
D/Messaging( 4662): mNeedToUpdateDate2: false
,D/Jerry   ( 4662): start to preload cursor >>>>>>>
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1221):  phoneType = -1
D/TelephUtils( 1221): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,V/MmsProvider( 1221): Update uri=content://mms, match=0
,V/MmsProvider( 1221): selection=st=129 AND m_type!=134
D/Messaging( 4662): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4662): TransactionService is going to be woken up.
,V/TransactionService( 4662): 1-Creating TransactionService
V/TransactionService( 4662): onStartCommand: 1
,D/MmsSystemEventReceiver( 4662): unRegisterForConnectionStateChanges
V/TransactionService( 4662): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4662): Loading previous transactions.
D/Messaging( 4662): ViewCache CreatePreload
,D/Messaging( 4662): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1221): device_type: 1
,D/Cust_MMSMS( 4662): _has_set_default_values_2=true
D/TransactionService( 4662): Force set service start id to 1
V/TransactionService( 4662): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4662): unRegisterForConnectionStateChanges
,D/TransactionService( 4662): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4662): Destroying TransactionService
,D/MsgPreferenceUtils( 4662): def_index: 0
,V/TransactionService( 4662): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4662): globalIndex = 1
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/MmsSmsV2Provider( 1221):  phoneType = -1
D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MsgPreferenceUtils( 4662): phone state: true
D/MsgPreferenceUtils( 4662): sd state: false
,D/MsgPreferenceUtils( 4662): vIndex = 0
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1221): sku_id=99
,D/DraftCache( 4662): [DraftCache/457] rebuildCache
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/Jerry   ( 1221): URI_DRAFT
,D/Messaging( 4662): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/DraftCache( 4662): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4662): [DraftCache/457] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4662): 
D/MmsAsyncWorkHandler( 4662): HM tk = 20002
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1221): sku_id=99
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1221): sku_id=99
,I/GAV4    ( 4639): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  905): acquireWL(43c00808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c00808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43b73968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41bd4e08: PendingIntentRecord{424c41c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=137428, Int=0
,D/PMS     (  905): acquireWL(43b73148): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43b72fe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43b73968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): releaseWL(43b73148): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43b72fe0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4257f960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{43ff3a00: PendingIntentRecord{43f884c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138108, Int=0
,D/PMS     (  905): releaseWL(4257f960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/PMS     (  905): acquireWL(424a1910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/PMS     (  905): acquireWL(4261d258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(424a1910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1198): Scheduling Phenotype for one-off execution 11222 seconds from now (1450226399879)
,D/GetConfigurationSnapshotOperation( 1198): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/PMS     (  905): acquireWL(439cc618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(439cc618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PhenotypeFlagCommitter( 1198): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1198): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1198): [NET] getaddrinfo-, 1
,D/libc    ( 1198): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c06d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 146
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1198): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
D/libc    ( 1198): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1198): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [11][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=50 [2][1][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1198/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4261d258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(440e8548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/PMS     (  905): releaseWL(440e8548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c52bb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4006): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/PMS     (  905): releaseWL(43c52bb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4269): service - mHandler: update timezone
,D/AutoSetting( 4252): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4252): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4252): service - onCreate()
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4252): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4252): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4252): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4252): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4252): service - mHandler: update timezone
,D/AutoSetting( 4252): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4252): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4252): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4252): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1522): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1522): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1108): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41dec4d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.htc.htclocationservice 3 10 2 11
,D/AutoSetting( 4269): service - handleMessage() stop self
,D/AutoSetting( 4269): service - handleMessage() quit looper
,D/AutoSetting( 4269): service - onDestroy() END
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/PMS     (  905): acquireWL(43b69be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{420548c8: PendingIntentRecord{422eed98 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142825, Int=0
D/PMS     (  905): acquireWL(424d0f48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43b69be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ca11 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(424d0f48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4246f9e0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  905): acquireWL(440a4020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41bd4e08: PendingIntentRecord{424c41c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=167445, Int=0
,D/PMS     (  905): acquireWL(437b0488): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(440a4020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43095b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=5 [35][2][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4006): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42bb54c0): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/PMS     (  905): releaseWL(437b0488): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4006): nl80211: survey data missing!
E/wpa_supplicant( 4006): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4006): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43095b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(440da9b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(440da9b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425842f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(425842f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1963): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42646850): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25804, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 167901, reason: UserStart
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
D/PMS     (  905): releaseWL(42bb54c0): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): releaseWL(42646850): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(433d8898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1535/10029)
,D/PMS     (  905): releaseWL(433d8898): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1332): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4252): service - handleMessage() stop self
,D/AutoSetting( 4252): service - onDestroy() END
,D/AutoSetting( 4252): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4457
,I/ActivityManager(  905): Killing 4457:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4457
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(432a6e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(432a6e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(44184ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41bd4e08: PendingIntentRecord{424c41c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=197500, Int=0
,D/PMS     (  905): acquireWL(42650160): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(44184ad0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43230e18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42650160): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(43230e18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(438128e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438128e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(440b22f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(440b22f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 1343): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4262aac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(4262aac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(425d1208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425d1208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(431e8348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(431e8348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4256bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4256bfb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4379b958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=318754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4379b958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  905): killProcessQuiet, pid=3821
,I/ActivityManager(  905): Killing 3821:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3821
,D/PMS     (  905): acquireWL(43c07eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43c07eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42865750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42865750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(43c29678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=378754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c29678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42bfc680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42bfc680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4688): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4688): [NET] getaddrinfo-,err=8
D/libc    ( 4688): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4688): [NET] getaddrinfo-, 1
,D/libc    ( 4688): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =593 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4688): [NET] getaddrinfo_proxy-, success
,I/jxcore-log( 3900): Connected to the server!
I/jxcore-log( 3900): 
,I/chromium( 3900): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  905): acquireWL(437b7cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(437b7cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4409e4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=438753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4409e4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42bd3ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42bd3ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(436404f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436404f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(43c5f068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=498754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c5f068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42bfd5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42bfd5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(440ef380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(440ef380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4378a7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=558753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4378a7e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4355a770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4355a770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c318d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c318d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(4267dd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=618753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4267dd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1221): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1221): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1221): sku_id=99
D/ContactMessageStore( 1221): start background delete task...
,D/ContactMessageStore( 1221): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete
,D/PMS     (  905): acquireWL(43c81830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(43c81830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(434ccdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434ccdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43115920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=678753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43115920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(433bf878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(433bf878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43500030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43500030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(431d7880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=738754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(431d7880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4352bcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4352bcb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(435d4b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435d4b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43c88cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=798753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c88cd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(426cbac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426cbac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(435e9940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435e9940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43c3b2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=858754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c3b2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434ce310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(434ce310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43ff6c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=918753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43ff6c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4362e6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4362e6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4315c910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4315c910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c19528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=978753, Int=0
I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c19528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434aaef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434aaef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43fc7098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c9adb8: PendingIntentRecord{4246a010 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785317, Int=0
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{425847d0: PendingIntentRecord{43f19868 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1011054, Int=0
,D/PMS     (  905): acquireWL(42c45f18): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42c45f18): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4806 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{425688e0: PendingIntentRecord{425b4f10 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450226473328, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{4261e1d0: PendingIntentRecord{432c2e38 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450226931661, Int=0
,D/Finsky  ( 4688): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  905): sending alarm PendingIntent{423b8f30: PendingIntentRecord{4257dd00 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450227193646, Int=900000
W/dalvikvm( 4688): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  905): acquireWL(43c4bb98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4819 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1343/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1343/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/PMS     (  905): releaseWL(43c4bb98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4806/10049)
,W/ContextImpl( 4819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4819): call getInstance()
D/PMS     (  905): releaseWL(43fc7098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025388
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025516
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025576
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025583
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025591
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026867
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360026880
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029683
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360108019
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360115872
,D/libc    ( 4688): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4688): [NET] getaddrinfo-,err=8
D/libc    ( 4688): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4688): [NET] getaddrinfo-, 1
,D/libc    ( 4688): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f368 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4688): [NET] getaddrinfo_proxy-, success
,I/global  ( 4688): call createSocket() return a new socket.
D/libc    ( 4688): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4688): [NET] getaddrinfo-, SUCCESS
,D/PowerUsageList:PowerUsageHelper( 4819): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/libc    ( 4688): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4688): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(44184c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{425c8210: PendingIntentRecord{44151490 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450227272941, Int=0
,D/PMS     (  905): acquireWL(43512428): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4819 1000 null
,D/SmartSyncUtils( 4819): isEpsOn(), nState = 0
D/PMS     (  905): releaseWL(44184c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  905): releaseWL(43512428): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(44168fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4819 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4819): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4819): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4819): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4819): SettingOnTime = 1450245600000, randomSettingOnTime = 1450243298000
,D/SmartSyncScreenOnOffTimeReceiver( 4819): SettingOffTime = 1450231200000, randomSettingOffTime = 1450236249000
,D/SmartSyncScreenOnOffTimeReceiver( 4819): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4819): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4819): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(44168fa0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/NetworkManagementSocketTagger( 4688): untagSocket(73) failed with errno -22
,D/Finsky  ( 4688): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
W/BatSI   (  905): Couldn't get kernel wake lock stats
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/NetworkManagementSocketTagger( 4688): untagSocket(73) failed with errno -22
,D/Process (  905): killProcessQuiet, pid=3835
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3835:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3835
,D/WifiService(  905): Client connection lost with reason: 4
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/NetworkManagementSocketTagger( 4688): untagSocket(73) failed with errno -22
,D/Finsky  ( 4688): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
,D/Finsky  ( 4688): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4688/10074)
,D/Finsky  ( 4688): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4688): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  905): acquireWL(43966308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{41e80898: PendingIntentRecord{43965c98 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1450227276247, Int=0,
,D/PMS     (  905): acquireWL(440f9700): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4688 10074 null
,D/PMS     (  905): releaseWL(43966308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4688): [488] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1198): client connected with version: 8296000
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4688): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4688): [NET] getaddrinfo-,err=8
D/libc    ( 4688): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 4688): [NET] getaddrinfo-, 1
,D/libc    ( 4688): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8f17 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4688): [NET] getaddrinfo_proxy-, success
,D/PMS     (  905): releaseWL(440f9700): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/Process (  905): killProcessQuiet, pid=4480
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4480:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4480
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(433ca9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{41ea9568: PendingIntentRecord{42be1320 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450227289195, Int=0
,D/PMS     (  905): releaseWL(433ca9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4688): [479] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4688): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PMS     (  905): acquireWL(4329c990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(4329c990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43b9d598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1038753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43b9d598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4362c770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4362c770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(436410c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(436410c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42685850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1098753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42685850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43965610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43965610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43fd8630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43fd8630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43f26728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1158753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43f26728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4406c860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(4406c860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c84498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c84498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42b17df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1218754, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42b17df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43632050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/BatteryService(  905): n_update end
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(43632050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4408f010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4408f010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43fd0bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1278753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43fd0bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434fa910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434fa910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(433bc0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1338753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1249): Grow heap (frag case) to 12.683MB for 50416-byte allocation
,D/PMS     (  905): releaseWL(433bc0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(439c4d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=98
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderNotification, total:1
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 3947): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/PMS     (  905): releaseWL(439c4d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  905): batLight: plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c80000
D/qdlights(  905): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ContextImpl( 4819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(4405a0d0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/TetherSettings( 3310): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3310): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3310): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3310): Cust_ConnectToPC   : spcsc>false
D/        ( 3310): Cust_ConnectToPC   : IPT>true
,D/        ( 3310): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3310): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 3310): Index of the first 1 = -1
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/BatteryController( 1108): status:2 level:98 unsupport:false plugged:true
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1198): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.98, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  905): releaseWL(4405a0d0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3310): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3310): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3310): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3310): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): acquireWL(43413f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43413f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
D/PowerUI ( 1108): closing low battery warning: level=98
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1108): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43272b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1398753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43272b80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4376d4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4376d4a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43602c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43602c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=98
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(433cb3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(433cb3e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(431b8c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1458753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(431b8c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43142410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43142410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4364c718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1518753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4364c718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43ac9f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43ac9f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=99
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  905): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,D/PMS     (  905): acquireWL(43545708): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1198): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.99, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  905): releaseWL(43545708): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/BatteryController( 1108): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426af6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426af6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43157328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1578753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43157328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43273520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43273520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43a950d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1638753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43a950d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43c11b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43c11b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42bd6e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1698753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42bd6e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4413cc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4413cc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/DotMatrix( 1522): [EventService] reorderNotification, total:0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 3947): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,D/PMS     (  905): acquireWL(440192f8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,D/TetherSettings( 3310): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3310): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3310): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3310): Cust_ConnectToPC   : spcsc>false
D/        ( 3310): Cust_ConnectToPC   : IPT>true
,D/        ( 3310): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3310): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3310): Index of the first 1 = -1
,W/ctxmgr  ( 1198): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1198): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(440192f8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3310): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3310): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3310): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3310): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3310): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/PMS     (  905): acquireWL(43563520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43563520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1522): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1522): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e4c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1758753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e4c698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(441ad360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(441ad360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(44151990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1818753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  905): Prepared write state in 41ms
,D/PMS     (  905): releaseWL(44151990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-16-28.bin
,D/PMS     (  905): acquireWL(43901098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43901098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(438ff360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{42342038: PendingIntentRecord{42062f08 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1878753, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(438ff360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/CustomizationManager( 4865): ====startRecUseTime====
D/htc.customization.log.level( 4865):  is 
W/CustomizationLogLevel( 4865): Level value is invalid, use default level 2
D/CustomizationManager( 4865):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4865): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4865): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4865): Parsing tag category name = system
I/CustomizationCIDLoader( 4865): Parsing tag category name = application
I/CustomizationCIDLoader( 4865): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4865): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4865): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4865): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4865): Parsing tag category name = Settings
D/CustomizationManager( 4865):  Read CID file spent 0.159 (s)
D/CustomizationManager( 4865):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4865): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4865): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4865): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4865): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4865, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=3900
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 3900:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42471bb8 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  905): Copying FileAsset 0x677ada10 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  905): WIN DEATH: Window{432ade30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
W/PackageSettings(  905): Skipping PackageSetting{42167668 com.example.hello/10397} due to missing metadata
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3900 uid 10389
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1522): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1522): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1522): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(42583b78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(42583b78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1249): Deferring update until onResume
D/Launcher( 1249): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1264): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  905):   Scheme: "sms"
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/[PluginManager]RegisterService( 4269): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4269): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
E/cutils-trace( 4865): Error opening trace file: No such file or directory (2)
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4882 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  905): acquireWL(43c86818): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43c86818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43c1e7d8): PARTIAL_WAKE_LOCK  Icing 0x1 1963 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 320 ms] updated apps [took 320 ms] 
E/SQLiteDatabase( 4882): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4882): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4882): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4882): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4882): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4882): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4882): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4882): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4882): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4882): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4882): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4882): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4882): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4882): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4882): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4882): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4882): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4882): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4882): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4882): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4882): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4882): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4882): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4882): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4882): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4882): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4882): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4882): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4882): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4882): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4882): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4882): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4882): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4882): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4882): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4882): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4882): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4882): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4882): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4882): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4882): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4882): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4882): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4882): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4882): threadid=11: thread exiting with uncaught exception (group=0x416ade30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4882): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4882): Process: com.google.android.apps.docs, PID: 4882
E/AndroidRuntime( 4882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4882): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4882): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4882): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4882): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4882): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4882): 	at aho.run(AbstractDatabaseInstance.java:455)
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
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4900 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4882): killProcess, pid=4882
D/Process ( 4882): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 4882
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4882) has died.
W/ContextImpl( 4900): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4913 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4900): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4900): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4900): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4900): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4900): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4900): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4900): threadid=10: thread exiting with uncaught exception (group=0x416ade30)
E/AndroidRuntime( 4900): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4900): Process: com.android.keychain, PID: 4900
E/AndroidRuntime( 4900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4900): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4900): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4900): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4900): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4900): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4913): getInstance(Context context)
D/AppTag  ( 4913): getInstance(Context context)
D/Process ( 4900): killProcess, pid=4900
D/Process ( 4900): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450228172090.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4913): onCreate()
I/ActivityManager(  905): Recipient 4900
I/ActivityManager(  905): Process com.android.keychain (pid 4900) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(425643e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3548 10160 null
D/PMS     (  905): releaseWL(425643e8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4688): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1963): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
I/ActivityManager(  905): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1963): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1963): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1963): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1963): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65ff5678
E/SQLiteDBG( 1963): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65f40a38
W/PackageManager(  905): Unable to load service info ResolveInfo{42be1130 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/dalvikvm( 1963): threadid=48: thread exiting with uncaught exception (group=0x416ade30)
E/DriveAsyncService( 1963): disk I/O error (code 3850)
E/DriveAsyncService( 1963): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1963): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1963): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1963): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1963): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1963): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1963): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1963): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 1963): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1963): Process: com.google.android.gms, PID: 1963
E/AndroidRuntime( 1963): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1963): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1963): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1963): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1963): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1963): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1963): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1963): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1963): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1963): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1963): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1963): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 1963): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1963): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1963): killProcess, pid=1963
E/SQLiteOpenHelper( 1963): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1963): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1963): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41b6fd38 +
I/Prism.WidgetManager( 1249): onLoadItems() +
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 1963
I/ActivityManager(  905): Process com.google.android.gms (pid 1963) has died.
D/PMS     (  905): handleWLDeath(43c1e7d8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10998ms
I/ActivityManager(  905): Resuming delayed broadcast
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10994ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
D/PMS     (  905): acquireWL(423bf0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c9adb8: PendingIntentRecord{4246a010 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1731081, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{41e85100: PendingIntentRecord{425a1c08 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1822332, Int=1800000
V/AlarmManager(  905): sending alarm PendingIntent{4267e7d8: PendingIntentRecord{439456b0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849847, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{43fe1bb8: PendingIntentRecord{439790b8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1864905, Int=0
E/SQLiteLog( 1343): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1343): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5c9eb5f0
V/AlarmManager(  905): sending alarm PendingIntent{440ee868: PendingIntentRecord{43f19868 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1911152, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{423b8f30: PendingIntentRecord{4257dd00 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450228093646, Int=900000
W/dalvikvm( 1343): threadid=1: thread exiting with uncaught exception (group=0x416ade30)
V/AlarmManager(  905): sending alarm PendingIntent{42305fc0: PendingIntentRecord{43953be0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450228110239, Int=1800000
E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1343): FATAL EXCEPTION: main
E/AndroidRuntime( 1343): Process: com.google.process.gapps, PID: 1343
E/AndroidRuntime( 1343): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1343): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1343): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1343): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1343): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1343): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1343): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1343): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1343): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1343): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1343): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1343): 	... 10 more
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4943 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1343): killProcess, pid=1343
D/Process ( 1343): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 4943): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4943 dbg=false s=true

```
