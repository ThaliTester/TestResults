#### Test 55613145ac448d4_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Finsky  ( 3723): [386] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3723): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/Process (  905): killProcessQuiet, pid=3473
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  905): Killing 3473:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3473
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3473): Died!
,E/cutils-trace( 4048): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4048): ====startRecUseTime====
D/htc.customization.log.level( 4048):  is 
W/CustomizationLogLevel( 4048): Level value is invalid, use default level 2
D/CustomizationManager( 4048):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4048): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4048): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4048): Parsing tag category name = system
I/CustomizationCIDLoader( 4048): Parsing tag category name = application
I/CustomizationCIDLoader( 4048): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4048): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4048): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4048): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4048): Parsing tag category name = Settings
D/CustomizationManager( 4048):  Read CID file spent 0.115 (s)
D/CustomizationManager( 4048):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 4048): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4048): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4048): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4048): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4048
D/PMS     (  905): acquireHCC(41be1360): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(41b318d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x69c62d00 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1113498000
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421e0858
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
D/PMS     (  905): acquireWL(4247b1d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4059 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4059): Copying FileAsset 0x5c725428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1248): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4059): Binding Chromium to main looper Looper (main, tid 1) {41aa2268}
I/LibraryLoader( 4059): Expected native library version number "",actual native library version number ""
I/chromium( 4059): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4059): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4232ae48:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4059): 1101757600: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): acquireWL(423c67b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): acquireWL(42373d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  905): releaseWL(423c67b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4059): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4059): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4059): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4059): Local Branch: 
I/Adreno-EGL( 4059): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4059): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4059):                  aa63bbd948f41d15fc72f585e
W/chromium( 4059): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4059): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4059): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4059): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4059): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4059): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4059): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4059): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4059): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4059): CordovaWebView is running on device made by: HTC
,W/AwContents( 4059): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +273ms
I/InputMethodManagerService(  905): Disable input method client, pid=1248
,I/InputMethodManagerService(  905): Enable input method client, pid=4059
W/ResourceType( 4059): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4059): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae9228, mServedView=org.apache.cordova.engine.SystemWebView{41aaefb8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 4059): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  905): releaseWL(4247b1d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4059): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4059): JniHelper::setJavaVM(0x41574048), pthread_self() = 1662230336
,D/JX-Cordova( 4059): jxcore cordova android initializing
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 11.600MB for 95956-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 11.680MB for 143930-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 11.793MB for 215890-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 11.969MB for 323830-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 12.234MB for 485740-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 13.241MB for 1092904-byte allocation
,I/SensorManager(  905): mEventCount = 900
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 14.142MB for 1639352-byte allocation
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 15.469MB for 2459024-byte allocation
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(41be1360): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(41b318d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,V/LightsService(  905): setLight #0: color=#3d
,V/LightsService(  905): setLight #0: color=#39
,I/dalvikvm-heap( 4059): Grow heap (frag case) to 17.507MB for 3688532-byte allocation
,V/LightsService(  905): setLight #0: color=#33
,V/LightsService(  905): setLight #0: color=#2c
,V/LightsService(  905): setLight #0: color=#25
,V/LightsService(  905): setLight #0: color=#1f
,V/LightsService(  905): setLight #0: color=#18
,W/jxcore-log( 4059): Initializing JXcore engine
,W/jxcore-log( 4059): JXcore engine is ready
,V/LightsService(  905): setLight #0: color=#14
,W/jxcore-log( 4059): Starting JXcore engine
,W/jxcore-log( 4059): Platform android
W/jxcore-log( 4059): 
,W/jxcore-log( 4059): Process ARCH arm
W/jxcore-log( 4059): 
,D/PMS     (  905): releaseWL(42373d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4059): JXcore Cordova bridge is ready!
I/jxcore-log( 4059): 
,W/jxcore-log( 4059): JXcore engine is started
,I/chromium( 4059): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4059): Toggling radios to true
I/jxcore-log( 4059): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): checking for enable restriction...
,D/BluetoothManagerService(  905): checkBTEasState, ret=true
,I/BluetoothManagerService(  905): isBluetoothRestricted(): false
D/BluetoothManagerService(  905): enable(): region ID = 6
,D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
,W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1317
W/Settings:Agent(  905): Process.myUid(): 1000
,W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 8(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 4059): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: true pid=4059, uid=10389
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1337
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
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4105 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 4059): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 4059): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/PMS     (  905): acquireWL(43693a90): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,I/jxcore-log( 4059): Radios toggled
I/jxcore-log( 4059): 
,I/jxcore-log( 4059): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4059): 
,D/AdapterServiceConfig( 4105): Adding HeadsetService
D/AdapterServiceConfig( 4105): Adding A2dpService
D/AdapterServiceConfig( 4105): Adding HidService
D/AdapterServiceConfig( 4105): Adding HealthService
D/AdapterServiceConfig( 4105): Adding PanService
,D/AdapterServiceConfig( 4105): Adding GattService
,W/linker  ( 4105): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 4105): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4406aba0:true
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 4105): make
,I/BluetoothAdapterState( 4105): Entering OffState
,I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 4105): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapter( 4105): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41abab78
,D/BluetoothAdapter( 4105): onBluetoothServiceUp done
,D/BluetoothAdapter( 1106): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c3e8c8
,D/BluetoothAdapter( 1106): onBluetoothServiceUp done
,D/BluetoothAdapter( 1196): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41be9050
,D/BluetoothAdapter( 1196): onBluetoothServiceUp done
,D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42417ac0
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
D/BluetoothAdapter( 1217): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c5c3a0
,D/BluetoothAdapter( 1217): onBluetoothServiceUp done
,D/BluetoothAdapter( 4059): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425fdaf8
,D/BluetoothAdapter( 4059): onBluetoothServiceUp done
,D/BluetoothAdapter( 1230): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bcf168
,D/BluetoothAdapter( 1230): onBluetoothServiceUp done
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 4105): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 4105): Setting state to 11
I/BluetoothAdapterState( 4105): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 4105): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 4105): make
,I/IntentController( 1106): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 4105): StableState(): Entering Off State
D/PMS     (  905): acquireWL(440d5bb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1196 10029 null
,D/HeadsetService( 4105): Received start request. Starting profile...
D/HeadsetStateMachine( 4105): Version 1.6
,D/HeadsetStateMachine( 4105): make
D/PMS     (  905): releaseWL(440d5bb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4131 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 4105): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 4105): setCurrentDevice, the latest mCurrentDevice is:null
,I/QuickSettingBluetooth( 1106): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpService( 4105): Received start request. Starting profile...
,V/Avrcp   ( 4105): make
,D/Avrcp   ( 4105): fillIntentFilter()
,D/A2dpStateMachine( 4105): make
,D/HtcBtWidget_BTWidgetProvider( 4131): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4131): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3852
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/A2dpStateMachine( 4105): Enter Disconnected: -2
,D/HidService( 4105): Received start request. Starting profile...
,D/HealthService( 4105): Received start request. Starting profile...
,I/ActivityManager(  905): Killing 3852:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PanService( 4105): Received start request. Starting profile...
D/BluetoothTethering(  905): supplyMessenger
D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
,D/PanService( 4105): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BtGatt.DebugUtils( 4105): handleDebugAction() action=null
D/BtGatt.GattService( 4105): Received start request. Starting profile...
,D/BtGatt.GattService( 4105): start()
I/ActivityManager(  905): Recipient 3852
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
V/BluetoothPbapService( 4105): Pbap Service onCreate
V/BluetoothPbapService( 4105): Starting PBAP service
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 11
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 11
E/BluetoothMasService( 4105): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 4105): Add permission for SmsProvider.
V/BluetoothMasService( 4105): Starting MAS instances
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 11
I/MailMessageReceiver( 4105): reg:com.android.bluetooth.btservice.AdapterApp@41aae0e0 with com.htc.util.mail.MailMessageReceiver@41aee648
I/MailManager( 4105): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41aee648
V/EmailUtils( 4105): Manager Instance is not NULL
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=4151 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  905): interfaceAdded wlan0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): interfaceAdded p2p0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/PMS     (  905): releaseWL(43693a90): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 4105): ============NULL aList========
,V/EmailUtils( 4105): <-getEmailAccountIdList
,V/BluetoothMasService( 4105): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 11
V/BluetoothMasService( 4105): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4105): Manager Instance is not NULL
D/EmailUtils( 4105): ============NULL aList========
,V/EmailUtils( 4105): <-getEmailAccountIdList
V/BluetoothSapService( 4105): Sap Service onCreate
,V/BluetoothSapService( 4105): initBinder
V/BluetoothSapService( 4105): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41af3a38
,V/BluetoothSapReceiver( 4105): BluetoothSapReceiver init
,D/BluetoothSapService( 4105): setSapService()
V/BluetoothSapService( 4105): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 4105): state: 12
,D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 11
D/BluetoothAdapterService( 4105): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4105): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4105): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 4105): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 4105): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterService( 4105): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetPhoneState( 4105): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterState( 4105): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  905): killProcessQuiet, pid=3455
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 4105): Bluetooth STATE CHANGED to 11
I/ActivityManager(  905): Killing 3455:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/qcom-bluetooth( 4169): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4171 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4187): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4188): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4190): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4171): Received state change = 11
,I/qcom-bluetooth( 4191): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4192): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4193): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  905): New client listening to asynchronous messages
,I/wpa_supplicant( 4197): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4197): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4197): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4197): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4197): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4197): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4197): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4197): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4197): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4197): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4197): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4197): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4197): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4197): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4197): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4197): update_config=1
D/wpa_supplicant( 4197): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4197): device_name='Android_1950'
D/wpa_supplicant( 4197): manufacturer='HTC'
D/wpa_supplicant( 4197): model_name='HTC_PHONE'
D/wpa_supplicant( 4197): model_number='1234'
D/wpa_supplicant( 4197): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4197): p2p_oper_reg_class=126
D/wpa_supplicant( 4197): p2p_oper_channel=36
D/wpa_supplicant( 4197): p2p_ssid_postfix='-Android_1950'
,D/wpa_supplicant( 4197): persistent_reconnect=1
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4197): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4197): nl80211: RFKILL status not available
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4197): nl80211: Using driver-based roaming
D/wpa_supplicant( 4197): nl80211: TDLS supported
D/wpa_supplicant( 4197): nl80211: TDLS external setup
D/wpa_supplicant( 4197): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4197): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4197): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4197): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4197): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4197): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4197): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8c6b758
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c6b758
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4197): htc_wext_command_init +
E/wpa_supplicant( 4197): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4197): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4197): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4197): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4197): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4197): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4197): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4197): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Process (  905): killProcessQuiet, pid=3766
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 2367): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  905): Killing 3766:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3455
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/IntentController( 1106): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1106): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  905): Recipient 3766
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4199 uid=10050 gids={50050}
,D/HtcWiFiWidget_WiFiWidgetProvider( 4199): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4199): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=3887
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  905): Killing 3887:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/QuickSettingWifi( 1106): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3887
,I/wpa_supplicant( 4197): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4197):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4197):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4197):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): nl80211: Flush PMKIDs
E/wpa_supplicant( 4197): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4197): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4211): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4212): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 4105): btu_task pending for preload complete event
,D/wpa_supplicant( 4197): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4197): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4197): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4197): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4197): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): Using existing control interface directory.
D/wpa_supplicant( 4197): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4197): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
D/wpa_supplicant( 4197): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4197): P2P: Own listen channel: 1
D/wpa_supplicant( 4197): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4197): P2P: Add operating class 81
I/wpa_supplicant( 4197): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4197): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4197): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4197): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4197): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4197): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4197): disable_scan_offload=1
D/wpa_supplicant( 4197): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4197): update_config=1
D/wpa_supplicant( 4197): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4197): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4197): manufacturer='HTC'
D/wpa_supplicant( 4197): model_name='HTC Desire 820'
D/wpa_supplicant( 4197): model_number='HTC Desire 820'
D/wpa_supplicant( 4197): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4197): persistent_reconnect=1
D/wpa_supplicant( 4197): p2p_disabled=1
D/wpa_supplicant( 4197): hs20=1
D/wpa_supplicant( 4197): interworking=1
D/wpa_supplicant( 4197): Line: 18 - start of a new network block
D/wpa_supplicant( 4197): key_mgmt: 0x2
D/wpa_supplicant( 4197): priority=1 (0x1)
,D/wpa_supplicant( 4197): signinfail=0 (0x0),
,D/wpa_supplicant( 4197): Priority group 1
D/wpa_supplicant( 4197):    id=0 ssid='NG700'
I/wpa_supplicant( 4197): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4197): nl80211: RFKILL status not available
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4197): nl80211: Using driver-based roaming
D/wpa_supplicant( 4197): nl80211: TDLS supported
D/wpa_supplicant( 4197): nl80211: TDLS external setup
D/wpa_supplicant( 4197): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4197): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4197): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4197): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4197): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4197): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4197): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8c7b718
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4197): htc_wext_command_init +
I/wpa_supplicant( 4197): htc_wext_command_init -
I/wpa_supplicant( 4197): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4197): Don't set 00 to countryID.conf
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4197): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4197): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4197): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4197): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4197): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4197): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4197): nl80211: Added 802.11b mode based on 802.11g information,
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false,
,I/wpa_supplicant( 4197): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4197):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4197):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4197):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4197): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4197): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4197): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4197): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4197): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4197): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4197): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4197): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4197): Using existing control interface directory.
,I/wpa_supplicant( 4197): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4197): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10,
I/wpa_supplicant( 4197): Auto country group 1: ch36
I/wpa_supplicant( 4197): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING - ret = 0
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  905): Regulatory Country Code:DE
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
D/wpa_supplicant( 4197): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4197): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4197): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4197): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4197): nl80211: Event message available
D/wpa_supplicant( 4197): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4197): nl80211: Regulatory domain change
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4197): nl80211: 2400-2483 @ 40 MHz,
D/wpa_supplicant( 4197): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4197): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4197): P2P: Add operating class 81,
D/wpa_supplicant( 4197): P2P: Add operating class 115
D/wpa_supplicant( 4197): P2P: Add operating class 116
D/wpa_supplicant( 4197): P2P: Add operating class 117
D/wpa_supplicant( 4197): P2P: Update channel list
D/wpa_supplicant( 4197): p2p0: Updating hw mode
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 95,
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4197): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4197): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4197): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4197): nl80211: 5470-5725 @ 80 MHz
,D/wpa_supplicant( 4197): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4197): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): set wifi ON
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  905): Loading config and enabling all networks
D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): list_network_info: ret=0x1, pos=0xb8c7e117 buf=0xb8c7e0e8
,I/wpa_supplicant( 4197): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4197): 0	NG700	any	
D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'bssid'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'as_cert_file'
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4197): Do not allow key_data field to be exposed
,I/IntentController( 1106): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/HtcWiFiWidget_WiFiWidgetProvider( 4199): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4199): updateWidget(context) for widget: 
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/WIFI_ICON( 1106): updateWifiState: WIFI_STATE_CHANGED enabled
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
I/wpa_supplicant( 4197): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4197): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4197): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4197): wpa_supplicant_trigger_scan +
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4197): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/wpa_supplicant( 4197): nl80211: Event message available
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4197): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4197): R,ecv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4197): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4197): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4197): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4197): manufacturer='HTC'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4197): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4197): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4197): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4197): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): SET_SCREEN_ON:On
I/wpa_supplicant( 4197): htc_wext_set_keepalive +
I/wpa_supplicant( 4197): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4197): getPrivFuncNum +	
I/wpa_supplicant( 4197): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4197): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): SETBAND: 0
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4197): P2P: Add operating class 81
D/wpa_supplicant( 4197): P2P: Add operating class 115
D/wpa_supplicant( 4197): P2P: Add operating class 116
D/wpa_supplicant( 4197): P2P: Add operating class 117
D/wpa_supplicant( 4197): P2P: Update channel list
I/wpa_supplicant( 4197): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4197): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4197): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4197): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4197): p2p_oper_reg_class=126
D/wpa_supplicant( 4197): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4197): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4197): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4197): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4197): p2p_oper_channel=36
E/wpa_supplicant( 4197): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4197): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4197): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4197): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4197): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4197): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4197): persistent_reconnect=1
I/wpa_supplicant( 4197): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_1950
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4197): device_name='Android_1950'
I/wpa_supplicant( 4197): Recv Cmd 2: SET device_name=Android_1950
I/QuickSettingWifi( 1106): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4197): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4197): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4197): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4197): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4197): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4197): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4197): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4197): Single channel concurrency preference: sta
I/wpa_supplicant( 4197): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
D/WifiP2pService(  905): P2pEnabledState
D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4197): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4197): P2P: Stopping find
D/wpa_supplicant( 4197): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4197): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4197): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4197): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4197): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4197): list_network_info: ret=0x22, pos=0xb8c7e10a buf=0xb8c7e0e8
I/wpa_supplicant( 4197): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4197): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  905):    returned false
D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4197): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4197): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4197): WFD: Update WFD IE
I/wpa_supplicant( 4197): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4197): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4197): WFD: Set subelement 0
D/wpa_supplicant( 4197): WFD: Update WFD IE
I/wpa_supplicant( 4197): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4197): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  905):    returned true
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
D/WifiDisplayController(  905):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  905):  WFD CtrlPort: 0
D/WifiDisplayController(  905):  WFD MaxThroughput: 0
D/WifiP2pService(  905): sending p2p persistent groups changed broadcast
D/WifiP2pService(  905): InactiveState
D/WifiP2pService(  905): InactiveState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-11ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  905): Successfully set WFD info.
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
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
,D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
,D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4197): nl80211: Event message available
D/wpa_supplicant( 4197): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4197): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4197): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 4197): nl80211: Survey data missing
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4197): Sorted scan results
I/wpa_supplicant( 4197): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 4197): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 4197): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 4197): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-79
I/wpa_supplicant( 4197): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 4197): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 4197): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 4197): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4197): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4197): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4197): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4197): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4197): Add randomness: count=7 entropy=5
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4197): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4197): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4197): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4197): wpa_supplicant_pick_network+
I/wpa_supplicant( 4197): Selecting BSS from priority group 1
I/wpa_supplicant( 4197): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4197): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4197): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4197): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4197): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4197):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4197):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 4197): Start print parameters
I/wpa_supplicant( 4197): wpa_s->wpa_state is 3
I/wpa_supplicant( 4197): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4197): isConcurrentMode() is 0
I/wpa_supplicant( 4197): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4197): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4197): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4197): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4197): wpa_s->reassociate is 0
I/wpa_supplicant( 4197): wpa_s->is_screen_on 1
I/wpa_supplicant( 4197): wpa_s->ifname wlan0
I/wpa_supplicant( 4197): End print parameters
I/wpa_supplicant( 4197): selected network = 2
D/wpa_supplicant( 4197): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid,: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8c7c4e8  current_ssid=0x0
D/wpa_supplicant( 4197): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4197): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4197): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4197): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4197): check if in concurrent case
,I/wpa_supplicant( 4197): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4197): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4197): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4197): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4197): RSN: PMKSA cache search - network_ctx=0xb8c7c4e8 try_opportunistic=0
D/wpa_supplicant( 4197): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4197): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4197): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4197): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4197): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4197): nl80211: Unsubscribe mgmt frames handle 0xb8c7b718 (mode change)
D/wpa_supplicant( 4197): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8c7b718
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718,
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Register frame type=0xd0 nl_handle=0xb8c7b718
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4197): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4197):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4197):   * freq=2412
D/wpa_supplicant( 4197):   * Auth Type 0
D/wpa_supplicant( 4197):   * WPA Versions 0x2
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4197): nl80211: Connect request send successfully
D/wpa_supplicant( 4197): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4197): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4197): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4197): reply (779) for get BSS: id=0
I/wpa_supplicant( 4197): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4197): freq=5220
I/wpa_supplicant( 4197): level=-48
I/wpa_supplicant( 4197): tsf=0000000102671076
I/wpa_supplicant( 4197): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4197): ssid=NG7005g
I/wpa_supplicant( 4197): ====
I/wpa_supplicant( 4197): id=1
I/wpa_supplicant( 4197): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4197): freq=2412
I/wpa_supplicant( 4197): level=-55
I/wpa_supplicant( 4197): tsf=0000000102671087
I/wpa_supplicant( 4197): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4197): ssid=01ABC
I/wpa_supplicant( 4197): ====
I/wpa_supplicant( 4197): id=2
I/wpa_supplicant( 4197): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4197): freq=2412
I/wpa_supplicant( 4197): level=-55
I/wpa_supplicant( 4197): tsf=0000000102671091
I/wpa_supplicant( 4197): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4197): ssid=NG700
I/wpa_supplicant( 4197): ====
I/wpa_supplicant( 4197): id=3
I/wpa_supplicant( 4197): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4197): freq=2452
I/wpa_supplicant( 4197): level=-79
I/wpa_supplicant( 4197): tsf=0000000102671096
I/wpa_supplicant( 4197): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4197): ssid=Gonzos
I/wpa_supplicant( 4197): ====
I/wpa_supplicant( 4197): id=4
I/wpa_supplicant( 4197): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 4197): freq=2437
I/wpa_supplicant( 4197): level=-89
I/wpa_supplicant( 4197): tsf=0000000102671103
I/wpa_supplicant( 4197): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4197): ssid=UPC5999698
I/wpa_supplicant( 4197): ====
I/wpa_supplicant( 4197): id=5
I/wpa_supplicant( 4197): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 4197): freq=2437
I/wpa_supplicant( 4197): level=-90
I/wpa_supplicant( 4197): tsf=0000000102671100
I/wpa_supplicant( 4197): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 4197): ssid=UPC Wi-Free
I/wpa_supplicant( 4197): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
D/WifiStateMachine(  905): == (6) end of scan result ==
,D/WifiManager( 1196): getScanResults enter 
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (6) end of scan result ==
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 102671076, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 102671087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 102671091, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2452, timestamp: 102671096, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 102671103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 102671100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 6 to mScanResults
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/bt-btu  ( 4105): btu_task received preload complete event
,D/bt-btm  ( 4105): btm_acl_device_down
D/bt-btm  ( 4105): btm_acl_reset_paging
,D/bt-btm  ( 4105): btm_acl_set_discing
,I/bt-btm  ( 4105): btm_reset_complete
,I/bt-btm  ( 4105): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 4105): Start reading local supported commands
,D/bt-btm  ( 4105): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 4105): BTM reads next extended features page (1)
,D/bt-btm  ( 4105): BTM reads next extended features page (2)
D/bt-btm  ( 4105): BTM reached last extended features page (2)
,D/bt-btm  ( 4105): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 4105): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 4105): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 4105): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 4105): btm_read_ble_wl_size 
D/bt-btm  ( 4105): btm_read_white_list_size_complete 
,D/bt-btm  ( 4105): btm_get_ble_buffer_size 
D/bt-btm  ( 4105): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 4105): btm_read_ble_local_supported_features 
D/bt-btm  ( 4105): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 4105): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 4105): btm_decode_ext_features_page page: 0
D/bt-btm  ( 4105): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 4105): Local supported SCO packet types: 0x038f
D/bt-btm  ( 4105): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 4105): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 4105): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 4105): BTM_SetInquiryMode
I/bt-btm  ( 4105): BTM_SetPageScanType
I/bt-btm  ( 4105): BTM_SetInquiryScanType
D/bt-btm  ( 4105): btm_decode_ext_features_page page: 1
D/bt-btm  ( 4105): btm_decode_ext_features_page page: 2
D/bt-btm  ( 4105): BTM_BleLoadLocalKeys
D/bt-btm  ( 4105): BTM_BleLoadLocalKeys
I/bt-btm  ( 4105): BTM_Sec: application registered
E/bt-btm  ( 4105): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f59941 
I/bt-btm  ( 4105): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 4105): SMP_Register state=0
E/bt-btm  ( 4105): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f59941 
I/bt-btm  ( 4105): BTM_Sec: application registered
D/bt-btm  ( 4105): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 4105): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 4105): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 4105): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 4105): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 4105): BTM_RegBusyLevelNotif
I/bt-att  ( 4105): GATT_Register
D/bt-att  ( 4105): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 4105): allocated gatt_if=3
I/bt-att  ( 4105): GATT_StartIf gatt_if=3
D/bt-att  ( 4105): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 4105): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
,E/bt-btif ( 4105): Calling BTA_HhEnable
E/bt-btif ( 4105): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 4105): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:2 len:6
I/bt-btm  ( 4105): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 4105): BTM_AllocateSCN
D/BluetoothAdapterProperties( 4105): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:1 len:14
,I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 4105): BTM_AllocateSCN
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btm  ( 4105): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4105):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 4105):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 4105): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 4105): A2D_AddRecord uuid: 110a
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
D/bt-avp  ( 4105): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 4105): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btm  ( 4105): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 4105):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm , ( 4105): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 08:ec:a9:50:75:41
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: f8:cf:c5:d9:e5:61
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 4105): BTM_GetHCIConnHandle
I/bt-btm  ( 4105): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 4105): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 4105): GATT_Register
D/bt-att  ( 4105): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 4105): allocated gatt_if=4
I/bt-att  ( 4105): GATT_StartIf gatt_if=4
D/bt-att  ( 4105): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 4105): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 4105): Scan Mode:20
I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 4105): Discoverable Timeout:120
I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:8 len:60
,D/BluetoothAdapter( 4105): getBluetoothService(): entry
D/BluetoothAdapter( 4105): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 4105): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41afe940
,D/BluetoothDevice( 4105): getService : Register callback
,D/BluetoothAdapterProperties( 4105): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 4105): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 4105): Adding bonded device:14:B4:84:21:3B:49
,D/BluetoothAdapterProperties( 4105): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 4105): Adding bonded device:08:EC:A9:50:75:41
,D/BluetoothAdapterProperties( 4105): Adding bonded device:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 4105): Adding bonded device:7C:F9:0E:34:8A:A0
,D/BluetoothAdapterProperties( 4105): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 4105): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 4105): Adding bonded device:38:94:96:B5:06:DC
,I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
D/wpa_supplicant( 4197): EAPOL: disable timer tick
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4197): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4197): nl80211: Event message available
D/wpa_supplicant( 4197): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4197): nl80211: Connect event
D/wpa_supplicant( 4197): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4197): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4197): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4197): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4197): Add randomness: count=8 entropy=6
I/wpa_supplicant( 4197): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4197): TDLS: Remove peers on association
D/wpa_supplicant( 4197): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4197): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4197): htc_wext_set_keepalive +
I/wpa_supplicant( 4197): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4197): getPrivFuncNum +	
I/wpa_supplicant( 4197): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Associated
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 4105): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 4105): Remote class is:5898764
,I/bt-btif ( 4105): BTA_JvEnable
I/bt-btm  ( 4105): BTM_ReadConnectability
I/bt-btm  ( 4105): BTM_ReadDiscoverability
I/bt-btm  ( 4105): BTM_SetDiscoverability
I/bt-btm  ( 4105): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 4105): br_edr_supported=0x2
I/bt-btm  ( 4105): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4105): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 4105): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4105): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4105): BTM_SetConnectability
I/bt-btm  ( 4105): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4105): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 4105): BTM_SetDiscoverability
I/bt-btm  ( 4105): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 4105): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 4105): br_edr_supported=0x0
I/bt-btm  ( 4105): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4105): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4105): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 4105): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4105): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 4105): BTM_SetConnectability
I/bt-btm  ( 4105): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4105): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 4105): bta_pan_co_init
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 4105): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4105):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 4105):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 4105): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4105):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4105): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 4105):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
,I/bt-btm  ( 4105): Write Extended Inquiry Response to controller,
,E/bt_mct  ( 4105): hci lib postload completed,
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btif ( 4105): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 4105): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4105): ScanMode =  20
D/BluetoothAdapterProperties( 4105): State =  11,
I/bt-btm  ( 4105): BTM_SetDiscoverability
I/bt-btm  ( 4105): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/BluetoothAdapterProperties( 4105): Setting state to 12
I/BluetoothAdapterState( 4105): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 4105): Broadcasting updateAdapterState() to 1 receivers.
D/bt-btm  ( 4105): btm_ble_set_discoverability (BREDR not sup)flag=0x4
I/bt-btif ( 4105): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-btm  ( 4105): br_edr_supported=0x0
,I/bt-btm  ( 4105): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 4105): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 4105): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 4105): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 4105): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 4105): BTM_SetConnectability
I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 4105): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 4105): new flag=0x0 cur flag=0x4
D/bt-btm  ( 4105): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 4105): btm_ble_update_adv_flag old=0x4
,I/bt-btm  ( 4105): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 4105): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 4105): Entering On State
,D/BluetoothAdapterProperties( 4105): Scan Mode:21
I/bt-btif ( 4105): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 4105): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 4105): Discoverable Timeout:120
D/BluetoothAdapterService(1101758472)( 4105): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4105): getBondedDevices: length=10
,D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1217): Proxy object connected
,D/BluetoothA2dp(  905): Proxy object connected
,D/BluetoothHeadset( 1217): Proxy object connected
D/BluetoothPhoneService( 1217): BluetoothHeadset onServiceConnected
,D/BluetoothAdapter(  905): 1111624248: getState(). Returning 12
,D/BluetoothAdapter( 1217): 1103065632: getState(). Returning 12
,D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1106): onBluetoothStateChange: up=true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1106): Proxy object connected
I/QuickSettingMiniLite( 1106): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41dae7b0
,D/BluetoothPan(  905): BluetoothPAN Proxy object connected
,D/BluetoothHeadset(  905): Proxy object connected
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1106): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothAdapter(  905): 1111624248: getState(). Returning 12
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/PMS     (  905): acquireWL(43f81b00): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1196 10029 null
,V/BluetoothPbapReceiver( 4105): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 4105): ***********state = 12
,D/BluetoothMasReceiver( 4105): Bluetooth STATE CHANGED to 12
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,V/BluetoothSapReceiver( 4105): SapReceiver onReceive 
V/BluetoothSapReceiver( 4105): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 4105):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 4105): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1101758472)( 4105): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 4105): getBondedDevices: length=10
,D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 12
D/PMS     (  905): releaseWL(43f81b00): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  905): acquireWL(425d27c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3421 1000 null
W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  905): releaseWL(425d27c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 4131): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4131): updateWidget(context) for widget: 
W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43932728:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 12
V/BluetoothMasService( 4105): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 4105): Manager Instance is not NULL
,I/LocationAgent( 3421): new LocationAgent instance!!
,D/PMS     (  905): acquireWL(438dab98): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3421 1000 null
D/HtcTagManager( 3421): HtcTagManager construction complete
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
D/BluetoothInputDevice( 3421): BluetoothInputDevice()
D/EmailUtils( 4105): ============NULL aList========
V/EmailUtils( 4105): <-getEmailAccountIdList
D/BluetoothManagerService(  905): registerStateChangeCallback+
V/BluetoothSapService( 4105): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 4105): state: 12
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 12
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
D/BluetoothInputDevice( 3421): BluetoothInputDevice(): Binding service...
W/ContextImpl( 4105): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/BluetoothManagerService(  905): Registered receivers: 7
,V/BluetoothSapService( 4105): Starting SAP server process
,V/BluetoothPbapService( 4105): Handler(): got msg=1
,V/BluetoothPbapService( 4105): Pbap Service startRfcommSocketListener
,D/BluetoothPan( 3421): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,V/BluetoothPbapService( 4105): Pbap Service initSocket
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  905): Registered receivers: 8
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
,D/BluetoothPan( 3421): BluetoothPan(): Binding service...
W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/BluetoothMap( 3421): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothAdapter( 4105): getBluetoothService(): entry
W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothMap( 3421): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  905): Registered receivers: 9
E/BluetoothServiceJni( 4105): SOCK FLAG = 1 ***********************
I/bt-btif ( 4105): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 4105):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 4105): Succeed to create listening socket 
V/BluetoothPbapService( 4105): Accepting socket connection...
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3421): BluetoothSap() call bindService
D/BluetoothManagerService(  905): Registered receivers: 10
V/BluetoothMasService( 4105): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 4105): BluetoothMns: isEmailEnabled: true
,D/BluetoothMasService( 4105): Map_prev 1
,W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 1106): 1104454928: getState(). Returning 12
D/BluetoothPbap( 3421): BluetoothPbap()
D/BluetoothAdapter( 1106): 1104454928: getState(). Returning 12
I/QuickSettingBluetooth( 1106): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1106): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothAdapter( 4105): getBluetoothService(): entry
W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 11
E/BluetoothServiceJni( 4105): SOCK FLAG = 3 ***********************
I/bt-btif ( 4105): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
D/BluetoothPbap( 3421): BluetoothPbap(): Binding service...
I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 4105):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 4105): getBluetoothService(): entry
D/BluetoothA2dp( 3421): BluetoothA2dp()
,W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 12
E/BluetoothServiceJni( 4105): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4105): BTA_JvCreateRecordByUser
,W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 4105):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
,D/BluetoothA2dp( 3421): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 3421): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
,D/BluetoothHeadset( 3421): BluetoothHeadset(): Binding service...
,D/BluetoothSapService( 4105): Sap_prev 1
,V/BluetoothSapService( 4105): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 4105): Sap Service initRfcommSocket
,D/HtcTagManager( 3421): startProxy
W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/ContextImpl( 3421): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
D/BluetoothAdapter( 4105): getBluetoothService(): entry
,W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3421): LocalBluetoothProfileManager construction complete
E/BluetoothServiceJni( 4105): SOCK FLAG = 3 ***********************
,I/bt-btif ( 4105): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
,I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 4105):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 4105): Succeed to create listening socket 
,V/BluetoothSapService( 4105): Accepting socket connection...
,W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/DockEventReceiver( 3421): finishStartingService: stopping service
D/BluetoothPan( 3421): BluetoothPAN Proxy object connected
D/PanProfile( 3421): Bluetooth service connected
D/BluetoothA2dp( 3421): Proxy object connected
D/A2dpProfile( 3421): Bluetooth service connected
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
V/TAG     ( 4105): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 4105): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41af5178
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4171): onCreate: going to find gatt base service first.
V/BluetoothPbapService( 4105): Pbap Service onBind
D/BluetoothHeadset( 3421): Proxy object connected
D/HeadsetProfile( 3421): Bluetooth service connected
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
D/BluetoothInputDevice( 3421): Proxy object connected
D/HidProfile( 3421): Bluetooth service connected
D/BluetoothAdapter( 1106): 1104454928: getState(). Returning 12
D/BluetoothAdapter( 3421): 1103335568: getState(). Returning 12
,I/QuickSettingMiniLite( 1106): updateLiteState:no connect device!
D/SapServerProfile( 3421): Bluetooth service connected
D/BluetoothPbap( 3421): Proxy object connected
,D/PbapServerProfile( 3421): Bluetooth service connected
,I/BluetoothFtpService( 4105): Ftp Service onCreate
,D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 12
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/PMS     (  905): releaseWL(438dab98): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423be8e8:true
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMasReceiver( 4105): Bluetooth STATE CHANGED to 12
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4105): getBluetoothService(): entry
W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothFtpService( 4105): Ftp_prev 1
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/BluetoothServiceJni( 4105): SOCK FLAG = 0 ***********************
I/bt-btif ( 4105): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 4105):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 4105): Accept thread started.
D/BluetoothAdapter( 4105): getBluetoothService(): entry
W/BluetoothAdapter( 4105): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 4105): SOCK FLAG = 1 ***********************
I/bt-btif ( 4105): BTA_JvCreateRecordByUser
D/bt-sdp  ( 4105): SDP_CreateRecord ok, num_records:16
D/[HTC_BLE][Constants]( 4171):  + defaultServices = 0
I/bt-btm  ( 4105): Write Extended Inquiry Response to controller
I/bt-btif ( 4105): BTA_JvRfcommStartServer
I/bt-btm  ( 4105): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 4105):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 4105): Run Accept thread
D/[HTC_BLE][Constants]( 4171):  + enableOnBonded = false
D/BluetoothAdapter( 4105): 1101776648: getState(). Returning 12
V/BluetoothMasService( 4105): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 4105): Manager Instance is not NULL
D/[HTC_BLE][Constants]( 4171):  + discoverServicesOnBonded = false
,D/EmailUtils( 4105): ============NULL aList========
,V/EmailUtils( 4105): <-getEmailAccountIdList
,D/BluetoothMasService( 4105): Map_prev 1
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4171):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4171): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab3190
D/[HTC_BLE][Constants]( 4171): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4171): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4171): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4171): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4171): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4171): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4171): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4171): Received state change = 12
,D/HtcTagManager( 3421): onServiceConnected
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4171): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4171): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab3190
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4171): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab3190
,D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4171): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab3190, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abe178
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4171): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab3190
,D/HtcTagProfile( 3421): setup proxy
D/HtcPxpProfile( 3421): setup proxy
,D/HtcFmpProfile( 3421): setup proxy
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42418890:true
,I/LocationAgent( 4002): new LocationAgent instance!!
,D/HtcTagManager( 4002): HtcTagManager construction complete
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothInputDevice( 4002): BluetoothInputDevice()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothInputDevice( 4002): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  905): Registered receivers: 14
,D/BluetoothPan( 4002): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 15
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothPan( 4002): BluetoothPan(): Binding service...
W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,D/BluetoothMap( 4002): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 16
,E/BluetoothMap( 4002): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothSap( 4002): BluetoothSap() call bindService
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 17
,D/BluetoothPbap( 4002): BluetoothPbap()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 18
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothPbap( 4002): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 4002): BluetoothA2dp()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 19
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothA2dp( 4002): BluetoothA2dp(): Binding service...
,D/BluetoothHeadset( 4002): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 20
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothHeadset( 4002): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 4002): startProxy
,W/ContextImpl( 4002): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 4002): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/LocalBluetoothProfileManager( 4002): setBluetoothStateOn
W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
D/HtcTagManager( 4002): startProxy
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
D/BluetoothAdapterService(1101758472)( 4105): Get Bonded Devices being called
D/BluetoothAdapterProperties( 4105): getBondedDevices: length=10
D/BluetoothAdapter( 4002): getBluetoothService(): entry
D/BluetoothAdapter( 4002): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 4002): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41af8678
D/BluetoothDevice( 4002): getService : Register callback
E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
D/wpa_supplicant( 4197): EAPOL: startWhen --> 0
D/wpa_supplicant( 4197): EAPOL: disable timer tick
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4197): EAPOL: enable timer tick
D/wpa_supplicant( 4197): EAPOL: txStart
,D/wpa_supplicant( 4197): WPA: drop TX EAPOL in non-IEEE 802.1X mode (type=1 len=0)
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/RingtoneManager( 4171): getExternalStorageState=mounted
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[-1]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[1]: Daisy
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[3]: Foxglove
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[12]: Tulip
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + Available RingingTone[14]: Wisteria
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4171):  + mAlertUri: content://settings/system/alarm_alert
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4171): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4171): Enter IdleState
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4171): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4171): initScanModeInterface: true
W/System.err(  905): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4406b648:true
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4171): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4171):  + mTag.getPrimaryDeviceList() = []
,D/HtcTagManager( 4002): addHtcTagProfiles
D/[HTC_BLE][Constants]( 4171):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4171):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4171):  + discoverServicesOnBonded = false
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4171): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abe178
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,E/BluetoothDevice( 4002): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): addHtcTagProfiles
,D/BluetoothInputDevice( 4002): Proxy object connected
D/HidProfile( 4002): Bluetooth service connected
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/AuthorizationBluetoothService( 2367): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2367): Proximity feature is not enabled.
D/BluetoothPan( 4002): BluetoothPAN Proxy object connected
,D/PanProfile( 4002): Bluetooth service connected
D/SapServerProfile( 4002): Bluetooth service connected
D/BluetoothPbap( 4002): Proxy object connected
D/PbapServerProfile( 4002): Bluetooth service connected
D/BluetoothA2dp( 4002): Proxy object connected
,D/A2dpProfile( 4002): Bluetooth service connected
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/BluetoothHeadset( 4002): Proxy object connected
,D/HeadsetProfile( 4002): Bluetooth service connected
,D/BluetoothAdapter( 4002): 1101787008: getState(). Returning 12
,D/HtcTagManager( 4002): onServiceConnected
D/HtcTagProfile( 4002): setup proxy
D/HtcPxpProfile( 4002): setup proxy
,D/HtcFmpProfile( 4002): setup proxy
,I/wpa_supplicant( 4197): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 4197): Get randomness: len=32 entropy=7
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 4197): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8c7b9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4197):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 10
D/WifiStateMachine(  905): This record is existed, only update it...
D/wpa_supplicant( 4197): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4197): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed8b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 4197):    broadcast key
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4197): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4197): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4197): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4197): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4197): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4197): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4197): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4197): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4197): set send_ind_to_ndc = 0
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4197): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4197): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4197): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4197): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4197): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4197): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4197): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4197): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4197): EAPOL authentication completed successfully
I/wpa_supplicant( 4197): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4197): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4197): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4197): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
,D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/IntentController( 1106): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1106): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WISPrService( 3421): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3421): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  905): New client listening to asynchronous messages
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,D/DhcpStateMachine(  905): [StoppedState] Start DHCP
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4197): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4197): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): Power_Mode_Type mode = 1
I/wpa_supplicant( 4197): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET",
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(422bff60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425bd0e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425bd0e8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1106): receive.wifiConnect:false wifiAPname:null elapse:1
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422b70d8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422b70d8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41efda28
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@41f50158
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
,E/BTIF_CORE( 4105): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 4105): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 4105): Wake lock released
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): OOBE c monitor 11
I/IntentController( 1106): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1230): ScreenObserver: OFF
,D/NfcService( 1230): applyRouting - 0
D/NfcService( 1230): applyRouting -2
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4363c768)
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=4059
D/PMS     (  905): acquireWL(42bdb460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/PMS     (  905): releaseWL(42bdb460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): wakingUp
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
I/WindowManager(  905): No lock screen! windowToken=null
D/PMN     (  905): onScreenOn
D/PMS     (  905): acquireWL(43663d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
W/ActivityManager(  905): Disable JIT of com.htc.bgp
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(43663d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2046): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2046): [MTP][onReceive]-
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4258 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/NfcService( 1230): applyRouting - 0
,D/NfcService( 1230): applyRouting -2
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): acquireWL(435a71a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1230 1027 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(435a71a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): SET_SCREEN_ON:On
I/wpa_supplicant( 4197): htc_wext_set_keepalive +
I/wpa_supplicant( 4197): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4197): getPrivFuncNum +	
I/wpa_supplicant( 4197): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive - ret = 0
,I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4197): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=100 [1][1][0]
,I/wpa_supplicant( 4197): Change stage from stage0 to stage3
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
I/ClockThread( 1106): stop update clock
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  905): updateScreenOn: false
,I/CalendarProvider2( 4258): Created com.android.providers.calendar.CalendarAlarmManager@41ad6a90(com.android.providers.calendar.HtcCalendarProvider@41abee18)
,D/CalendarProvider2( 4258): wait start:true
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/CalendarProvider2( 4258): wait end:false
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4278 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  905): acquireWL(43690288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43690288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(44076210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  905): releaseWL(44076210): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4171): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4171): onScreenOn: 1452596493432
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4171): onScreenOn: 1452596493432
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41efda28
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41efda28, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@41f50158
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(4368d060): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
W/ContextImpl( 4278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20261 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): SET_SCREEN_ON:Off
I/wpa_supplicant( 4197): htc_wext_set_keepalive +
I/wpa_supplicant( 4197): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4197): getPrivFuncNum +	
I/wpa_supplicant( 4197): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4197): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4197): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 4197): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  905): acquireWL(42b5f8d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
D/PMS     (  905): releaseWL(42b5f8d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ContactMessageStore( 1217): start background delete task...
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1217): size: 0 , 0
D/ContactMessageStore( 1217): Background delete complete
,D/SmartSyncUtils( 4278): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(428a7290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4278 1000 null
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1319): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  905): releaseWL(428a7290): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/TetherSettings( 3421): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3421): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3421): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3421): Cust_ConnectToPC   : spcsc>false
D/        ( 3421): Cust_ConnectToPC   : IPT>true
D/        ( 3421): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3421): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3421): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3421): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3421): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1319): service - onCreate()
,I/ActivityManager(  905): Delay finish: com.android.settings/.NSReceiver
D/SmartSyncUtils( 4278): getMobilePolicyEnabled, result = true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/AutoSetting( 1319): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3421): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4197): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/SmartNS_PSService( 3421): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3421): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3421):  defaultType:0
I/ActivityManager(  905): Resuming delayed broadcast
W/ContextImpl( 3421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4197): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/PMS     (  905): releaseWL(422bff60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4197): WiFioffload: SignalStrength: =97
D/LocationManagerService(  905): request 42476100 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/WifiNative-wlan0(  905):    returned true
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4197): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 4197): htc_wext_set_keepalive +
I/wpa_supplicant( 4197): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4197): getPrivFuncNum +	
I/wpa_supplicant( 4197): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4197): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4197): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4197): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 4197): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
,D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1106): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/DotMatrix( 1520): [EventService] getTotalRam: 1873 Mb
,I/IntentController( 1106): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  905): WAN detection
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1106): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1106): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  905): acquireWL(425b7038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/PMS     (  905): releaseWL(425b7038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WISPrService( 3421): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43349038): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/MDST    (  905): default: setTeardownRequested(true)
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@42426638
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
W/ContextImpl( 4278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  905): releaseWL(43349038): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/SmartSyncUtils( 4278): isEpsOn(), nState = 0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/SmartSyncUtils( 4278): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4278): isEpsOn(), nState = 0
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
D/WifiService(  905): New client listening to asynchronous messages
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(4296bae0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f50158
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,I/QuickSettingWifi( 1106): receive.wifiConnect:true wifiAPname:NG700 elapse:1
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f50158, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41f50158, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4171): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4171): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4171): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4171): disableBatteryAlarm: null
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41f50158
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4171): onScreenOff
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4208fd90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4208fd90 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(4296bae0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{42591a90 u0 com.test.thalitest/.MainActivity t2}
,I/CalendarProvider2( 4258): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4258): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 3988): ---------------------------------------------------
,D/ProviderChangeReceiver( 3988): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3988): start to updateAlertNotification!
,W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3988): No fired or scheduled alerts
,D/HtcAlertUtils( 3988): -- cancelReminderNotification --
,D/HtcAlertUtils( 3988): broadcastExistReminder!
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4340 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,I/ConnectivityHelper( 1248): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/PMS     (  905): acquireWL(43fb9248): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1248/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1532/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b0b3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3918/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3496/10053)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3918/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43b101c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(44061b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/MusicStore( 4340): Database version: 95
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4340): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 104
D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): sen,d_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  905): acquireWL(438b26f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4340): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/PMS     (  905): acquireWL(44056a98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 905 1000 WorkSource{10029}
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(428afb08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
D/wpa_supplicant( 4197): nl80211: survey data missing!
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43849e18): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
D/wpa_supplicant( 4197): nl80211: survey data missing!
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,I/IntentController( 1106): receive(android.intent.action.TIME_SET,4,false)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1520): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/FeedActionBar( 1248): updateLastUpdatedTime(in String) LAST UPDATED 12:00
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1196): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1196): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/DotMatrix( 1520): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/PMS     (  905): acquireWL(425a5888): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
W/dalvikvm( 1196): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/dalvikvm( 1196): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/GoogleURLConnFactory( 1196): Using platform SSLCertificateSocketFactory
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(440a5570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4340): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4370 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  905): releaseWL(44061b58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  905): NTP server returned: 1452596491982 (Tue Jan 12 12:01:31 CET 2016) reference: 108697 certainty: 13 system time offset: -59
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43fb8a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(42467c80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/PMS     (  905): releaseWL(43fb8a30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(440fb2c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(440fb2c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(430aa830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  905): releaseWL(430aa830): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  905): releaseWL(43fb9248): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  905): releaseWL(43b101c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
D/PMS     (  905): acquireWL(43f86da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43f86da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1962): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 25015, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 108816, reason: UserStart
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43fe8708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43849e18): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/GamesSyncServiceMain( 1962): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1962): Failed to execute periodic sync, missing client context - aborting
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4340): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): releaseWL(440a5570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43b2f9a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4340): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/PhenotypeConfigurator( 1196): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4340, uid=10154, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1532/10029)
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
E/Auth.Api.Credentials( 1962): [CredentialSyncAdapter] Unknown sync event.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
D/PMS     (  905): releaseWL(43b2f9a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(44072e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/InstanceID/Rpc( 1196): Found 10029
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/MediaRouterService(  905): Client com.google.android.music (pid 4340): Registered
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/MediaRouter( 4340): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43fe8708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(432cfe50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(4384ed98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
W/dalvikvm( 1196): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4340/10154)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
I/NetworkMonitor( 4340): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4399 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(432cfe50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(44072e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4308cfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42d16e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/DelayedSyncController( 4370): Delaying sync.
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/PMS     (  905): releaseWL(42d16e08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4255e6a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/PMS     (  905): releaseWL(44056a98): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/MediaRouter( 4340): getSelectedRoute
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,I/NetworkMonitor( 4340): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4340/10154)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4340, uid=10154, userID:0
D/PMS     (  905): releaseWL(4308cfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1196): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1196): [NET] getaddrinfo-,err=8
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/libc    ( 1196): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1196): [NET] getaddrinfo-, 1
,D/libc    ( 1196): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET] +++++ res_nsend xid =ff1 +++++
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(423b4640): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 905 1000 WorkSource{10029}
,I/IntentController( 1106): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): releaseWL(4255e6a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(432af7c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/Process (  905): killProcessQuiet, pid=3918
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Killing 3918:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  905): releaseWL(42467c80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 3918
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 10183
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1196): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ACRA    ( 4399): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ACRA    ( 4399): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ACRA    ( 4399): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(438dc6c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(432af7c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43742b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/PhoneStatusBar( 1106): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/Process (  905): killProcessQuiet, pid=3938
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(425a5888): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  905): Killing 3938:com.htc.backup/1000 (adj 15): empty #17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
I/ActivityManager(  905): Recipient 3938
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43742b28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43162368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/SystemClassLoaderAdder( 4399): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0,
D/PMS     (  905): releaseWL(43162368): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4365fc18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
V/DexLibLoader( 4399): Preparing secondary program dexes.
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4399): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4399): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4399): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4399): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
V/DexLibLoader( 4399): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,W/DexLibLoader( 4399): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
V/DexLibLoader( 4399): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/DexLibLoader( 4399): Dex already copied
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/OdexVerifier( 4399): Odex verification is skipped.
,V/DexLibLoader( 4399): Creating class loader
D/PMS     (  905): releaseWL(4365fc18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43757fb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43757fb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4399): Finished creating class loader
V/DexLibLoader( 4399): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4399): Dex already copied
D/OdexVerifier( 4399): Odex verification is skipped.
V/DexLibLoader( 4399): Creating class loader
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4399): Finished creating class loader
V/DexLibLoader( 4399): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4399): Dex already copied
D/OdexVerifier( 4399): Odex verification is skipped.
V/DexLibLoader( 4399): Creating class loader
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: ,IFNAME=wlan0
W/DriveInitializer( 1962): Awaiting to be initialized
W/DriveInitializer( 1962): Background init thread started
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4399): Finished creating class loader
V/DexLibLoader( 4399): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4399): Dex already copied
D/OdexVerifier( 4399): Odex verification is skipped.
V/DexLibLoader( 4399): Creating class loader
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/DexLibLoader( 4399): Finished creating class loader
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4399): Verifying classes from secondary dexes.
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/DexLibLoader( 4399): DexLibLoader.ensureDexLoaded took 130 ms
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,I/PhenotypeConfigurator( 1196): Scheduling Phenotype for one-off execution 5843 seconds from now (1452596492716)
,D/GetConfigurationSnapshotOperation( 1196): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1962): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,W/DriveInitializer( 1962): Background init thread ended
,I/PhenotypeFlagCommitter( 1196): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,I/GoogleURLConnFactory( 1196): Using platform SSLCertificateSocketFactory
,D/libc    ( 1196): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1196): [NET] getaddrinfo-,err=8
D/libc    ( 1196): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1196): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43be61c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,I/Scheduler( 1196): Use legacy PeriodicScheduler
D/PMS     (  905): releaseWL(428afb08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [6][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): releaseWL(43be61c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43fb1148): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(423b4640): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
I/jxcore-log( 4059): Test app app.js loaded
I/jxcore-log( 4059): 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/Choreographer( 4059): Skipped 526 frames!  The application may be doing too much work on its main thread.
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNA,L_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(433d8c88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 905 1000 WorkSource{10029}
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(43fb1148): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42946c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(438dc6c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/ResourceType( 4059): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4059): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aaefb8 VFEDH.C. .F....ID 0,0-720,1134 #64}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/chromium( 4059): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(4368d060): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  905): acquireWL(42439850): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
D/PMS     (  905): releaseWL(42946c48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42892328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42892328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43636ee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43636ee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/DelayedSyncController( 4370): Delaying sync.
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(431c0340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42439850): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/PhenotypeConfigurator( 1196): Server returned 404
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(438b26f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42660d50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): acquireWL(440fb278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(431c0340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4264aaa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(433d8c88): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/PMS     (  905): acquireWL(42548420): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
D/PMS     (  905): releaseWL(4264aaa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4378e4b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/PMS     (  905): releaseWL(4378e4b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43f9b9c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43f9b9c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
D/PMS     (  905): releaseWL(440fb278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(437d1458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42c31658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42548420): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(437d1458): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43fc72c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 905 1000 WorkSource{10160}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42c31658): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43291e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43291e60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{423ab400: PendingIntentRecord{42b83f38 com.google.android.gms startService}}) : type=2 triggerAtTime=315360109907 win=-1 tElapsed=315360109907 maxElapsed=551880109906 interval=0 standalone=false
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4410d6e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,D/PMS     (  905): releaseWL(43fc72c0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4410d6e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/libc    ( 1196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1196): [NET] getaddrinfo-,err=8
D/libc    ( 1196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1196): [NET] getaddrinfo-, 1
D/libc    ( 1196): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b8c5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(440a1880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 245
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1196): [NET] getaddrinfo_proxy-, success
D/PMS     (  905): releaseWL(42660d50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/PMS     (  905): acquireWL(429f9e40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(440a1880): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(43fc5480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43fc5480): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(425bbf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(429f9e40): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1106): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(425bbf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    ( 1196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1196): [NET] getaddrinfo-,err=8
D/libc    ( 1196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1196): [NET] getaddrinfo-,err=8
,D/PhoneStatusBar( 1106): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 4399): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  905): acquireWL(43716cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(43f94940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43716cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43f94940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4292ab58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4292ab58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4399): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =134e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4399): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 16
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/104.81.130.175
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=33 [3][1][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1196/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,E/FbInjectorInitializer( 4399): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/PMS     (  905): releaseWL(4384ed98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(432631b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/PMS     (  905): releaseWL(432631b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43fe09a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/PMS     (  905): releaseWL(43fe09a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):StaticBindingVerifier( 4399): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4399): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4399): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  905): killProcessQuiet, pid=3956
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3956:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3956
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1319): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4460 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1319): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1319): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1319): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
,W/fb4a(:<default>):UserScope( 4399): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4399): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4399): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4460): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4460): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4460): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4460): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4460/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4460/10079)
,D/PMS     (  905): acquireWL(4373ff10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4474 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3905
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3905:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4460/10079)
,I/ActivityManager(  905): Recipient 3905
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(43238da0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452528229604 min interval config: 0 actual interval: 68264854
D/PMS     (  905): releaseWL(4373ff10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checking schedule, now: 1452596494466 next: 1452528259555
,I/CheckinService( 1962): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/CheckinService( 1962): Preparing to send checkin request
,I/EventLogService( 1962): Accumulating logs since 1452596434321
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,E/dalvikvm( 4399): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4399): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4399): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4399): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4399): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4399): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4399): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4399): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4399): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4399): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4399): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4399): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4399): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4399): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4399): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4399): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4399): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4399): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4474): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/WifiService(  905): New client listening to asynchronous messages
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4474): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 9.918MB for 39954-byte allocation
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 9.992MB for 79892-byte allocation
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 10.063MB for 84664-byte allocation
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 10.091MB for 28144-byte allocation
,D/PMS     (  905): acquireWL(4410d0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029}
,D/ContactMessageStore( 1217): notify MmsSms
D/AccFlag ( 1217): sense_version=6.0
,D/AccFlag ( 1217): sku_id=99
V/AlarmManager(  905): sending alarm PendingIntent{440fce70: PendingIntentRecord{441644b8 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  905): releaseWL(4410d0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1217): sku_id=99
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4474/10151)
,V/WebViewChromiumFactoryProvider( 4474): Binding Chromium to main looper Looper (main, tid 1) {41aa3270}
,I/LibraryLoader( 4474): Expected native library version number "",actual native library version number ""
,I/chromium( 4474): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,I/BrowserStartupController( 4474): Initializing chromium process, renderers=0
,D/AccFlag ( 1217): sku_id=99
,D/PMS     (  905): acquireWL(440d3e30): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4474): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(440a9df0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 10.255MB for 75760-byte allocation
D/PMS     (  905): releaseWL(440d3e30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4474): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4474): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4474): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4474): Local Branch: 
I/Adreno-EGL( 4474): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4474): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4474):                  aa63bbd948f41d15fc72f585e
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1217): sku_id=99
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c4d0f0 u0 ReceiverList{423c80e0 4399 com.facebook.katana/10027/u0 remote:425c1920}}
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
,D/AccFlag ( 1217): sku_id=99
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bc3b78 u0 ReceiverList{423c4ce8 4399 com.facebook.katana/10027/u0 remote:425a4cd8}}
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1962/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/NSApplication( 4474): Starting up...
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4474/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4474/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
D/PMS     (  905): acquireWL(43c536a0): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43c536a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/GLSActivity( 2367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,V/GLSActivity( 2367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(43bd4660): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3693/10160)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=3665
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3693/10160)
,I/ActivityManager(  905): Killing 3665:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42515410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42515410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,I/iu.SyncManager( 1962): SYNC; picasa accounts
D/libc    ( 2367): [NET] getaddrinfo-, 1
,D/libc    ( 2367): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b6ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/NetworkLogImpl( 1962): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 1962): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
I/iu.UploadsManager( 1962): num queued entries: 0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/iu.UploadsManager( 1962): num updated entries: 0
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/iu.SyncManager( 1962): NEXT; no task
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 293
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2367): [NET] getaddrinfo_proxy-, success
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4399): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  905): Recipient 3665
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4399): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4399): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
,D/AlertReceiver( 3988): beginStartingService
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/PMS     (  905): acquireWL(4406bed8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3988 10013 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/PMS     (  905): acquireWL(43c56be0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 2367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 2367): [NET] getaddrinfo-, 1
,D/libc    ( 2367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =df93 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/AlertService( 3988): start to updateAlertNotification!
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4534 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 199
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/AlertService( 3988): No fired or scheduled alerts
,D/HtcAlertUtils( 3988): -- cancelReminderNotification --
,D/libc    ( 2367): [NET] getaddrinfo_proxy-, success
,D/HtcAlertUtils( 3988): broadcastExistReminder!
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/WeatherRequest( 1106): request cur loc, but there is no sys cur
,D/PMS     (  905): releaseWL(4406bed8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3988): stopSelfResult true
,D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2367): [NET] getaddrinfo-, 1
,D/libc    ( 2367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =269a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2367): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
,D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/libc    ( 2367): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
,W/WeatherUtility( 4534): can't get weather sync account
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4550 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 4534): request cur loc, but there is no sys cur
,W/Settings( 4534): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/PMS     (  905): acquireWL(42687c98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4550 10071 null
,D/PMS     (  905): acquireWL(43661428): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4550 10071 null
I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 2 11 17
D/PMS     (  905): releaseWL(42687c98): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4565 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 4550): update TASK shortcut>
,D/libc    ( 2367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,I/TodoTaskNotifyService( 4550): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/GCM     ( 2367): GCM config loaded
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4,
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,I/TodoTaskNotifyService( 4550): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): releaseWL(43661428): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4550): stopSelfResult true
,I/WorldClock.Global( 4565): isHtcDevice = true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/Process (  905): killProcessQuiet, pid=3723
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=7 [26][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(433ce5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,I/ActivityManager(  905): Killing 3723:com.android.vending/u0a74 (adj 15): empty #17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4002): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/WorldClock.Global( 4565): isHtcDevice = true
I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4583 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 4565): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmUtils( 4565): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4565): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1106): receive(android.intent.action.ALARM_CHANGED,1,false)
D/PMS     (  905): acquireWL(440dda80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3723
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/PMS     (  905): acquireWL(430c84d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/TimeService( 4583): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452596495434
,D/Process (  905): killProcessQuiet, pid=4031
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  905): releaseWL(43c56be0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
I/ActivityManager(  905): Killing 4031:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2367/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/Process (  905): killProcessQuiet, pid=4199
,I/ActivityManager(  905): Killing 4199:com.htc.widget.process2/u0a50 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/VacuumService( 1196): Vacuum at: now=1452596495469 tag=VacuumService
I/ActivityManager(  905): Recipient 4031
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(436ace38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(436ace38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(440dda80): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452528229604 min interval config: 0 actual interval: 68265881
D/PMS     (  905): acquireWL(44091e60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2367/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  905): acquireWL(42bf9648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2367/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/PMS     (  905): acquireWL(43c56488): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1962 10029 null
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/PMS     (  905): acquireWL(43f81de8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430c84d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(44091e60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42bf9648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/PMS     (  905): releaseWL(43c56488): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  905): releaseWL(43f81de8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(433ce5e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43fc0820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Recipient 4199
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
D/PMS     (  905): releaseWL(43fc0820): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(43fc4528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
D/PMS     (  905): releaseWL(43fc4528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43789c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4604 uid=10041 gids={50041}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4616 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  905): releaseWL(43789c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=4131
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4131:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4131
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(425a3238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4616): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4616): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
I/MultiDex( 4616): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4616): install
,I/MultiDex( 4616): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/MultiDex( 4616): loading existing secondary dex files
,I/MultiDex( 4616): load found 3 secondary dex files
,I/MultiDex( 4616): install done
D/PMS     (  905): releaseWL(425a3238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(43fc4ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/PMS     (  905): acquireWL(428b4588): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4550 10071 null
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(425e9ec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4550 10071 null
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,W/dalvikvm( 4616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4616): VFY: unable to resolve instance field 36
,W/dalvikvm( 4616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PMS     (  905): acquireWL(430c89f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4550 10071 null
,D/PMS     (  905): releaseWL(428b4588): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.notification.NotifyReceiver
,I/ProviderInstaller( 4616): Installed default security provider GmsCore_OpenSSL
D/PMS     (  905): acquireWL(425e9ec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4550 10071 null
D/PMS     (  905): releaseWL(43fc4ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/TodoTaskNotifyService( 4550): java.lang.NullPointerException
,W/System.err( 4550): java.lang.NullPointerException
W/System.err( 4550): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4550): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4550): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): releaseWL(430c89f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  905): releaseWL(425e9ec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 4550): stopSelfResult false
E/TodoTaskNotifyService( 4550): java.lang.NullPointerException
W/System.err( 4550): java.lang.NullPointerException
W/System.err( 4550): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4550): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4550): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4550): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4550): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4550): mStartingService is null
I/ActivityManager(  905): Resuming delayed broadcast
,W/NotifyReceiver( 4550): stopSelfResult true
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4638 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/dalvikvm( 4616): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4616): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4616): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4616): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4616): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4616): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4616): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,I/Icing   ( 1962): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Babel   ( 4638): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4638): MmsConfig.loadMmsSettings
,W/dalvikvm( 4638): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4638): VFY: unable to resolve instance field 36
,W/dalvikvm( 4638): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,V/JNIHelp ( 4638): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4663 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/Icing   ( 1962): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
,D/NativeLibraryUtils( 4616): Install completed successfully. count=14 extracted=0
D/PMS     (  905): releaseWL(43bd4660): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4638, uid=10111, userID:0
,W/Settings( 4638): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4638, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4638, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4638, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4638, uid=10111, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4638, uid=10111, userID:0
,W/dalvikvm( 4616): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/MessageFrequencyProvider( 4663): onCreate
,W/dalvikvm( 4616): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4616): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/MmsCustomizationProvider( 4663): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/dalvikvm( 4616): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/GetPrviateResource( 4663): GetPrviateResource
,W/dalvikvm( 4616): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,V/GetPrviateResource( 4663): GetPrviateResource
,D/MmsCustomizationProvider( 4663): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/GoogleURLConnFactory( 4616): Using platform SSLCertificateSocketFactory
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3413949859
I/Babel   ( 4638): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4638): MmsConfig.loadFromDatabase
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,E/Babel   ( 4638): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4638): MmsConfig.loadFromResources
,E/Babel   ( 4638): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4638): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/libc    ( 4616): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4616): [NET] getaddrinfo-,err=8
D/libc    ( 4616): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4616): [NET] getaddrinfo-, 1
,D/libc    ( 4616): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =31b5 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/ProviderInstaller( 4638): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4638/10111)
,D/Process (  905): killProcessQuiet, pid=4151
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 4151:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4638/10111)
,I/ActivityManager(  905): Recipient 4151
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/MessageCustFlag( 4663): sense_version=6.0
,D/BTAccessoryUtil( 4663): createReceiver
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 289
D/libc    (  364): [NET]res_nsend:resplen=86
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4616): [NET] getaddrinfo_proxy-, success
D/BTAccessoryUtil( 4663): registerReceiver return intent = null
D/MessageCustFlag( 4663): sku_id=99
,W/SystemReader( 4663): Cannot find message_ambs_application_id, use default value instead
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Resuming delayed broadcast
D/Messaging( 4663): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4663): networkCode: 
,D/MessageCustFlag( 4663): sku_id=99
D/MmsConfig( 4663): SIE smsPri: null
D/MmsConfig( 4663): networkCode: 
,D/GCM     ( 2367): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/PMS     (  905): acquireWL(436b39d0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/HtcTelephonyCapability( 4663): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4663): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4663): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4663): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4688 uid=10078 gids={50078}
,D/Process (  905): killProcessQuiet, pid=3421
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3421:com.android.settings/1000 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
D/PMS     (  905): releaseWL(436b39d0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(436564b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/SMSBackup( 4688): Got a database change event
,I/ActivityManager(  905): Killing 4278:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=4278
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WearableService( 1196): callingUid 10029, callindPid: 1196
D/PMS     (  905): acquireWL(431d5860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,E/MDM     ( 1196): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Recipient 3421
D/LocationInitializer( 1962): Restart initialization of location
,D/PMS     (  905): releaseWL(436564b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/AuthorizationBluetoothService( 2367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2367): Proximity feature is not enabled.
I/ActivityManager(  905): Recipient 4278
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): releaseWL(431d5860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(41e0a3c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1196): No location to return for getLastLocation()
,W/FusedLocationProvider( 1196): location=null
D/PMS     (  905): acquireWL(4365fde0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4365fde0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
D/PMS     (  905): releaseWL(41e0a3c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 2367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    ( 4616): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4616): [NET] getaddrinfo-,err=8
D/libc    ( 4616): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4616): [NET] getaddrinfo-,err=8
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/libc    ( 4638): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4638): [NET] getaddrinfo-,err=8
D/libc    ( 4638): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4638): [NET] getaddrinfo-, 1
,D/libc    ( 4638): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3d1c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4638): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4638): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4638): [NET] getaddrinfo-,err=8
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1506747632
,D/PMS     (  905): acquireWL(424220a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10014}
,V/AlarmManager(  905): sending alarm PendingIntent{4202b0d0: PendingIntentRecord{432d6710 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=113742, Int=0
,D/PMS     (  905): acquireWL(436640b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4258 10014 null
,I/ActivityManager(  905): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/PMS     (  905): releaseWL(436640b8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/WVCdm   (  371): CdmEngine::CloseSession
D/PMS     (  905): releaseWL(424220a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,W/fb4a(:<default>):UserScope( 4399): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4399): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  905): acquireWL(4288b798): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4340 10154 null
,I/ActivityManager(  905): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=22 [50][11][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4340): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4340, uid=10154, userID:0
,D/PMS     (  905): releaseWL(4288b798): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4340): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4340): Conditions not met for autocaching.
,I/MusicLeanback( 4340): Stop autocaching.
I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/Process (  905): killProcessQuiet, pid=3496
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3496:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3496
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42639dd0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4638 10111 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4399): Called registerBroadcastReceiver twice.
,I/Babel   ( 4638): Account registration complete:Redacted-21
,D/PMS     (  905): releaseWL(42639dd0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/libc    ( 4399): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4399): [NET] getaddrinfo-,err=8
D/libc    ( 4399): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4399): [NET] getaddrinfo-, 1
,D/libc    ( 4399): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =251f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2
D/libc    (  364): [NET]res_nsend:resplen=74
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4399): [NET] getaddrinfo_proxy-, success
I/global  ( 4399): call createSocket() return a new socket.
D/libc    ( 4399): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4399): [NET] getaddrinfo-, SUCCESS
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 4399): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4399): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4399): Grow heap (frag case) to 10.988MB for 32784-byte allocation
,W/Settings( 4616): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  905): releaseWL(440a9df0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  905): acquireWL(441321e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4399 10027 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4616/10029)
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4399/10027)
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1962): [NET] getaddrinfo-, 1
D/libc    ( 1962): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =62cc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1962): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1962): Sending checkin request (12459 bytes)
,D/Messaging( 4663): mNeedToUpdateDate2 start
,D/MmsConfig( 4663): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4663): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4663): 
D/MmsAsyncWorkHandler( 4663): HM tk = 20001
,D/ReportIndicatorCache( 4663): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4663): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aa9498
,I/Messaging( 4663): mccmnc> 
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/DraftCache( 4663): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4663): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1217):  phoneType = -1
D/MmsConfig( 4663): networkCode: 
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4663): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4663): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4663): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4663): createReceiver
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1217): sku_id=99
,D/MessageCustFlag( 4663): sense_version=6.0
,D/Jerry   ( 4663): start to preload cursor >>>>>>>
,D/TelephUtils( 1217): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/DraftCache( 4663): [DraftCache/463] rebuildCache
V/MmsProvider( 1217): Update uri=content://mms, match=0
,V/MmsProvider( 1217): selection=st=129 AND m_type!=134
,D/Messaging( 4663): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4663): TransactionService is going to be woken up.
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4663): 1-Creating TransactionService
,V/TransactionService( 4663): onStartCommand: 1
,D/MmsSystemEventReceiver( 4663): unRegisterForConnectionStateChanges
V/TransactionService( 4663): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4663): Loading previous transactions.
,D/Messaging( 4663): mNeedToUpdateDate2: false
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4663): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1217):  phoneType = -1
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1217): device_type: 1
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/Jerry   ( 1217): URI_DRAFT
D/TransactionService( 4663): Force set service start id to 1
V/TransactionService( 4663): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4663): unRegisterForConnectionStateChanges
,D/TransactionService( 4663): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4663): Destroying TransactionService
D/Messaging( 4663): ViewCache CreatePreload
,D/Messaging( 4663): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4663): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/DraftCache( 4663): hasDraft() = false mNeedNotifyChange = true
,D/Cust_MMSMS( 4663): _has_set_default_values_2=true
D/DraftCache( 4663): [DraftCache/463] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4663): 
D/MmsAsyncWorkHandler( 4663): HM tk = 20002
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1217): sku_id=99
,D/MsgPreferenceUtils( 4663): def_index: 0
,D/MsgPreferenceUtils( 4663): globalIndex = 1
,D/MsgPreferenceUtils( 4663): phone state: true
D/MsgPreferenceUtils( 4663): sd state: false
,D/MsgPreferenceUtils( 4663): vIndex = 0
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1217): sku_id=99
,I/CheckinResponseProcessor( 1962): From server: 2 gservices updates and 0 deletes
,I/CertBlacklister(  905): Certificate blacklist changed, updating...
,I/CertBlacklister(  905): Certificate blacklist updated
,I/GservicesProvider( 2367): main difference update completed
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  905): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4767 uid=10016 gids={50016, 3003, 5012, 2001}
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4460/10079)
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4767): Update started
I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4767): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4767): Update started
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1962/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=22 [35][8][0]
,I/DownloadManager( 2046): Download 247 starting
D/PMS     (  905): acquireWL(4265c028): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2046 10021 WorkSource{10016}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
,I/ActivityManager(  905): Resuming delayed broadcast
,W/ActivityThread( 2046): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/UpdateRequestReceiver( 4767): Received malformed URL while handling Gservices.CHANGED_ACTION
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
E/UpdateRequestReceiver( 4767): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 4767): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4799 uid=10032 gids={50032, 3003, 5012}
D/Process (  905): killProcessQuiet, pid=4399
I/ActivityManager(  905): Killing 4399:com.facebook.katana/u0a27 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/libc    ( 2046): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2046): [NET] getaddrinfo-,err=8
D/libc    ( 2046): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2046): [NET] getaddrinfo-, 1
D/libc    ( 2046): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ab17 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 274
D/libc    (  364): [NET]res_nsend:resplen=49
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2046): [NET] getaddrinfo_proxy-, success
,I/DownloadManager( 2046): Download 248 starting
D/PMS     (  905): acquireWL(44135748): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2046 10021 WorkSource{10016}
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): Recipient 4399
D/WifiService(  905): Client connection lost with reason: 4
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): handleWLDeath(441321e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/libc    ( 2046): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2046): [NET] getaddrinfo-,err=8
D/libc    ( 2046): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2046): [NET] getaddrinfo-, 1
,D/libc    ( 2046): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e0b1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2046): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  905): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/CheckinTask( 1962): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1962): Checking schedule, now: 1452596499224 next: 1453119436202
,I/CheckinService( 1962): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,D/CheckinService( 1962): Recording last checkin time for package unspecified as 1452596499244
,I/DownloadManager( 2046): Ignoring Content-Length since Transfer-Encoding is also defined
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
D/PMS     (  905): acquireWL(4409ba38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4409ba38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4799, uid=10032, userID:0
D/PMS     (  905): releaseWL(43238da0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4799, uid=10032, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4799, uid=10032, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4799, uid=10032, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4799, uid=10032, userID:0
,D/PMS     (  905): acquireWL(43fb07e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43fb07e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=22 [9][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
,D/PMS     (  905): acquireWL(43b22b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43b22b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43b0eee0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43b0eee0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4397e1a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2046): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  905): releaseWL(4397e1a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4243a048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4243a048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(425e8f70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425e8f70): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4460
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DownloadManager( 2046): Download 248 finished with status SUCCESS
I/ActivityManager(  905): Killing 4460:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/PMS     (  905): releaseWL(44135748): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4460
,I/DownloadManager( 2046): Download 247 finished with status SUCCESS
I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4828 uid=10079 gids={50079, 3003, 5012}
D/PMS     (  905): releaseWL(4265c028): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/GAV2    ( 4474): Thread[GAThread,5,main]: No campaign data found.
,E/PhoneMonitor( 4828): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4828): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  905): killProcessQuiet, pid=4370
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
I/ActivityManager(  905): Killing 4370:com.android.chrome/u0a96 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4828/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4828/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4828/10079)
,I/Search.GservicesUpdateTask( 2662): Updating Gservices keys
D/PMS     (  905): acquireWL(425c6ba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42520c60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425c6ba0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452596499244 min interval config: 0 actual interval: 401
,I/CheckinService( 1962): Checking schedule, now: 1452596499671 next: 1452596529202
,I/CheckinService( 1962): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
D/PMS     (  905): releaseWL(42520c60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3693, uid=10160, userID:0
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
,I/dalvikvm-heap( 3693): Grow heap (frag case) to 13.625MB for 1821008-byte allocation
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=3693, uid=10160, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=3693, uid=10160, userID:0
,I/ActivityManager(  905): Recipient 4370
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ContactAccountLoggerTas( 2662): canRun() : Opted Out
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(440e8200): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(430aa4f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452596499244 min interval config: 0 actual interval: 1174
D/PMS     (  905): releaseWL(440e8200): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1962): Checking schedule, now: 1452596500426 next: 1452596529202
,I/CheckinService( 1962): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/SystemUpdateService( 1962): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1962): onCreate
D/PMS     (  905): acquireWL(43f9a738): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(430aa4f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 1962): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1962): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
I/SystemUpdateService( 1962): cancelUpdate (empty URL)
,I/SystemUpdateService( 1962): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/SystemUpdateService( 1962): onDestroy
D/PMS     (  905): releaseWL(43f9a738): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1319): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1319): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1319): service - requestNLP() NetworkLocationProvider not enabled
,E/DynamiteModule( 1962): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1962): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1962): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1962): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1962): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1962): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1962): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1962): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1962): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1962): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1962): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1962): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 1962): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 1962): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 1962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1962): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 1962): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 1962): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1962): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1962): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 1962): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 1962): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1962): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1962): Selected local version of com.google.android.gms.flags
,W/SQLiteConnectionPool( 1962): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  905): acquireWL(428678c0): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
,D/SystemEventReceiver( 1962): Received GSERVICES_CHANGED broadcast
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,I/OcrUtils( 1962): Updating ocr activity enabled=false
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1196, uid=10029, userID:0
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/GCM     ( 2367): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1962, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43be2560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/OcrModelManager( 1962): Updating downloaded model state (gservices changed)
,I/IntentController( 1106): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): acquireWL(42666bb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(43be2560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(428678c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=28 [7][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(43c55dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(43c55dd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1106): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(43ba4958): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42666bb8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1106): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(43ba4958): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/dalvikvm( 1196): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1196): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/PhoneStatusBar( 1106): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 1196): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  905): acquireWL(41d917e0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360118107
,W/AlarmManager(  905): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{41d6d2e8: PendingIntentRecord{428fa788 com.google.android.gms startService}}) : type=2 triggerAtTime=315360118107 win=-1 tElapsed=315360118107 maxElapsed=551880118106 interval=0 standalone=false
,I/GCoreUlr( 1196): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1196): DispatchingService.onCreate()
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/GCM     ( 2367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  905): acquireWL(430ef010): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/GCoreUlr( 1196): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(43b0ae60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(43b0ae60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ctxmgr  ( 1196): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,I/DownloadManager( 2046): Download 249 starting
D/PMS     (  905): acquireWL(4410d0d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2046 10021 WorkSource{10016}
D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2046): Ignoring Content-Length since Transfer-Encoding is also defined
,W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,W/ctxmgr  ( 1196): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1196): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  905): releaseWL(41d917e0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,D/GCM     ( 2367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  905): acquireWL(43bd2c80): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2046 10021 WorkSource{10016}
D/GCM     ( 2367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DownloadManager( 2046): Download 250 starting
D/ConnectivityService(  905): getAllNetworkInfo called by  (2046/10021)
,D/PMS     (  905): acquireWL(422cfb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
I/DownloadManager( 2046): Download 249 finished with status SUCCESS
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360118107
D/PMS     (  905): releaseWL(4410d0d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/PMS     (  905): releaseWL(422cfb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42a94640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
,I/DownloadManager( 2046): Ignoring Content-Length since Transfer-Encoding is also defined
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [9][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
I/GCoreUlr( 1196): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [1][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360118107
,D/PMS     (  905): acquireWL(425270e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1196): Unbound from all location providers
,I/GCoreUlr( 1196): Place inference reporting - stopped
D/PMS     (  905): releaseWL(430ef010): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/PMS     (  905): releaseWL(425270e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42a94640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=5 [20][1][0]
D/PMS     (  905): acquireWL(440a77a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2046/10021)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360118107
,I/GCoreUlr( 1196): DispatchingService.onDestroy()
,I/GCoreUlr( 1196): Stopping handler for UlrDispSvcFast
D/PMS     (  905): acquireWL(440fd3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(440a77a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1196): Unbound from all location providers
,I/GCoreUlr( 1196): Place inference reporting - stopped
D/PMS     (  905): releaseWL(440fd3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4767): Update downloaded, starting installation
,I/UpdateFetcherService( 4767): Started installation
I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
D/PMS     (  905): acquireWL(430fa4b0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(430fa4b0): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42698c98): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42698c98): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/DownloadManager( 2046): Download 250 finished with status SUCCESS
D/PMS     (  905): releaseWL(43bd2c80): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/ContextImpl( 4767): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/ActivityManager(  905): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
I/UpdateFetcherService( 4767): Update downloaded, starting installation
I/UpdateFetcherService( 4767): Started installation
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ConfigUpdateInstallReceiver(  905): Not installing, new version is <= current version
,I/GAV4    ( 4638): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4638, uid=10111, userID:0
,D/Process (  905): killProcessQuiet, pid=4474
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4474:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4474
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3988
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3988:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3988
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1248): AllAppsMgr addApps, already exist: ApplicationInfo(id=38, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Launcher( 1248): Deferring update until onResume
,D/Launcher( 1248): waitUntilResume // bindAppsUpdated
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/dalvikvm-heap( 1248): Grow heap (frag case) to 12.605MB for 53840-byte allocation
,W/Prism.AllAppsManager( 1248): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/dalvikvm-heap( 3693): Grow heap (frag case) to 15.338MB for 1821008-byte allocation
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1248): Deferring update until onResume
,D/Launcher( 1248): waitUntilResume // bindAppsUpdated
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/GAV2    ( 3693): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,I/dalvikvm-heap( 3693): Grow heap (frag case) to 17.081MB for 1821008-byte allocation
I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  905): acquireWL(43fcbe60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3693 10160 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/ActivityManager(  905): Resuming delayed broadcast
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4900 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  905): releaseWL(43fcbe60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/HtcFingerPrintQuickLaunchProvider( 4900): -onCreate()
,V/Settings:HtcSettingsApplication( 4900): [4900/4900] onCreate()
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  905):   Scheme: "mmsto"
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4916 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=4534
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 4534:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,W/PackageManager(  905): Unable to load service info ResolveInfo{428b3318 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/Settings:HtcWirelessFeatureFlags( 4900): id/is att sku: 99/false
,W/SystemReader( 4900): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4916, uid=10074, userID:0
I/ActivityManager(  905): Recipient 4534
,W/SystemReader( 4900): Cannot find support_harman, use default value instead
,W/SystemReader( 4900): Cannot find effect_manager_id, use default value instead
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Settings:HtcWrapHeaderInfo( 4900): no such activity!
,D/Finsky  ( 4916): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4900): The wrap header doesn't exist in header list.
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4916/10074)
,E/Settings:HtcWrapHeaderInfo( 4900): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4900): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]support         :false
,W/FingerprintManager( 4900): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4900): isSupportVoWifi: null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4900): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4916/10074)
,D/Finsky  ( 4916): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4916): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4916): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4916): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4916, uid=10074, userID:0
,D/Ads     ( 4916): Skipping gmscore version check
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4900): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4900): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4900): isSupportMusicChannel(): false
D/Finsky  ( 4916): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4916): [1] Libraries$2.run: Finished loading 1 libraries.
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4900): [supportHomeButton]support         :false
,D/Finsky  ( 4916): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/FingerprintManager( 4900): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4900): isSupportVoWifi: null
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 4900): Failed to find provider info for com.htc.vowifi
W/dalvikvm( 4916): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4916): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(438bf180): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4638 10111 null
,D/PMS     (  905): acquireWL(4280d080): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(438bf180): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  905): releaseWL(4280d080): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=4565
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4565:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1962, uid=10029, userID:0
,W/PackageManager(  905): Unable to load service info ResolveInfo{42b5c5c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
D/PMS     (  905): acquireWL(42c41be0): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/PMS     (  905): releaseWL(42c41be0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42bd6c90): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1196): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4565
,D/PMS     (  905): acquireWL(435d9848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(435d9848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(436fb010): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(436fb010): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43698288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43698288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428a4dd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428a4dd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{425c4630 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(44109dd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3693 10160 null
,D/PMS     (  905): releaseWL(44109dd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 1962): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 774 ms] updated apps [took 774 ms] 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1248): onLoadItems() -
,I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 -
,I/Icing   ( 1962): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 1962): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1962): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/Icing   ( 1962): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,I/Icing   ( 1962): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,D/PMS     (  905): releaseWL(42bd6c90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1248): onLoadItems() -
,I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 -
,W/PackageSettings(  905): Skipping PackageSetting{42180510 com.example.hello/10397} due to missing metadata
,D/PMS     (  905): acquireWL(426ab468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/PMS     (  905): releaseWL(426ab468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 4197): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4197): EAPOL: disable timer tick
,D/PMS     (  905): acquireWL(42574b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f7f148: PendingIntentRecord{41f85fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=136717, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42574b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(428ab758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42541438: PendingIntentRecord{428f9448 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137558, Int=0
,D/PMS     (  905): releaseWL(428ab758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2367/10029)
,D/PMS     (  905): acquireWL(42894470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d24db0: PendingIntentRecord{4248bb98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=138756, Int=0
,D/PMS     (  905): acquireWL(43569908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
D/PMS     (  905): releaseWL(42894470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(423c4c58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43569908): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(423c4c58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1319): service - mHandler: update timezone
,D/AutoSetting( 4258): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4258): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1319): service - handleMessage() stop self
,D/AutoSetting( 4258): service - onCreate()
,D/AutoSetting( 1319): service - handleMessage() quit looper
,D/AutoSetting( 1319): service - onDestroy() END
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4258): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4258): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4258): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4258): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4258): service - mHandler: update timezone
,D/AutoSetting( 4258): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4258): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4258): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4258): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1520): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1520): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1106): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41e174c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.htc.htclocationservice 2 13 4 11
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(434d84e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{424ea568: PendingIntentRecord{424ea180 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141732, Int=0
D/PMS     (  905): acquireWL(438ff860): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
V/AlarmManager(  905): sending alarm PendingIntent{42c32028: PendingIntentRecord{42a68500 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452596529202, Int=522937000
,D/PMS     (  905): acquireWL(426683e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(434d84e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7e07 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452596499244 min interval config: 0 actual interval: 29996
D/PMS     (  905): acquireWL(430fa518): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426683e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1962): Checking schedule, now: 1452596529245 next: 1452596529202
,I/CheckinService( 1962): active receiver: enabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/CheckinService( 1962): Preparing to send checkin request
,I/EventLogService( 1962): Accumulating logs since 1452596494508
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,I/CheckinRequestBuilder( 1962): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1962/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=10 [10][1][0]
,V/GLSActivity( 2367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=546943392
,I/WVCdm   (  371): CdmEngine::CloseSession
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1858146151
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4616): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4616): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4616): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4616): Local Branch: 
I/Adreno-EGL( 4616): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4616): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4616):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4616): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4616/10029)
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1962): [NET] getaddrinfo-,err=8
D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1962): [NET] getaddrinfo-, 1
,D/libc    ( 1962): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =202 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1962): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
,D/libc    ( 1962): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1962): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1962): Sending checkin request (12253 bytes)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/CheckinRequestBuilder( 1962): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  905): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1962/10029)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=2 [47][1][0]
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,I/CheckinTask( 1962): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1962): Checking schedule, now: 1452596532057 next: 1453119469047
,I/CheckinService( 1962): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024491
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024704
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024708
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024711
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024713
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025965
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025981
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360029093
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360109907
,D/CheckinService( 1962): Recording last checkin time for package unspecified as 1452596532088
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360118107
,D/PMS     (  905): releaseWL(430fa518): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
,D/GCM     ( 2367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): releaseWL(438ff860): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(43757fb0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4638 10111 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
W/Prism.AllAppsManager( 1248): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{4403d0b8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/Launcher( 1248): Deferring update until onResume
D/Launcher( 1248): waitUntilResume // bindAppsUpdated
,D/PMS     (  905): releaseWL(43757fb0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(437180a0): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43fcb180): PARTIAL_WAKE_LOCK  AsyncService 0x1 3693 10160 null
,D/PMS     (  905): releaseWL(43fcb180): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): releaseWL(437180a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4312e378): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1962): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  905): Resuming delayed broadcast
,I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 1044 ms] updated apps [took 1044 ms] 
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
,W/PackageManager(  905): Unable to load service info ResolveInfo{43fc5928 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Icing   ( 1962): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1962): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(4312e378): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1248): onLoadItems() -
,I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 -
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,I/GCoreNlp( 1196): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): acquireWL(42c42920): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42c42920): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(43c7c4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(43c7c4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425d32d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425d32d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,D/PMS     (  905): acquireWL(435edec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(435edec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(43ad3b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d24db0: PendingIntentRecord{4248bb98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=168774, Int=0
,D/PMS     (  905): acquireWL(42bf31d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43ad3b28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(440e16d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4197): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4197): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4197): nl80211: survey data missing!
E/wpa_supplicant( 4197): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4197): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(43fc8d60): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/PMS     (  905): releaseWL(42bf31d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(440e16d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(431e0998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(431e0998): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1962): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42982da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/SyncManager(  905): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24994, reason: UserStart, SyncResult: databaseError: true stats []
,D/PMS     (  905): releaseWL(43fc8d60): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/SyncManager(  905): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 168870, reason: UserStart
D/PMS     (  905): releaseWL(42982da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1532/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4291eac0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): releaseWL(4291eac0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,D/AutoSetting( 4258): service - handleMessage() stop self
,D/AutoSetting( 4258): service - onDestroy() END
,D/AutoSetting( 4258): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=4002
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4002:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4002
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/BluetoothSapService( 4105): onUnbind: android.bluetooth.IBluetoothSap
D/WifiService(  905): Client connection lost with reason: 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(425c15d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(425c15d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
,D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4265ada0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f7f148: PendingIntentRecord{41f85fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=196717, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4265ada0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(44067fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d24db0: PendingIntentRecord{4248bb98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=198828, Int=0
,D/PMS     (  905): acquireWL(43167888): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(44067fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(430b33b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(43167888): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(430b33b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(4403cab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4403cab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ClearcutLoggerApiImpl( 2367): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42c187d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end,
,D/PMS     (  905): releaseWL(42c187d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43c547e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41f7f148: PendingIntentRecord{41f85fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=256717, Int=0
,I/IntentController( 1106): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43c547e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42929b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(42929b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(440a57d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1106): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): releaseWL(440a57d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1520): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1520): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1106): closing low battery warning: level=100
D/PowerUI ( 1106): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1106): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4059): --= Surplus to requirements =--
I/jxcore-log( 4059): 
,I/jxcore-log( 4059): ****TEST TOOK:  ms ****
I/jxcore-log( 4059): 
,I/jxcore-log( 4059): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4059): 
,E/cutils-trace( 5017): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5017): ====startRecUseTime====
D/htc.customization.log.level( 5017):  is 
,W/CustomizationLogLevel( 5017): Level value is invalid, use default level 2
,D/CustomizationManager( 5017):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5017): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 5017): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5017): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 5017): Parsing tag category name = system
,I/CustomizationCIDLoader( 5017): Parsing tag category name = application
I/CustomizationCIDLoader( 5017): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 5017): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5017): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 5017): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5017): Parsing tag category name = Settings
D/CustomizationManager( 5017):  Read CID file spent 0.158 (s)
,D/CustomizationManager( 5017):  All configurations done spent 0.158 (s)
,W/HtcNativeFlag( 5017): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5017): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5017): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 5017): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=5017, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=4059
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  905): Killing 4059:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{42591a90 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  905): Copying FileAsset 0x6ce6a590 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  905): channel '423874c0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '423874c0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/WifiService(  905): Client connection lost with reason: 4
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '423874c0 com.test.thalitest.MainActivity (s)'
I/WindowState(  905): WIN DEATH: Window{423874c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowManager(  905): WINDOW DIED Window{423874c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 4059 uid 10389
,W/PackageSettings(  905): Skipping PackageSetting{42180510 com.example.hello/10397} due to missing metadata
,W/Binder  ( 1183): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1183): java.lang.NullPointerException
W/Binder  ( 1183): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1183): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1183): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1183): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1520): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1520): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1520): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1303): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1248): Deferring update until onResume
,D/Launcher( 1248): waitUntilResume // bindAppsRemoved
,W/GeofencerStateMachine( 1196): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(4410f360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1196 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4410f360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/VoicemailCleanupService( 1272): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1230): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/AccTypeManager( 1303): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1303): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  905):   Scheme: "smsto"
I/IcingCorporaProvider( 2662): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5033 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,E/ExternalAccountType( 1303): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  905): acquireWL(41cdd280): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,E/SQLiteLog( 2662): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2662): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64299fb8
,E/IcingCorporaProvider( 2662): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2662): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2662): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2662): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2662): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2662): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2662): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2662): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2662): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2662): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2662): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2662): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2662): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2662): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2662): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2662): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2662): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2662): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2662): 	... 15 more
W/IcingCorporaProvider( 2662): notifyTableChanged failed.
W/IcingCorporaProvider( 2662): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2662): UpdateCorporaTask done [took 363 ms] updated apps [took 363 ms] 
,D/PMS     (  905): releaseWL(41cdd280): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/SQLiteDatabase( 5033): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5033): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5033): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5033): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5033): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5033): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5033): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5033): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5033): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5033): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5033): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5033): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5033): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5033): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5033): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5033): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5033): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5033): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 5033): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5033): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5033): 	at Bk.b(ClientFlagDatabaseImpl.java:149),
E/SQLiteOpenHelper( 5033): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5033): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5033): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5033): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5033): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5033): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5033): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5033): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5033): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5033): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5033): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5033): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5033): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5033): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5033): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5033): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5033): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 5033): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5033): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5033): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5033): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5033): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5033): 	at ahn.a(AbstractDatabaseInstance.java:437),
E/SQLiteDatabase( 5033): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5033): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 5033): threadid=11: thread exiting with uncaught exception (group=0x4166ce30)
,E/AndroidRuntime( 5033): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5033): Process: com.google.android.apps.docs, PID: 5033
E/AndroidRuntime( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5033): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5033): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5033): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5033): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5033): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  905): Can't write: system_app_crash
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
,E/SQLiteDatabase( 5033): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5033): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5033): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5033): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5033): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5033): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5033): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5033): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5033): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5052 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteOpenHelper( 5033): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5033): 	at android.database.sq,lite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5033): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5033): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5033): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5033): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5033): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5033): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5033): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5033): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5033): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 5033): killProcess, pid=5033
D/Process ( 5033): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/PMS     (  905): acquireWL(436ab3f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41f7f148: PendingIntentRecord{41f85fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=316718, Int=0
,I/ActivityManager(  905): Recipient 5033
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4583
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4583:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 5033) has died.
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4583
,W/ContextImpl( 5052): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,W/PackageManager(  905): Unable to load service info ResolveInfo{43635c90 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5065 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5052): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5052): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5052): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5052): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5052): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5052): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5052): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5052): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5052): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5052): threadid=10: thread exiting with uncaught exception (group=0x4166ce30)
E/AndroidRuntime( 5052): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5052): Process: com.android.keychain, PID: 5052
E/AndroidRuntime( 5052): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5052): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5052): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5052): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5052): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5052): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5052): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5052): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5052): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5052): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5052): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  905): App crashed! Process: com.android.keychain
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
,D/AppTag  ( 5065): getInstance(Context context)
,D/AppTag  ( 5065): getInstance(Context context)
,D/AppTag  ( 5065): onCreate()
,D/Process ( 5052): killProcess, pid=5052
,D/Process ( 5052): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452596700354.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 5052
,I/ActivityManager(  905): Process com.android.keychain (pid 5052) has died.
,W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b2eeb0 +
I/Prism.WidgetManager( 1248): onLoadItems() +
,D/PMS     (  905): acquireWL(42323b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 3693 10160 null
,D/PMS     (  905): releaseWL(42323b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4916): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2367): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteLog( 1962): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2367): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x644db790
,E/SQLiteDBG( 1962): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65e22e30
,W/dalvikvm( 2367): threadid=1: thread exiting with uncaught exception (group=0x4166ce30)
,W/dalvikvm( 1962): threadid=48: thread exiting with uncaught exception (group=0x4166ce30)
,E/ActivityManager(  905): App crashed! Process: com.google.process.gapps
,E/AndroidRuntime( 2367): FATAL EXCEPTION: main
E/AndroidRuntime( 2367): Process: com.google.process.gapps, PID: 2367
E/AndroidRuntime( 2367): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2367): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2367): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2367): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2367): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2367): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2367): 	... 10 more
E/SQLiteLog( 1962): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 1962): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6ce7ec38
,E/DriveAsyncService( 1962): disk I/O error (code 3850)
E/DriveAsyncService( 1962): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1962): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1962): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1962): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1962): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1962): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1962): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1962): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1962): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1962): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 1962): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1962): Process: com.google.android.gms, PID: 1962
E/AndroidRuntime( 1962): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1962): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1962): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1962): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1962): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1962): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1962): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1962): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1962): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1962): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/syst,em/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2367): killProcess, pid=2367
D/Process ( 2367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5090 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1962): killProcess, pid=1962
D/Process ( 1962): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
,I/DeviceManagement( 5090): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5090 dbg=false s=true
,I/DeviceManagement( 5090): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5090): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 5090): WorkflowService: Starting workflow service
,I/DeviceManagement( 5090): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ace0b0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5090): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5090): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 5090): PackageUpdateWorkflow: ==================================================
,I/ActivityManager(  905): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 5090): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 5090): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5090): SessionStateController: Checking invariants...
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2367
I/ActivityManager(  905): Process com.google.process.gapps (pid 2367) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Recipient 1962
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Process com.google.android.gms (pid 1962) has died.
,D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10968ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10968ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20968ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20967ms
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5112 uid=10099 gids={50099, 3003, 5012}
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20950ms
,W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20950ms

```
