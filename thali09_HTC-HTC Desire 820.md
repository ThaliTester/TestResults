#### Test 54970261c23922d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  907): setLight #0: color=#23
V/LightsService(  907): setLight #0: color=#20
,V/LightsService(  907): setLight #0: color=#19
V/LightsService(  907): setLight #0: color=#14
--------- beginning of /dev/log/main
E/cutils-trace( 3877): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3877): ====startRecUseTime====
D/htc.customization.log.level( 3877):  is 
W/CustomizationLogLevel( 3877): Level value is invalid, use default level 2
D/CustomizationManager( 3877):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3877): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3877): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3877): Parsing tag category name = system
I/CustomizationCIDLoader( 3877): Parsing tag category name = application
I/CustomizationCIDLoader( 3877): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3877): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3877): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3877): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3877): Parsing tag category name = Settings
D/CustomizationManager( 3877):  Read CID file spent 0.098 (s)
D/CustomizationManager( 3877):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 3877): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3877): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3877): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3877): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3877
D/PMS     (  907): acquireHCC(425642d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4249c7a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1128386448
I/FeedHostManager( 1252): [onPause]
I/FeedProviderManager( 1252): onPause
I/FeedHostManager( 1252): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bbaf48
I/SocialFeedProvider( 1252): +onPause
I/SocialFeedProvider( 1252): -onPause
D/PMS     (  907): acquireWL(4257bf20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3888 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1252): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3888): Binding Chromium to main looper Looper (main, tid 1) {41a99428}
I/LibraryLoader( 3888): Expected native library version number "",actual native library version number ""
I/chromium( 3888): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3888): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(43c70660): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(423c3ae8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4264f690:true
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3888): 1101721184: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): releaseWL(43c70660): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3888): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3888): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3888): Local Branch: 
I/Adreno-EGL( 3888): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3888): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3888):                  aa63bbd948f41d15fc72f585e
W/chromium( 3888): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3888): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3888): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3888): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3888): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3888): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3888): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3888): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3888): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3888): CordovaWebView is running on device made by: HTC
,W/AwContents( 3888): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1252
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +258ms
W/ResourceType( 3888): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3888): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae03e8, mServedView=org.apache.cordova.engine.SystemWebView{41aa6178 VFEDH.C. .F...... 0,0-720,1134 #64}
W/XT9_C   ( 1190): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1190): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1190): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1190): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=3888
D/PMS     (  907): releaseWL(4257bf20): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3888): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3888): JniHelper::setJavaVM(0x41571048), pthread_self() = 1662687320
,D/JX-Cordova( 3888): jxcore cordova android initializing
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 11.625MB for 95956-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 11.704MB for 143930-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 11.819MB for 215890-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 11.994MB for 323830-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 12.266MB for 485740-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 13.266MB for 1092904-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 14.147MB for 1639352-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 15.487MB for 2459024-byte allocation
,I/dalvikvm-heap( 3888): Grow heap (frag case) to 17.514MB for 3688532-byte allocation
,W/jxcore-log( 3888): Initializing JXcore engine
,W/jxcore-log( 3888): JXcore engine is ready
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(425642d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(4249c7a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3888): Starting JXcore engine,
,W/jxcore-log( 3888): Platform android
W/jxcore-log( 3888): 
,W/jxcore-log( 3888): Process ARCH arm
W/jxcore-log( 3888): 
,I/jxcore-log( 3888): JXcore Cordova bridge is ready!
I/jxcore-log( 3888): 
,W/jxcore-log( 3888): JXcore engine is started
,I/chromium( 3888): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3888): Toggling radios to true
I/jxcore-log( 3888): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  907): checking for enable restriction...
,D/BluetoothManagerService(  907): checkBTEasState, ret=true
I/BluetoothManagerService(  907): isBluetoothRestricted(): false
,D/BluetoothManagerService(  907): enable(): region ID = 6
D/BluetoothManagerService(  907): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 1
W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1335
W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  907): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3888): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
D/WifiService(  907): setWifiEnabled: true pid=3888, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
D/WifiService(  907): New client listening to asynchronous messages
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
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
,W/Settings:Agent(  907): << traceCallingStack(): 4(ms)
I/ActivityManager(  907): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3933 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3888): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3888): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/jxcore-log( 3888): Radios toggled
I/jxcore-log( 3888): 
D/PMS     (  907): acquireWL(425099c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/AdapterServiceConfig( 3933): Adding HeadsetService
D/AdapterServiceConfig( 3933): Adding A2dpService
D/AdapterServiceConfig( 3933): Adding HidService
D/AdapterServiceConfig( 3933): Adding HealthService
D/AdapterServiceConfig( 3933): Adding PanService
,D/AdapterServiceConfig( 3933): Adding GattService
,W/linker  ( 3933): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3933): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43138d28:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3933): make
,I/BluetoothAdapterState( 3933): Entering OffState
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3933): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  907): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapter( 1112): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e624e0
,D/BluetoothAdapter( 1112): onBluetoothServiceUp done
D/BluetoothAdapter( 1218): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41b58e80
,D/BluetoothAdapter( 1218): onBluetoothServiceUp done
D/BluetoothAdapter(  907): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@44114428
,D/BluetoothAdapter(  907): onBluetoothServiceUp done
,D/BluetoothAdapter( 1237): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bcbc88
,D/BluetoothAdapter( 1237): onBluetoothServiceUp done
D/BluetoothAdapter( 1203): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41de3338
,D/BluetoothAdapter( 1203): onBluetoothServiceUp done
D/BluetoothAdapter( 3933): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ab1d40
,D/BluetoothAdapter( 3933): onBluetoothServiceUp done
,D/BluetoothAdapter( 3888): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4262af08
D/BluetoothAdapter( 3888): onBluetoothServiceUp done
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3933): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3933): Setting state to 11
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  907): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3933): make,
I/IntentController( 1112): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3933): StableState(): Entering Off State
,D/HeadsetService( 3933): Received start request. Starting profile...
D/PMS     (  907): acquireWL(435684d8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1203 10029 null
D/PMS     (  907): releaseWL(435684d8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,D/PMS     (  907): releaseWL(423c3ae8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/HeadsetStateMachine( 3933): Version 1.6
,D/HeadsetStateMachine( 3933): make
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3958 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 3933): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3933): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3933): Received start request. Starting profile...
V/Avrcp   ( 3933): make
,D/Avrcp   ( 3933): fillIntentFilter()
,D/HtcBtWidget_BTWidgetProvider( 3958): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3958): updateWidget(context) for widget: 
,D/A2dpStateMachine( 3933): make
,D/Process (  907): killProcessQuiet, pid=3685
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/QuickSettingBluetooth( 1112): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3933): Enter Disconnected: -2
,I/ActivityManager(  907): Killing 3685:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/HidService( 3933): Received start request. Starting profile...
,D/HealthService( 3933): Received start request. Starting profile...
,D/PanService( 3933): Received start request. Starting profile...
D/BluetoothTethering(  907): supplyMessenger
,D/BluetoothTethering(  907): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  907): got MESSAGE_CONNECT_PANSERVICE, call connect
D/PanService( 3933): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  907): got CMD_CHANNEL_HALF_CONNECTED
I/ActivityManager(  907): Recipient 3685
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
D/BtGatt.DebugUtils( 3933): handleDebugAction() action=null
D/BtGatt.GattService( 3933): Received start request. Starting profile...
D/BtGatt.GattService( 3933): start()
V/BluetoothPbapService( 3933): Pbap Service onCreate
V/BluetoothPbapService( 3933): Starting PBAP service
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 11
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 11
E/BluetoothMasService( 3933): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3933): Add permission for SmsProvider.
V/BluetoothMasService( 3933): Starting MAS instances
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 11
I/MailMessageReceiver( 3933): reg:com.android.bluetooth.btservice.AdapterApp@41aa52a8 with com.htc.util.mail.MailMessageReceiver@41ae51f0
I/MailManager( 3933): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41ae51f0
V/EmailUtils( 3933): Manager Instance is not NULL
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3977 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  907): interfaceAdded wlan0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): wlan0 is not a tetherable iface, ignoring
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): interfaceAdded p2p0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/Tethering(  907): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/PMS     (  907): releaseWL(425099c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
,V/BluetoothMasService( 3933): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 11
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3933): Manager Instance is not NULL
D/EmailUtils( 3933): ============NULL aList========
,V/EmailUtils( 3933): <-getEmailAccountIdList
V/BluetoothSapService( 3933): Sap Service onCreate
,V/BluetoothSapService( 3933): initBinder
V/BluetoothSapService( 3933): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41aea5e0
,V/BluetoothSapReceiver( 3933): BluetoothSapReceiver init
,D/BluetoothSapService( 3933): setSapService()
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3933): state: 12
,D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 11
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 3933): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3933): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothAdapterService( 3933): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothTethering(  907): got CMD_CHANNEL_FULLY_CONNECTED
,D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/Process (  907): killProcessQuiet, pid=3340
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 11
I/ActivityManager(  907): Killing 3340:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/qcom-bluetooth( 3996): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/ActivityManager(  907): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3997 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4014): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3997): Received state change = 11
,I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4018): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4019): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4021): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  907): New client listening to asynchronous messages
,D/Process (  907): killProcessQuiet, pid=3607
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1353): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  907): Killing 3607:com.google.android.talk/u0a111 (adj 15): empty #17
,D/WifiMonitor(  907): startMonitoring(wlan0) with mConnected = false
I/IntentController( 1112): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1112): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  907): Recipient 3340
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/wpa_supplicant( 4025): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4025): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4025): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4025): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4025): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4025): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4025): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4025): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4025): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4025): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4025): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4025): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4025): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4025): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4025): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4025): update_config=1
D/wpa_supplicant( 4025): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4025): device_name='Android_1950'
D/wpa_supplicant( 4025): manufacturer='HTC'
D/wpa_supplicant( 4025): model_name='HTC_PHONE'
D/wpa_supplicant( 4025): model_number='1234'
D/wpa_supplicant( 4025): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4025): p2p_oper_reg_class=126
D/wpa_supplicant( 4025): p2p_oper_channel=36
D/wpa_supplicant( 4025): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4025): persistent_reconnect=1
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4025): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4025): nl80211: RFKILL status not available
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
,I/ActivityManager(  907): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4027 uid=10050 gids={50050}
D/wpa_supplicant( 4025): nl80211: Using driver-based roaming
D/wpa_supplicant( 4025): nl80211: TDLS supported
D/wpa_supplicant( 4025): nl80211: TDLS external setup
D/wpa_supplicant( 4025): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4025): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4025): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4025): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4025): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4025): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4025): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8787758
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8787758
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4025): htc_wext_command_init +
E/wpa_supplicant( 4025): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4025): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4025): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4025): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4025): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4025): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged p2p0, false
D/Tethering(  907): interfaceStatusChanged p2p0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,I/QuickSettingWifi( 1112): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
D/Process (  907): killProcessQuiet, pid=3723
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  907): Killing 3723:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3723
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3607
,I/qcom-bluetooth( 4039): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4040): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 4025): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4025):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4025):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4025):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): nl80211: Flush PMKIDs
E/wpa_supplicant( 4025): send_and_recv error -22 - cmd 54
I/wpa_supplicant( 4025): State: DISCONNECTED -> INACTIVE
,I/bt-btu  ( 3933): btu_task pending for preload complete event
,D/wpa_supplicant( 4025): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4025): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4025): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4025): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4025): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4025): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): Using existing control interface directory.
D/wpa_supplicant( 4025): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4025): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
D/wpa_supplicant( 4025): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4025): P2P: Own listen channel: 1
D/wpa_supplicant( 4025): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4025): P2P: Add operating class 81
,I/wpa_supplicant( 4025): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4025): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4025): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4025): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4025): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4025): disable_scan_offload=1
D/wpa_supplicant( 4025): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4025): update_config=1
D/wpa_supplicant( 4025): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 4025): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4025): manufacturer='HTC'
D/wpa_supplicant( 4025): model_name='HTC Desire 820'
D/wpa_supplicant( 4025): model_number='HTC Desire 820'
D/wpa_supplicant( 4025): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4025): persistent_reconnect=1
D/wpa_supplicant( 4025): p2p_disabled=1
D/wpa_supplicant( 4025): hs20=1
D/wpa_supplicant( 4025): interworking=1
D/wpa_supplicant( 4025): Line: 18 - start of a new network block
D/wpa_supplicant( 4025): key_mgmt: 0x2
D/wpa_supplicant( 4025): priority=1 (0x1)
,D/wpa_supplicant( 4025): signinfail=0 (0x0)
,D/wpa_supplicant( 4025): Priority group 1
D/wpa_supplicant( 4025):    id=0 ssid='NG700'
I/wpa_supplicant( 4025): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4025): nl80211: RFKILL status not available
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4025): nl80211: Using driver-based roaming
D/wpa_supplicant( 4025): nl80211: TDLS supported
D/wpa_supplicant( 4025): nl80211: TDLS external setup
D/wpa_supplicant( 4025): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4025): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4025): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4025): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4025): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4025): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4025): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8797718
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4025): htc_wext_command_init +
I/wpa_supplicant( 4025): htc_wext_command_init -
I/wpa_supplicant( 4025): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4025): Don't set 00 to countryID.conf
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4025): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4025): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4025): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4025): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4025): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4025): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4025):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4025):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 4025):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4025): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4025): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4025): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4025): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 4025): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4025): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4025): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
,D/wpa_supplicant( 4025): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4025): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4025): Using existing control interface directory.
I/wpa_supplicant( 4025): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4025): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4025): Auto country group 1: ch36
I/wpa_supplicant( 4025): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4025): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 4025): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4025): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4025): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_907-2
D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4025): nl80211: Event message available
D/wpa_supplicant( 4025): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4025): nl80211: Regulatory domain change
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4025): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4025): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4025): P2P: Add operating class 81
D/wpa_supplicant( 4025): P2P: Add operating class 115
D/wpa_supplicant( 4025): P2P: Add operating class 116
D/wpa_supplicant( 4025): P2P: Add operating class 117
D/wpa_supplicant( 4025): P2P: Update channel list
D/wpa_supplicant( 4025): p2p0: Updating hw mode
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4025): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4025): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4025): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4025): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4025): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): set wifi ON
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER MACADDR
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  907): Loading config and enabling all networks
D/WifiNative-wlan0(  907): doString: LIST_NETWORKS
W/WifiHW  (  907): QCOM Debu,g wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): list_network_info: ret=0x1, pos=0xb879a117 buf=0xb879a0e8
I/wpa_supplicant( 4025): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4025): 0	NG700	any	
D/WifiNative-wlan0(  907):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  907): 0	NG700	any	
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
I/IntentController( 1112): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 bssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'bssid'
V/RegulatoryObserver(  907): uevent:
V/RegulatoryObserver(  907): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  907): Regulatory Country Code:DE
V/RegulatoryObserver(  907): Start wifi-crda service to run crda.
V/RegulatoryObserver(  907): Country Code is DE
V/RegulatoryObserver(  907): Send broadcast country code message.
I/RegulatoryObserver(  907): Broadcast intent for crda country code: DE
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WIFI_ICON( 1112): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 priority
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4025): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 proto
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  907): Failed to look-up a string: W
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 group
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  907): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  907): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 limited
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 eap
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 phase2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): onWiFiStateChanged() for widget: 
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 password
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/HtcWiFiWidget_WiFiWidgetProvider( 4027): updateWidget(context) for widget: 
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 key_id
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  907): doString: GET_NETWORK 0 private_key
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4025): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  907): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  907): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4025): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4025): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET manufacturer HTC
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4025): manufacturer='HTC'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4025): model_name='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4025): model_number='HTC Desire 820'
D/WifiNative-wlan0(  907):    returned true
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4025): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET auto_interworking 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4025): auto_interworking=0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): SET_SCREEN_ON:On
I/wpa_supplicant( 4025): htc_wext_set_keepalive +
I/wpa_supplicant( 4025): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4025): getPrivFuncNum +	
I/wpa_supplicant( 4025): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET ps 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4025): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiP2pService(  907): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  907): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  907): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): SETBAND: 0
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4025): P2P: Add operating class 81
D/wpa_supplicant( 4025): P2P: Add operating class 115
D/wpa_supplicant( 4025): P2P: Add operating class 116
D/wpa_supplicant( 4025): P2P: Add operating class 117
D/wpa_supplicant( 4025): P2P: Update channel list
I/wpa_supplicant( 4025): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 4025): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4025): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4025): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4025): p2p_oper_reg_class=126
D/wpa_supplicant( 4025): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4025): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4025): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4025): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4025): p2p_oper_channel=36
E/wpa_supplicant( 4025): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4025): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4025): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4025): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4025): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: BSS_FLUSH 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): wpa_supplicant_scan enter
I/wpa_supplicant( 4025): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4025): ap_scan=1 , scan_req =2
I/wpa_supplicant( 4025): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4025): Scan req (ret=0) - timeout 10 secs
D/wpa_supplicant( 4025): nl80211: Event message available
D/wpa_supplicant( 4025): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4025): wpa_supplicant_scan enter
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Wifi band: 0, ScanBroadCastCounter: 0
I/wpa_supplicant( 4025): wpa_supplicant_scan enter
D/libc    (  907): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  907): startMonitoring(p2p0) with mConnected = true
D/WifiNative-p2p0(  907): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4025): persistent_reconnect=1
I/wpa_supplicant( 4025): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_name Android_1950
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4025): device_name='Android_1950'
I/wpa_supplicant( 4025): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4025): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4025): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 4025): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4025): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4025): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4025): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
I/QuickSettingWifi( 1112): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: P2P_SET conc_pref sta
D/WifiP2pService(  907): P2pEnablingState
D/WifiP2pService(  907): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2p socket connection successful
D/WifiP2pService(  907): P2pEnabledState
D/WifiP2pService(  907): sending p2p connection changed broadcast
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  907): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  907): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4025): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4025): Single channel concurrency preference: sta
I/wpa_supplicant( 4025): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: STATUS
W/WifiHW  (  907): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  907): doBoolean: P2P_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4025): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4025): P2P: Stopping find
D/wpa_supplicant( 4025): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4025): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4025): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  907): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4025): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4025): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doString: LIST_NETWORKS
W/WifiHW  (  907): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4025): list_network_info: ret=0x22, pos=0xb879a10a buf=0xb879a0e8
I/wpa_supplicant( 4025): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4025): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  907):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  907): doBoolean: AP_SCAN 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  907):    returned false
D/WifiNative-p2p0(  907): doBoolean: SET wifi_display 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4025): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4025): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4025): WFD: Update WFD IE
I/wpa_supplicant( 4025): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4025): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  907):    returned true
D/WifiNative-p2p0(  907): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  907): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4025): WFD: Set subelement 0
D/wpa_supplicant( 4025): WFD: Update WFD IE
I/wpa_supplicant( 4025): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4025): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  907):    returned true
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
D/WifiP2pService(  907): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  907):  deviceAddress: b6:ce:f6:ad:a4:6b
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
D/WifiP2pService(  907): InactiveState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  907):  WFD CtrlPort: 7236
D/WifiP2pService(  907):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-10ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  907):  WFD CtrlPort: 7236
D/WifiP2pService(  907):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  907): Successfully set WFD info.
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  907): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  907):  deviceAddress: b6:ce:f6:ad:a4:6b
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
D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
D/HtcEffectManager(  907): convertEffect after=902
,D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,I/SensorManager(  907): mEventCount = 750
,D/wpa_supplicant( 4025): nl80211: Event message available
D/wpa_supplicant( 4025): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4025): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4025): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 4025): nl80211: Survey data missing
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4025): Sorted scan results
I/wpa_supplicant( 4025): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 4025): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 4025): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 4025): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-88
D/wpa_supplicant( 4025): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 4025): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4025): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4025): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4025): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4025): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4025): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4025): wpa_supplicant_pick_network+
I/wpa_supplicant( 4025): Selecting BSS from priority group 1
I/wpa_supplicant( 4025): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4025): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4025): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4025): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4025): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4025):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4025):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 4025): Start print parameters
I/wpa_supplicant( 4025): wpa_s->wpa_state is 3
I/wpa_supplicant( 4025): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4025): isConcurrentMode() is 0
I/wpa_supplicant( 4025): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4025): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4025): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4025): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4025): wpa_s->reassociate is 0
I/wpa_supplicant( 4025): wpa_s->is_screen_on 1
I/wpa_supplicant( 4025): wpa_s->ifname wlan0
I/wpa_supplicant( 4025): End print parameters
I/wpa_supplicant( 4025): selected network = 2
D/wpa_supplicant( 4025): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87984e8  current_ssid=0x0
D/wpa_supplicant( 4025): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4025): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4025): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4025): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4025): check if in concurrent case
,I/wpa_supplicant( 4025): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 4025): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4025): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4025): wpa_supplicant_associate, 1795,
D/wpa_supplicant( 4025): RSN: PMKSA cache search - network_ctx=0xb87984e8 try_opportunistic=0,
D/wpa_supplicant( 4025): RSN: Search for BSSID c0:ff:d4:d3:aa:48,
D/wpa_supplicant( 4025): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4025): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=-1, operstate=5,
D/wpa_supplicant( 4025): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4025): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4025): nl80211: Unsubscribe mgmt frames handle 0xb8797718 (mode change)
D/wpa_supplicant( 4025): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8797718
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Register frame type=0xd0 nl_handle=0xb8797718
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4025): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4025):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4025):   * freq=2412
D/wpa_supplicant( 4025):   * Auth Type 0
D/wpa_supplicant( 4025):   * WPA Versions 0x2
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4025): nl80211: Connect request send successfully
D/wpa_supplicant( 4025): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4025): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4025): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4025): reply (489) for get BSS: id=0
I/wpa_supplicant( 4025): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4025): freq=5220
I/wpa_supplicant( 4025): level=-47
I/wpa_supplicant( 4025): tsf=0000000103411059
I/wpa_supplicant( 4025): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4025): ssid=NG7005g
I/wpa_supplicant( 4025): ====
I/wpa_supplicant( 4025): id=1
I/wpa_supplicant( 4025): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4025): freq=2412
I/wpa_supplicant( 4025): level=-54
I/wpa_supplicant( 4025): tsf=0000000103411069
I/wpa_supplicant( 4025): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4025): ssid=01ABC
I/wpa_supplicant( 4025): ====
I/wpa_supplicant( 4025): id=2
I/wpa_supplicant( 4025): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4025): freq=2412
I/wpa_supplicant( 4025): level=-54
I/wpa_supplicant( 4025): tsf=0000000103411073
I/wpa_supplicant( 4025): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4025): ssid=NG700
I/wpa_supplicant( 4025): ====
I/wpa_supplicant( 4025): id=3
I/wpa_supplicant( 4025): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4025): freq=2412
I/wpa_supplicant( 4025): level=-88
I/wpa_supplicant( 4025): tsf=0000000103411077
I/wpa_supplicant( 4025): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4025): ssid=Gonzos
I/wpa_supplicant( 4025): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1203): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 103411059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 103411069, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 103411073, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2412, timestamp: 103411077, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4025): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4025): nl80211: Event message available
D/wpa_supplicant( 4025): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4025): nl80211: Connect event
D/wpa_supplicant( 4025): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4025): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4025): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4025): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4025): Add randomness: count=6 entropy=4
I/wpa_supplicant( 4025): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4025): TDLS: Remove peers on association
D/wpa_supplicant( 4025): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4025): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4025): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4025): htc_wext_set_keepalive +
I/wpa_supplicant( 4025): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4025): getPrivFuncNum +	
I/wpa_supplicant( 4025): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4025): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4025): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMo,nitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Associated
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...,
I/wpa_supplicant( 4025): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87979f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4025):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4025): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4025): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0fb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4025):    broadcast key
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4025): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4025): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4025): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4025): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4025): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4025): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4025): set send_ind_to_ndc = 0
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4025): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4025): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4025): EAPOL: SUPP_PAE entering state AUTHENTICATING,
D/wpa_supplicant( 4025): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4025): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 4025): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4025): EAPOL: SUPP_BE entering state IDLE,
D/wpa_supplicant( 4025): EAPOL authentication completed successfully
I/wpa_supplicant( 4025): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4025): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4025): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4025): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...,
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3305): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WISPrService( 3305): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  907): New client listening to asynchronous messages
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  907): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4025): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): Power_Mode_Type mode = 1
I/wpa_supplicant( 4025): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(43106c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42548390 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42548390 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1112): receive.wifiConnect:false wifiAPname:null elapse:0
,I/bt-btu  ( 3933): btu_task received preload complete event
,D/bt-btm  ( 3933): btm_acl_device_down
,D/bt-btm  ( 3933): btm_acl_reset_paging
,D/bt-btm  ( 3933): btm_acl_set_discing
,I/bt-btm  ( 3933): btm_reset_complete
,I/bt-btm  ( 3933): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3933): Start reading local supported commands
,D/bt-btm  ( 3933): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3933): BTM reads next extended features page (1)
,D/bt-btm  ( 3933): BTM reads next extended features page (2)
D/bt-btm  ( 3933): BTM reached last extended features page (2)
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3933): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3933): btm_read_ble_wl_size 
D/bt-btm  ( 3933): btm_read_white_list_size_complete 
,D/bt-btm  ( 3933): btm_get_ble_buffer_size 
D/bt-btm  ( 3933): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3933): btm_read_ble_local_supported_features 
D/bt-btm  ( 3933): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3933): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 0
,D/bt-btm  ( 3933): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3933): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3933): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3933): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,I/bt-btm  ( 3933):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3933): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3933): BTM_SetInquiryMode
I/bt-btm  ( 3933): BTM_SetPageScanType
I/bt-btm  ( 3933): BTM_SetInquiryScanType
,D/bt-btm  ( 3933): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3933): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
D/bt-btm  ( 3933): BTM_BleLoadLocalKeys
I/bt-btm  ( 3933): BTM_Sec: application registered
,E/bt-btm  ( 3933): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f52941 
I/bt-btm  ( 3933): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3933): SMP_Register state=0
E/bt-btm  ( 3933): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f52941 
,I/bt-btm  ( 3933): BTM_Sec: application registered
D/bt-btm  ( 3933): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3933): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3933): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 3933): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3933): BTM_RegBusyLevelNotif
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 3933): allocated gatt_if=3
I/bt-att  ( 3933): GATT_StartIf gatt_if=3
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3933): Calling BTA_HhEnable
E/bt-btif ( 3933): Calling BTA_HhEnable
,I/bt-btm  ( 3933): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
E/bt-btif ( 3933): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:2 len:6
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:3
D/BluetoothAdapterProperties( 3933): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:1 len:14
D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:4
,D/bt-btm  ( 3933): BTM_AllocateSCN
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3933):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3933): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-avp  ( 3933): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3933): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3933):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3,933): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 08:ec:a9:50:75:41
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: f8:cf:c5:d9:e5:61
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3933): BTM_GetHCIConnHandle
I/bt-btm  ( 3933): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3933): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3933): GATT_Register
D/bt-att  ( 3933): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3933): allocated gatt_if=4
I/bt-att  ( 3933): GATT_StartIf gatt_if=4
D/bt-att  ( 3933): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3933): gatt_find_the_connected_bda found=0 found_idx=7
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3933): Scan Mode:20
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:8 len:60
,D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothAdapter( 3933): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3933): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41af5928
,D/BluetoothDevice( 3933): getService : Register callback
,D/BluetoothAdapterProperties( 3933): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3933): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 3933): Adding bonded device:14:B4:84:21:3B:49
,D/BluetoothAdapterProperties( 3933): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3933): Adding bonded device:08:EC:A9:50:75:41
,D/BluetoothAdapterProperties( 3933): Adding bonded device:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3933): Adding bonded device:7C:F9:0E:34:8A:A0
,D/BluetoothAdapterProperties( 3933): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 3933): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3933): Adding bonded device:38:94:96:B5:06:DC
,I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
D/wpa_supplicant( 4025): EAPOL: disable timer tick
D/wpa_supplicant( 4025): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4025): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 18
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
,I/bt-btif ( 3933): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3933): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 3933): Remote class is:5898764
I/bt-btif ( 3933): BTA_JvEnable
I/bt-btm  ( 3933): BTM_ReadConnectability
,I/bt-btm  ( 3933): BTM_ReadDiscoverability
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3933): br_edr_supported=0x2
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3933): bta_pan_co_init
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3933):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,E/bt_mct  ( 3933): hci lib postload completed
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
,I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3933): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3933): ScanMode =  20
D/BluetoothAdapterProperties( 3933): State =  11
I/bt-btm  ( 3933): BTM_SetDiscoverability
I/bt-btm  ( 3933): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3933): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3933): br_edr_supported=0x0
I/bt-btm  ( 3933): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3933): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3933): BTM_SetConnectability
I/bt-btm  ( 3933): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3933): new flag=0x0 cur flag=0x4
D/BluetoothAdapterProperties( 3933): Setting state to 12
D/bt-btm  ( 3933): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3933): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3933): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3933): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterState( 3933): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3933): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,I/BluetoothAdapterState( 3933): Entering On State
D/BluetoothAdapterProperties( 3933): Scan Mode:21
I/bt-btif ( 3933): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3933): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3933): Discoverable Timeout:120
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1101722064)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=10
,D/BluetoothHeadset( 1112): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1218): Proxy object connected
,D/BluetoothHeadset( 1112): Proxy object connected
I/QuickSettingMiniLite( 1112): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41dc6c40
,D/BluetoothPan(  907): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
,D/BluetoothPan(  907): BluetoothPAN Proxy object connected
D/BluetoothHeadset( 1218): Proxy object connected
,D/BluetoothPhoneService( 1218): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset(  907): onBluetoothStateChange: up=true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothA2dp(  907): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1218): 1103045960: getState(). Returning 12
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothHeadset(  907): Proxy object connected
,I/IntentController( 1112): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,D/BluetoothAdapter(  907): 1111625328: getState(). Returning 12
V/BluetoothPbapReceiver( 3933): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 3933): ***********state = 12
,D/BluetoothA2dp(  907): Proxy object connected
,D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
,D/HtcBtWidget_BTWidgetProvider( 3958): onBTStateChanged() for widget: 
V/BluetoothSapReceiver( 3933): SapReceiver onReceive 
V/BluetoothSapReceiver( 3933): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3933):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3933): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/HtcBtWidget_BTWidgetProvider( 3958): updateWidget(context) for widget: 
D/BluetoothAdapterService(1101722064)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=10
,D/BluetoothAdapter(  907): 1111625328: getState(). Returning 12
D/PMS     (  907): acquireWL(42621a80): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3305 1000 null
D/PMS     (  907): acquireWL(42a706a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1203 10029 null
W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  907): releaseWL(42a706a0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  907): releaseWL(42621a80): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 12
,D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 12
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3933): Manager Instance is not NULL
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4408ff60:true
,D/BluetoothManagerService(  907): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/LocationAgent( 3305): new LocationAgent instance!!
,D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/PMS     (  907): acquireWL(44184ce0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3305 1000 null
D/HtcTagManager( 3305): HtcTagManager construction complete
D/EmailUtils( 3933): ============NULL aList========
V/EmailUtils( 3933): <-getEmailAccountIdList
V/BluetoothSapService( 3933): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3933): state: 12
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 12
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
W/ContextImpl( 3933): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
D/BluetoothInputDevice( 3305): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
V/BluetoothSapService( 3933): Starting SAP server process
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
D/BluetoothInputDevice( 3305): BluetoothInputDevice(): Binding service...
,D/BluetoothManagerService(  907): Registered receivers: 7
,V/BluetoothPbapService( 3933): Handler(): got msg=1
,D/BluetoothPan( 3305): BluetoothPan()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,V/BluetoothPbapService( 3933): Pbap Service startRfcommSocketListener
,V/BluetoothPbapService( 3933): Pbap Service initSocket
,W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
D/BluetoothPan( 3305): BluetoothPan(): Binding service...
D/BluetoothAdapter( 3933): getBluetoothService(): entry
,W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/BluetoothMap( 3305): Create BluetoothMap proxy object
,D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
,I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3933): Succeed to create listening socket 
V/BluetoothPbapService( 3933): Accepting socket connection...
,D/BluetoothManagerService(  907): registerStateChangeCallback+
,V/BluetoothMasService( 3933): handleMessage: mIsEmailEnabledtrue
,W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
V/BtMns   ( 3933): BluetoothMns: isEmailEnabled: true
E/BluetoothMap( 3305): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothAdapter( 1112): 1104553256: getState(). Returning 12
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothSap( 3305): BluetoothSap() call bindService
D/BluetoothMasService( 3933): Map_prev 1
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 1112): 1104553256: getState(). Returning 12
,D/BluetoothPbap( 3305): BluetoothPbap()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
,I/QuickSettingBluetooth( 1112): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1112): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothAdapter( 3933): getBluetoothService(): entry
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
D/BluetoothPbap( 3305): BluetoothPbap(): Binding service...
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3933): getBluetoothService(): entry
,W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
,I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
,I/bt-btm  ( 3933):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothA2dp( 3305): BluetoothA2dp()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
,D/BluetoothA2dp( 3305): BluetoothA2dp(): Binding service...
W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothHeadset( 3305): BluetoothHeadset()
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothSapService( 3933): Sap_prev 1
,V/BluetoothSapService( 3933): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 3933): Sap Service initRfcommSocket
W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
,D/BluetoothHeadset( 3305): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3305): startProxy
,W/ContextImpl( 3305): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3305): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 3 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/BluetoothAdapter( 1112): 1104553256: getState(). Returning 12
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3933):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3933): Succeed to create listening socket 
V/BluetoothSapService( 3933): Accepting socket connection...
I/QuickSettingMiniLite( 1112): updateLiteState:no connect device!
D/DockEventReceiver( 3305): finishStartingService: stopping service
D/BluetoothPan( 3305): BluetoothPAN Proxy object connected
D/PanProfile( 3305): Bluetooth service connected
D/BluetoothA2dp( 3305): Proxy object connected
D/A2dpProfile( 3305): Bluetooth service connected
V/TAG     ( 3933): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3933): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41aebd20
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
V/BluetoothPbapService( 3933): Pbap Service onBind
D/BluetoothInputDevice( 3305): Proxy object connected
D/HidProfile( 3305): Bluetooth service connected
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
D/BluetoothHeadset( 3305): Proxy object connected
D/HeadsetProfile( 3305): Bluetooth service connected
D/BluetoothAdapter( 3305): 1103329360: getState(). Returning 12
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3997): onCreate: going to find gatt base service first.
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/BluetoothFtpService( 3933): Ftp Service onCreate
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 12
,D/BluetoothMasReceiver( 3933): Bluetooth STATE CHANGED to 12
D/SapServerProfile( 3305): Bluetooth service connected
D/BluetoothPbap( 3305): Proxy object connected
D/PbapServerProfile( 3305): Bluetooth service connected
D/BluetoothAdapter( 3933): getBluetoothService(): entry
,W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 0 ***********************
,I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:15
,I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 3933):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 3933): Accept thread started.
,D/PMS     (  907): releaseWL(44184ce0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothFtpService( 3933): Ftp_prev 1
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3933): getBluetoothService(): entry
W/BluetoothAdapter( 3933): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3933): SOCK FLAG = 1 ***********************
I/bt-btif ( 3933): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3933): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3933): Write Extended Inquiry Response to controller
I/bt-btif ( 3933): BTA_JvRfcommStartServer
I/bt-btm  ( 3933): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3933):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
V/BluetoothFtpService:RfcommSocketAcceptThread( 3933): Run Accept thread
D/BluetoothAdapter( 3933): 1101740240: getState(). Returning 12
V/BluetoothMasService( 3933): parseIntent 1: mIsEmailEnabled: true
D/[HTC_BLE][Constants]( 3997):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3997):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3997):  + discoverServicesOnBonded = false
V/EmailUtils( 3933): Manager Instance is not NULL
,D/EmailUtils( 3933): ============NULL aList========,
V/EmailUtils( 3933): <-getEmailAccountIdList
,D/BluetoothMasService( 3933): Map_prev 1
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3997):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3997): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab5120
D/[HTC_BLE][Constants]( 3997): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3997): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3997): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3997): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3997): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3997): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3997): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3305): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3997): Received state change = 12
D/HtcTagProfile( 3305): setup proxy
,D/HtcPxpProfile( 3305): setup proxy
,D/HtcFmpProfile( 3305): setup proxy
D/BluetoothManagerService(  907): Registered receivers: 8
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 9
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 10
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 11
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41c75320:true
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3997): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3997): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab5120
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3997): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab5120
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3997): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab5120, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac0ad8
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3997): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41ab5120
D/wpa_supplicant( 4025): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4025): EAPOL: disable timer tick
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440f6d98:true
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3841): new LocationAgent instance!!
,D/HtcTagManager( 3841): HtcTagManager construction complete
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/BluetoothInputDevice( 3841): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 14
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/BluetoothInputDevice( 3841): BluetoothInputDevice(): Binding service...
,D/RingtoneManager( 3997): getExternalStorageState=mounted
,W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3841): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 15
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/BluetoothPan( 3841): BluetoothPan(): Binding service...,
D/BluetoothMap( 3841): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 16
,E/BluetoothMap( 3841): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3841): BluetoothSap() call bindService
,D/BluetoothManagerService(  907): Registered receivers: 17
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3841): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[0]: Crocus
D/BluetoothManagerService(  907): Registered receivers: 18
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[3]: Foxglove
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/BluetoothPbap( 3841): BluetoothPbap(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[10]: Snowbell
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3997):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothA2dp( 3841): BluetoothA2dp()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3997): BleProfilesStateMachine is initialized...
D/BluetoothManagerService(  907): Registered receivers: 19
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3997): Enter IdleState
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/BluetoothA2dp( 3841): BluetoothA2dp(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3997): initLeServices_platform
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3997): initScanModeInterface: true
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3997): loadDeviceConfiguration() init =true
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b21d30:true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3997):  + mTag.getPrimaryDeviceList() = []
,D/[HTC_BLE][Constants]( 3997):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3997):  + enableOnBonded = false
D/BluetoothHeadset( 3841): BluetoothHeadset()
D/[HTC_BLE][Constants]( 3997):  + discoverServicesOnBonded = false
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 20
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/BluetoothHeadset( 3841): BluetoothHeadset(): Binding service...
,D/HtcTagManager( 3841): startProxy
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3997): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac0ad8
,W/ContextImpl( 3841): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3841): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3841): setBluetoothStateOn
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): startProxy
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/BluetoothAdapterService(1101722064)( 3933): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3933): getBondedDevices: length=10
D/BluetoothAdapter( 3841): getBluetoothService(): entry
D/BluetoothAdapter( 3841): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3841): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41aef850
,D/BluetoothDevice( 3841): getService : Register callback
,W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,E/BluetoothDevice( 3841): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): addHtcTagProfiles
,D/BluetoothInputDevice( 3841): Proxy object connected
,D/HidProfile( 3841): Bluetooth service connected
D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
D/AuthorizationBluetoothService( 1353): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1353): Proximity feature is not enabled.
D/BluetoothPan( 3841): BluetoothPAN Proxy object connected
,D/PanProfile( 3841): Bluetooth service connected
D/SapServerProfile( 3841): Bluetooth service connected
D/BluetoothPbap( 3841): Proxy object connected
D/PbapServerProfile( 3841): Bluetooth service connected
D/BluetoothA2dp( 3841): Proxy object connected
,D/A2dpProfile( 3841): Bluetooth service connected
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/BluetoothHeadset( 3841): Proxy object connected
,D/HeadsetProfile( 3841): Bluetooth service connected
,D/BluetoothAdapter( 3841): 1101750616: getState(). Returning 12
,D/HtcTagManager( 3841): onServiceConnected
,D/HtcTagProfile( 3841): setup proxy
D/HtcPxpProfile( 3841): setup proxy
,D/HtcFmpProfile( 3841): setup proxy
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c1c88
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c1c88, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420b9058
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@425c9800
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4025): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(43106c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1112): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20067 delay=15s
,D/WifiWatchdogStateMachine(  907): WAN detection
,D/WISPrService( 3305): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1112): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42426a70
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(422aa560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 319ms
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
,I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/QuickSettingWifi( 1112): receive.wifiConnect:true wifiAPname:NG700 elapse:0
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42464780)
D/NfcService( 1237): ScreenObserver: OFF
,D/NfcService( 1237): applyRouting - 0
D/PMN     (  907): wakingUp
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=3888
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,D/NfcService( 1237): applyRouting -2
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(42344700): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1237 1027 null
D/PMS     (  907): acquireWL(430bc798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42344700): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  907): releaseWL(430bc798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/PMN     (  907): onScreenOn
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2150): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2150): [MTP][onReceive]-
,D/NfcService( 1237): applyRouting - 0
I/HtcPowerSaver(  907): << updateStatus
,D/NfcService( 1237): applyRouting -2
,D/AutoSetting( 1296): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  907): acquireWL(425580f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1237 1027 null
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): releaseWL(425580f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20068 delay=15s
D/TetherSettings( 3305): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3305): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3305): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3305): Cust_ConnectToPC   : spcsc>false
D/        ( 3305): Cust_ConnectToPC   : IPT>true
D/        ( 3305): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3305): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3305): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3305): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3305): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1296): service - onCreate()
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/AutoSetting( 1296): service - AddressCache: using context: com.htc.Weather
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
D/PMS     (  907): releaseWL(422aa560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
I/PSReceiver( 3305): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1296): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1112): stop update clock
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/LocationManagerService(  907): request 42514b10 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): SET_SCREEN_ON:On
I/wpa_supplicant( 4025): htc_wext_set_keepalive +
I/wpa_supplicant( 4025): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4025): getPrivFuncNum +	
I/wpa_supplicant( 4025): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 4025): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  907):    returned true
I/SmartNS_PSService( 3305): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3305): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3305):  defaultType:0
W/ContextImpl( 3305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4025): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1112): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  907): updateScreenOn: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/ActivityManager(  907): Disable JIT of com.htc.bgp
,I/ActivityManager(  907): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4125 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(439c5c00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(439c5c00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43122a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43122a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3997): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3997): onScreenOn: 1451923453236
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3997): onScreenOn: 1451923453236
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420b9058
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420b9058, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@425c9800
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(43b42e98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/CalendarProvider2( 4125): Created com.android.providers.calendar.CalendarAlarmManager@41ad8a28(com.android.providers.calendar.HtcCalendarProvider@41ac0db0)
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20068 mDataStallAlarmIntent=PendingIntent{43bd22b0: PendingIntentRecord{423bf760 android broadcastIntent}}
,D/CalendarProvider2( 4125): wait start:true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4025): SET_SCREEN_ON:Off
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 4025): htc_wext_set_keepalive +
I/wpa_supplicant( 4025): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4025): getPrivFuncNum +	
I/wpa_supplicant( 4025): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4025): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4025): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4025): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4025): htc_wext_set_keepalive - ret = 0
D/AlarmManager(  907): ACTION_SCREEN_OFF,
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): acquireWL(42517170): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/CalendarProvider2( 4125): wait end:false
,D/wpa_supplicant( 4025): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(42517170): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ContactMessageStore( 1218): start background delete task...
D/ContactMessageStore( 1218): size: 0 , 0
D/ContactMessageStore( 1218): Background delete complete
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4144 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] getTotalRam: 1873 Mb
W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(437b1018): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437b1018): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4144): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(43c9ce38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4144 1000 null
D/PMS     (  907): acquireWL(42621b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4144): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(42621b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43c9ce38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3997): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3997): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3997): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3997): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3997): onScreenOff
,D/AutoSetting( 1296): service - mHandler: cancel location update
,D/AutoSetting( 1296): service -           changes count: 0
W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4144): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4144): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4144): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425c9800
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c9800, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425c9800, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425c9800
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42590040 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42590040 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{424f97d0 u0 com.test.thalitest/.MainActivity t2}
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4165 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/PMS     (  907): acquireWL(42398930): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1538/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3381/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3753/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b0ac +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,I/ConnectivityHelper( 1252): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1252/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(44186790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3753/10100)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
D/PMS     (  907): acquireWL(43b6be78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4353e568): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 907 1000 WorkSource{10029}
,D/PMS     (  907): acquireWL(4340c8e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 907 1000 WorkSource{10029}
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42f8cb80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 907 1000 WorkSource{10029}
,D/PMS     (  907): acquireWL(43c71a88): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 907 1000 WorkSource{10029}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43bc3108): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
I/MusicStore( 4165): Database version: 95
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(43f3e668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4190 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/PMS     (  907): releaseWL(44186790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,W/ContextImpl( 4165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/ContextImpl( 4165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/dalvikvm( 1203): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PMS     (  907): acquireWL(431f0b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(431f0b70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(433e88d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/dalvikvm( 1203): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/GoogleURLConnFactory( 1203): Using platform SSLCertificateSocketFactory
,D/PMS     (  907): releaseWL(433e88d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426506f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ba13 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(426506f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/CalendarProvider2( 4125): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4125): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42584eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  907): releaseWL(42584eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1961): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43e47110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24406, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 106894, reason: UserStart
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(43c71a88): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
W/ContextImpl( 4165): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1538/10029)
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(425eb4b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4165, uid=10154, userID:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/PMS     (  907): releaseWL(43e47110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(437d6608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
E/Auth.Api.Credentials( 1961): [CredentialSyncAdapter] Unknown sync event.
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43b6be78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/MediaRouterService(  907): Client com.google.android.music (pid 4165): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/PMS     (  907): releaseWL(437d6608): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43b20200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/MediaRouter( 4165): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/GamesSyncServiceMain( 1961): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 1961): Failed to execute periodic sync, missing client context - aborting
,D/PMS     (  907): releaseWL(425eb4b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432ec3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,I/NetworkMonitor( 4165): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4165/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2150/10021)
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(432ec3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4222 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/PMS     (  907): acquireWL(425ef9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,D/MediaRouter( 4165): getSelectedRoute
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,I/NetworkMonitor( 4165): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4165/10154)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(425ef9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4370d788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1203): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4165, uid=10154, userID:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/DelayedSyncController( 4190): Delaying sync.
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43b20200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(441848c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=3753
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4340c8e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,I/ActivityManager(  907): Killing 3753:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3753
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/PMS     (  907): acquireWL(431a6800): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 907 1000 WorkSource{10029}
D/PMS     (  907): releaseWL(441848c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/IntentController( 1112): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4243e4d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4353e568): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  907): acquireWL(4239aec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ACRA    ( 4222): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ACRA    ( 4222): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ACRA    ( 4222): Looking for error files in /data/data/com.facebook.katana/app_minidumps
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  907): acquireWL(4260b0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 907 1000 WorkSource{10029}
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4243e4d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(41f8ff90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(41f8ff90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(4370d788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4259edc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/Process (  907): killProcessQuiet, pid=3773
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(43bc3108): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  907): Killing 3773:com.htc.backup/1000 (adj 15): empty #17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PhoneStatusBar( 1112): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4259edc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(423dc300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(423dc300): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4365fde8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4365fde8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/SystemClassLoaderAdder( 4222): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
D/libc    ( 1203): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1203): [NET] getaddrinfo-, 1
D/libc    ( 1203): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =ec93 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,V/DexLibLoader( 4222): Preparing secondary program dexes.
V/DexLibLoader( 4222): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4222): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4222): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4222): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4222): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4222): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4222): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4222): Dex already copied
D/OdexVerifier( 4222): Odex verification is skipped.
,V/DexLibLoader( 4222): Creating class loader
,V/DexLibLoader( 4222): Finished creating class loader
V/DexLibLoader( 4222): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4222): Dex already copied
D/OdexVerifier( 4222): Odex verification is skipped.
,V/DexLibLoader( 4222): Creating class loader
,V/DexLibLoader( 4222): Finished creating class loader
V/DexLibLoader( 4222): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4222): Dex already copied
D/OdexVerifier( 4222): Odex verification is skipped.
,V/DexLibLoader( 4222): Creating class loader
,V/DexLibLoader( 4222): Finished creating class loader
,V/DexLibLoader( 4222): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4222): Dex already copied
D/OdexVerifier( 4222): Odex verification is skipped.
,V/DexLibLoader( 4222): Creating class loader
,V/DexLibLoader( 4222): Finished creating class loader
,V/DexLibLoader( 4222): Verifying classes from secondary dexes.
,I/ActivityManager(  907): Recipient 3773
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/DriveInitializer( 1961): Awaiting to be initialized
,W/DriveInitializer( 1961): Background init thread started
,D/DexLibLoader( 4222): DexLibLoader.ensureDexLoaded took 135 ms
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1961): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,W/dalvikvm( 1353): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1353): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1353): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1353): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
D/libc    ( 1353): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5eac +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,W/DriveInitializer( 1961): Background init thread ended
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42647d10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [2][0][0]
,D/PMS     (  907): releaseWL(431a6800): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(43b79838): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 907 1000 WorkSource{10096}
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/DelayedSyncController( 4190): Delaying sync.
D/PMS     (  907): releaseWL(42647d10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b3d3b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(43b3d3b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43484b68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43b79838): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43484b68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43668000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42f8cb80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(4396dc18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 907 1000 WorkSource{10029}
D/PMS     (  907): releaseWL(43668000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43c8d618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4260b0d8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  907): releaseWL(43c8d618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(440ea9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(440ea9b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/BTIF_CORE( 3933): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3933): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3933): Wake lock released
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44093458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4396dc18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1112): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  907): releaseWL(44093458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1112): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 4222): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4222): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2958 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,E/FbInjectorInitializer( 4222): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4222): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4222): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4222): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3790
,I/ActivityManager(  907): Killing 3790:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Recipient 3790
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1296): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1296/10055)
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4270 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1296): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1296): service - onStartCommand() screen is off, don't request location
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1296/10055)
D/AutoSetting( 1296): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1296): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4222): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4222): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4222): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4270): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4270): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4270): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4270): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4270/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4270/10079)
,I/DeviceManagement( 3740): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4270/10079)
,D/PMS     (  907): acquireWL(43459d10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 3740): WorkflowService: Starting workflow service
I/DeviceManagement( 3740): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41c72590] args=[Bundle[mParcelledData.dataSize=804]]
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4285 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [4][0][0]
I/DeviceManagement( 3740): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 3740): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 3740): NetworkChangeWorkflow: ==================================================
,I/DeviceManagement( 3740): SessionStateController: Checking invariants...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/PMS     (  907): acquireWL(42fc2508): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1451336015456 min interval config: 0 actual interval: 587441162
D/PMS     (  907): releaseWL(43459d10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1961): Checking schedule, now: 1451923456625 next: 1451336045413
,I/CheckinService( 1961): active receiver: enabled
I/CheckinService( 1961): Preparing to send checkin request
,I/EventLogService( 1961): Accumulating logs since 1451923428995
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,I/DeviceManagement( 3740): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 3740): Perf: *** Cache update - start...
,I/DeviceManagement( 3740): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3740): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3740): Perf: *** Enabled app cache update - complete: 1 ms
,I/DeviceManagement( 3740): Perf: *** Config cache update - start...
I/DeviceManagement( 3740): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3740): ConfigCacheController: *** Updating stale config cache entries...
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4285): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3740): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 3740): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
W/dalvikvm( 3740): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4285): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4285): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/dalvikvm( 4222): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4222): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4222): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4222): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4222): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4222): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4222): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4222): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4222): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4222): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4222): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4222): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4222): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4222): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4285): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4222): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4222): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4222): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4222): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiService(  907): New client listening to asynchronous messages
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4285): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/System.err( 3740): Starting the internal HTTP client
I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.reportagent/versions/687983cc-3a99-4a94-8c51-4a06dce9d091/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNzE2Wg
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 9.959MB for 84664-byte allocation
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 9.986MB for 39954-byte allocation
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/BuildInfo( 3740): Created new instance: com.htc.cs.lib.hms.BuildInfo@41d94980
,I/DeviceManagement( 3740): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4285/10151)
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1961/10029)
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 10.062MB for 79892-byte allocation
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,V/WebViewChromiumFactoryProvider( 4285): Binding Chromium to main looper Looper (main, tid 1) {41a95970}
,I/LibraryLoader( 4285): Expected native library version number "",actual native library version number ""
,I/chromium( 4285): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4285): Initializing chromium process, renderers=0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(431f0a10): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  907): releaseWL(431f0a10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4285): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(43580e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 10.089MB for 28144-byte allocation
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
I/Adreno-EGL( 4285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4285): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4285): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4285): Local Branch: 
I/Adreno-EGL( 4285): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4285): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4285):                  aa63bbd948f41d15fc72f585e
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2955 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/NSApplication( 4285): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4285/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4285/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
,D/libc    ( 1353): [NET] getaddrinfo_proxy+
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1dd8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
,D/Process (  907): killProcessQuiet, pid=3826
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3507/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3507/10160)
I/ActivityManager(  907): Killing 3826:com.htc.calendar/u0a13 (adj 15): empty #17
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1451336015456 min interval config: 0 actual interval: 587441468
D/PMS     (  907): acquireWL(42fc6080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Recipient 3826
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(42fc6080): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/iu.SyncManager( 1961): SYNC; picasa accounts
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42a46668 u0 ReceiverList{42a46548 4222 com.facebook.katana/10027/u0 remote:42a461a8}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44069b98 u0 ReceiverList{44069b38 4222 com.facebook.katana/10027/u0 remote:4401c7d8}}
,D/NetworkLogImpl( 1961): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 1961): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,I/iu.UploadsManager( 1961): num queued entries: 0
,I/iu.UploadsManager( 1961): num updated entries: 0
,I/iu.SyncManager( 1961): NEXT; no task
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4339 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): acquireWL(4365f490): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
D/libc    ( 1353): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =54ee +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/CalendarApplication( 4339): onCreate
D/ProviderChangeReceiver( 4339): ---------------------------------------------------
,D/ProviderChangeReceiver( 4339): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4339): start to updateAlertNotification!
D/PMS     (  907): acquireWL(4375ca08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4375ca08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 4339): No fired or scheduled alerts
,D/HtcAlertUtils( 4339): -- cancelReminderNotification --
,D/HtcAlertUtils( 4339): broadcastExistReminder!
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1353): [NET] getaddrinfo-, 1
D/libc    ( 1353): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =312c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4360 uid=10041 gids={50041}
,I/ActivityManager(  907): Killing 3586:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3586
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  907): killProcessQuiet, pid=3536
,I/ActivityManager(  907): Killing 3536:com.android.vending/u0a74 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3586
,I/ActivityManager(  907): Recipient 3536
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Choreographer( 3888): Skipped 523 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 3888): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3888): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa6178 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  907): releaseWL(43b42e98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 3888): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4222): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4222): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4222): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 129
D/libc    (  364): [NET]res_nsend:resplen=104
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13721
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 283
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    ( 1203): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  907): [NET] getaddrinfo_proxy-, success
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,D/GpsLocationProvider(  907): NTP server returned: 1451923453519 (Mon Jan 04 17:04:13 CET 2016) reference: 111759 certainty: 22 system time offset: -5636
,D/GpsLocationProvider(  907): [handleMessage] INJECT_NTP_TIME_FINISHED
,D/GpsLocationProvider(  907): reportAGpsStatus with type = 12090status = 30767ipAddr = [B@425b6a08ssid = nullpassword = null
D/GpsLocationProvider(  907): [handleMessage] REPORT_AGPS_STATUS
D/GpsLocationProvider(  907): handleReportAgpsStatus with type = 12090status = 30767ipAddr = [B@425b6a08ssid = password = null
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 12090
D/GpsLocationProvider(  907): reportAGpsStatus agpsConnInfo is null for type 12090
,D/GpsLocationProvider(  907): xtraDownloadRequest
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): releaseWL(42398930): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  907): acquireWL(43c36568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2567 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 37
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/PMS     (  907): acquireWL(43b0bfe0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4165 10154 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,W/ContextImpl( 4165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4165, uid=10154, userID:0
,D/PMS     (  907): releaseWL(43b0bfe0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4165): Conditions not met for autocaching.
I/MusicLeanback( 4165): Stop autocaching.
W/fb4a(:<default>):UserScope( 4222): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/ContextImpl( 4165): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/fb4a(:<default>):UserScope( 4222): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=5 [53][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,W/dalvikvm( 1961): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,E/fb4a(:<default>):LocalFbBroadcastManager( 4222): Called registerBroadcastReceiver twice.
,D/libc    ( 1203): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,W/PhenotypeConfigurator( 1203): Server returned 404
,D/PMS     (  907): releaseWL(43f3e668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4222): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4222): [NET] getaddrinfo-,err=8
D/libc    ( 4222): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4222): [NET] getaddrinfo-, 1
D/libc    ( 4222): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bb36 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): acquireWL(43574818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 36
D/libc    (  364): [NET]res_nsend:resplen=74
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4222): [NET] getaddrinfo_proxy-, success
,I/global  ( 4222): call createSocket() return a new socket.
D/libc    ( 4222): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4222): [NET] getaddrinfo-, SUCCESS
D/PMS     (  907): releaseWL(43580e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(43574818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4260aae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=15 [13][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=100 [1][1][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(4260aae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=204
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4222): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4222): [NET] getaddrinfo-,err=8
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4222): Grow heap (frag case) to 10.992MB for 32784-byte allocation
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 296
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
,D/PMS     (  907): acquireWL(4340a368): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4222 10027 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1353): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4222/10027)
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,D/libc    ( 1353): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4251c148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=14 [42][6][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/libc    ( 1353): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1353): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,I/GCM     ( 1353): GCM config loaded
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): acquireWL(42fcd128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1203): Vacuum at: now=1451923460304 tag=VacuumService
,D/libc    ( 1961): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 1961): [NET] getaddrinfo-,err=8
D/libc    ( 1961): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 1961): [NET] getaddrinfo-, 1
D/libc    ( 1961): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d6ea +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(4251c148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4312f948): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): releaseWL(4365f490): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 282
D/libc    (  364): [NET]res_nsend:resplen=86
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1961): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/PMS     (  907): releaseWL(4312f948): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4405 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/PMS     (  907): releaseWL(42fcd128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 3740): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3740): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3740): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 3740): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3740): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3740): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
,W/dalvikvm( 3740): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 3740): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3740): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
,W/dalvikvm( 3740): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3740): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 3740): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,D/PMS     (  907): acquireWL(43c98988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
D/libc    ( 1961): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1961): [NET] getaddrinfo-,err=8
D/PMS     (  907): acquireWL(42609be8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4417 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PMS     (  907): releaseWL(43c98988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
,D/PMS     (  907): acquireWL(431f0bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=11 [9][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(42609be8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(431f0bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43935138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4417): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4417): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4417): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4417): install
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,I/MultiDex( 4417): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4417): loading existing secondary dex files
,I/MultiDex( 4417): load found 3 secondary dex files
,D/PMS     (  907): acquireWL(43b71418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
I/MultiDex( 4417): install done
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
D/PMS     (  907): releaseWL(43b71418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43935138): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433310b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1961): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 1961): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
W/dalvikvm( 4417): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4417): VFY: unable to resolve instance field 36
,W/dalvikvm( 4417): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
I/Babel   ( 4405): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4405): MmsConfig.loadMmsSettings
W/dalvikvm( 4405): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4417): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/dalvikvm( 4405): VFY: unable to resolve instance field 36
,W/dalvikvm( 4405): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(433310b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/JNIHelp ( 4405): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c1eb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4446 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4405, uid=10111, userID:0
,W/Settings( 4405): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4405, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4405, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4405, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4405, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4405, uid=10111, userID:0
,D/MessageFrequencyProvider( 4446): onCreate
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,V/GetPrviateResource( 4446): GetPrviateResource
D/MmsCustomizationProvider( 4446): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4446): GetPrviateResource
,D/MmsCustomizationProvider( 4446): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ProviderInstaller( 4417): Installed default security provider GmsCore_OpenSSL
,I/ProviderInstaller( 4405): Installed default security provider GmsCore_OpenSSL
I/Babel   ( 4405): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4405): MmsConfig.loadFromDatabase
D/PMS     (  907): releaseWL(4239aec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(440eeb48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
E/Babel   ( 4405): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4405): MmsConfig.loadFromResources
,E/Babel   ( 4405): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4405): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(440eeb48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4405/10111)
W/dalvikvm( 4417): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 4417): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Process (  907): killProcessQuiet, pid=3859
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,W/dalvikvm( 4417): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4417): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4417): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4417): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4417): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Killing 3859:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4405/10111)
I/ActivityManager(  907): Recipient 3859
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 4446): sense_version=6.0
,D/BTAccessoryUtil( 4446): createReceiver
,D/BTAccessoryUtil( 4446): registerReceiver return intent = null
D/MessageCustFlag( 4446): sku_id=99
,W/SystemReader( 4446): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4446): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4446): networkCode: 
,D/MessageCustFlag( 4446): sku_id=99
D/MmsConfig( 4446): SIE smsPri: null
,D/MmsConfig( 4446): networkCode: 
,D/HtcTelephonyCapability( 4446): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4446): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4446): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4446): Cannot find qct_8960_interface, use default value instead
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4417): Install completed successfully. count=14 extracted=0
,W/dalvikvm( 4417): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4417): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 4417): Using platform SSLCertificateSocketFactory
,D/libc    ( 4417): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4417): [NET] getaddrinfo-,err=8
D/libc    ( 4417): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4417): [NET] getaddrinfo-, 1
,D/libc    ( 4417): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7b82 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4417): [NET] getaddrinfo_proxy-, success
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3649943920
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=9 [11][1][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/libc    ( 4417): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4417): [NET] getaddrinfo-,err=8
D/libc    ( 4417): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4417): [NET] getaddrinfo-,err=8
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=14 [14][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/Process (  907): killProcessQuiet, pid=3381
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
I/ActivityManager(  907): Killing 3381:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  907): Recipient 3381
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =350b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4405): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4405): [NET] getaddrinfo-,err=8
D/libc    ( 4405): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4405): [NET] getaddrinfo-, 1
,D/libc    ( 4405): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7c0e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4405): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4405): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4405): [NET] getaddrinfo-,err=8
,W/Settings( 4417): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=6 [29][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fd2c +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,I/global  ( 4222): I/O error closing connection
I/global  ( 4222): java.net.SocketException: Socket is closed
I/global  ( 4222): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4222): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4222): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4222): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4222): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4222): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4222): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4222): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4222): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4222): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4222): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4222): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4222): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4222): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4222): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4222): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4222): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4222): Removing a connection that never existed!
D/PMS     (  907): releaseWL(4340a368): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/PMS     (  907): acquireWL(4347fff8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4405 10111 null
,I/GAV2    ( 4285): Thread[GAThread,5,main]: No campaign data found.
,I/Babel   ( 4405): Account registration complete:Redacted-21
,D/PMS     (  907): releaseWL(4347fff8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/Adreno-EGL( 4417): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4417): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4417): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4417): Local Branch: 
I/Adreno-EGL( 4417): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4417): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4417):                  aa63bbd948f41d15fc72f585e
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=6 [15][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/libc    (  364): [NET]Querying server xid =b0ac (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
I/WVCdm   (  371): CdmEngine::OpenSession
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1aaa +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/libc    (  364): [NET]res_nsend:resplen=104
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,D/DotMatrix( 1526): [EventService] EVENT_RESET_THEME_TIMESTAMP
,I/FeedActionBar( 1252): updateLastUpdatedTime(in String) LAST UPDATED 17:02
,I/IntentController( 1112): receive(android.intent.action.TIME_SET,4,false)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/DotMatrix( 1526): [EventService] isTheSameDay:false,timestamp is early than today:true
,D/WVCdm   (  371): PrepareKeyRequest: nonce=4125533595
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4417/10029)
,I/Adreno-EGL( 4417): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4417): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4417): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4417): Local Branch: 
I/Adreno-EGL( 4417): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4417): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4417):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4417): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4417): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4417): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4417): Local Branch: 
I/Adreno-EGL( 4417): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4417): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4417):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,D/libc    ( 1961): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1961): [NET] getaddrinfo-,err=8
D/libc    ( 1961): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1961): [NET] getaddrinfo-, 1
,D/libc    ( 1961): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8959 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1961): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1961): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1961): [NET] getaddrinfo-,err=8
,D/Messaging( 4446): mNeedToUpdateDate2 start
,D/MmsConfig( 4446): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4446): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4446): 
D/MmsAsyncWorkHandler( 4446): HM tk = 20001
D/ReportIndicatorCache( 4446): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4446): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aa8098
,I/Messaging( 4446): mccmnc> 
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/DraftCache( 4446): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4446): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsConfig( 4446): networkCode: 
,D/Messaging( 4446): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4446): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4446): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4446): createReceiver
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1218): sku_id=99
,D/MessageCustFlag( 4446): sense_version=6.0
,D/Jerry   ( 4446): start to preload cursor >>>>>>>
D/TelephUtils( 1218): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1218): Update uri=content://mms, match=0
,V/MmsProvider( 1218): selection=st=129 AND m_type!=134
,D/DraftCache( 4446): [DraftCache/436] rebuildCache
D/Messaging( 4446): Reset downloading state: 0
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,V/MmsSystemEventReceiver( 4446): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
I/ActivityManager(  907): Delaying start of: ServiceRecord{43b66bf8 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/Messaging( 4446): mNeedToUpdateDate2: false
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/libc    ( 1961): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1961): [NET] getaddrinfo-,err=8
D/libc    ( 1961): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1961): [NET] getaddrinfo-,err=8
,D/Messaging( 4446): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/Jerry   ( 1218): URI_DRAFT
D/Messaging( 4446): ViewCache CreatePreload
,D/Messaging( 4446): ViewCache CreatePreloadOnlyMultipleOpsList
I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,D/Cust_MMSMS( 4446): _has_set_default_values_2=true
D/DraftCache( 4446): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4446): [DraftCache/436] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4446): 
D/MmsAsyncWorkHandler( 4446): HM tk = 20002
,D/MsgPreferenceUtils( 4446): def_index: 0
,D/MsgPreferenceUtils( 4446): globalIndex = 1
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1218): sku_id=99
D/MsgPreferenceUtils( 4446): phone state: true
D/MsgPreferenceUtils( 4446): sd state: false
,D/MsgPreferenceUtils( 4446): vIndex = 0
,I/CheckinTask( 1961): Sending checkin request (13216 bytes)
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1218): sku_id=99
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=10 [30][3][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =77f +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1961/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=18 [11][2][0]
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/CheckinTask( 1961): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1961): Checking schedule, now: 1451923457915 next: 1452446394908
,I/CheckinService( 1961): active receiver: disabled
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=20 [5][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
I/CheckinService( 1961): Checking schedule, now: 1451923457946 next: 1452446394908
,I/CheckinService( 1961): active receiver: disabled
D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/CheckinService( 1961): Recording last checkin time for package unspecified as 1451923457953
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =153a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/PMS     (  907): releaseWL(42fc2508): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=8 [12][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cdb0 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  907): releaseWL(43c36568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,I/DeviceManagement( 3740): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,I/DeviceManagement( 3740): DeviceClientResource: Active network...
I/DeviceManagement( 3740):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=7 [14][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.cs.dm (3740/10098)
,D/libc    ( 3740): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  364): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3740): [NET] getaddrinfo-,err=8
D/libc    ( 3740): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3740): [NET] getaddrinfo-, 1
,D/libc    ( 3740): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7ec2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3740): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 3740): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3740): DeviceClientResourceController: handleDirectives: []
I/System.out( 3740): isCompatible false
I/System.out( 3740): createObjectMapper
,I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
I/System.out( 3740): isCompatible false
,I/System.out( 3740): isCompatible false
,D/DraftCache( 4446): [DraftCache/1] refresh
,D/ContactMessageStore( 1218): notify MmsSms
D/AccFlag ( 1218): sense_version=6.0
,D/AccFlag ( 1218): sku_id=99
D/PMS     (  907): acquireWL(4367be28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029}
V/AlarmManager(  907): sending alarm PendingIntent{421882a8: PendingIntentRecord{4374dcb8 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  907): releaseWL(4367be28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 68
,D/AccFlag ( 1218): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,I/DeviceManagement( 3740): ConfigCacheController: *** Update config cache: updating 9 entries...
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, statusCode=0, authCode=0>
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 67
,D/AccFlag ( 1218): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,D/PMS     (  907): acquireWL(4411e208): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4411e208): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44109e60): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,I/DeviceManagement( 3740): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3740): AlarmController: Scheduling TTL alarm for: 2016.01.05 at 17:04:19.788 CET (due to: com.htc.launcher)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3740, uid=10098, userID:0
,I/DeviceManagement( 3740): Perf: *** Config cache update - complete: 8884 ms
I/DeviceManagement( 3740): Perf: *** Cache update - complete: 8886 ms
,I/DeviceManagement( 3740): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41c72590]
,I/DeviceManagement( 3740): WorkflowService: Stopping workflow service
,D/Process (  907): killProcessQuiet, pid=4027
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4027:com.htc.widget.process2/u0a50 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4027
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DraftCache( 4446): [DraftCache/436] rebuildCache
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/Jerry   ( 1218): URI_DRAFT
,D/DraftCache( 4446): hasDraft() = false mNeedNotifyChange = false
,D/DraftCache( 4446): [DraftCache/436] rebuildCache time: 3
,I/Icing   ( 1961): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 1961): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  907): releaseWL(44109e60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/TransactionService( 4446): 1-Creating TransactionService
,V/TransactionService( 4446): onStartCommand: 1
,D/MmsSystemEventReceiver( 4446): unRegisterForConnectionStateChanges
V/TransactionService( 4446): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4446): Loading previous transactions.
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1218): device_type: 1
,D/TransactionService( 4446): Force set service start id to 1
V/TransactionService( 4446): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4446): unRegisterForConnectionStateChanges
,V/TransactionService( 4446): Destroying TransactionService
,D/TransactionService( 4446): stopSelfResult: true, mLastHandledServiceId: 1
,I/ActivityManager(  907): Resuming delayed broadcast
,V/TransactionService( 4446): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/PMS     (  907): acquireWL(43d88458): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1353): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): releaseWL(43d88458): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10029 com.google.android.gms},
,D/WearableService( 1203): callingUid 10029, callindPid: 1203
,D/LocationInitializer( 1961): Restart initialization of location
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/MDM     ( 1203): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  907): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1353): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1353): Proximity feature is not enabled.
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1203): location=null
D/PMS     (  907): acquireWL(4257c348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4257c348): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): acquireWL(42611ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/AlertReceiver( 4339): beginStartingService
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [17][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
D/PMS     (  907): acquireWL(420cc738): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 4339 10013 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/AlertService( 4339): start to updateAlertNotification!
D/PMS     (  907): releaseWL(42611ee0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AlertService( 4339): No fired or scheduled alerts
,D/HtcAlertUtils( 4339): -- cancelReminderNotification --
,D/HtcAlertUtils( 4339): broadcastExistReminder!
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4544 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 4339): stopSelfResult true
D/PMS     (  907): releaseWL(420cc738): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/WeatherRequest( 1112): request cur loc, but there is no sys cur
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4559 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4544): can't get weather sync account
,W/WeatherRequest( 4544): request cur loc, but there is no sys cur
,W/Settings( 4544): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  907): acquireWL(4343db50): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4559 10071 null
D/PMS     (  907): acquireWL(425aa7b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4559 10071 null
D/PMS     (  907): releaseWL(4343db50): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 1 10 17
,I/TodoTaskNotifyService( 4559): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TodoTaskshortcut( 4559): update TASK shortcut>
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4574 uid=10090 gids={50090, 3003, 5012, 1028}
,I/TodoTaskNotifyService( 4559): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4559): stopSelfResult true
D/PMS     (  907): releaseWL(425aa7b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WorldClock.Global( 4574): isHtcDevice = true
,I/WorldClock.Global( 4574): isHtcDevice = true
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4574): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 4574): Cancel any alarm from alarm manager
,I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4590 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4574): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/GAV4    ( 4405): Thread[GAThread,5,main]: No campaign data found.
,I/IntentController( 1112): receive(android.intent.action.ALARM_CHANGED,1,false)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4405, uid=10111, userID:0
,D/Process (  907): killProcessQuiet, pid=3958
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3958:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3977
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3977:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3958
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3977
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TimeService( 4590): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923461728
,D/PMS     (  907): acquireWL(44092530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10014}
,V/AlarmManager(  907): sending alarm PendingIntent{425617c8: PendingIntentRecord{437618c0 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=119821, Int=0
,D/Process (  907): killProcessQuiet, pid=3305
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3305:com.android.settings/1000 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4144
,I/ActivityManager(  907): Killing 4144:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  907): acquireWL(433c33e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms},
I/ActivityManager(  907): Recipient 4144
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Recipient 3305
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(43b6a450): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1451923457953 min interval config: 0 actual interval: 4108
D/PMS     (  907): releaseWL(433c33e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(43b6a450): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(430c4b88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1961 10029 null
,D/PMS     (  907): acquireWL(43c9c5b8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
D/PMS     (  907): releaseWL(430c4b88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  907): releaseWL(43c9c5b8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=4270
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4270:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4270
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
,D/GCM     ( 1353): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4608 uid=10078 gids={50078}
,D/SMSBackup( 4608): Got a database change event
,D/PMS     (  907): acquireWL(4408a950): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4559 10071 null
,D/PMS     (  907): acquireWL(4305b7b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4559 10071 null
,D/PMS     (  907): acquireWL(440b4440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4559 10071 null
E/TodoTaskNotifyService( 4559): java.lang.NullPointerException
W/System.err( 4559): java.lang.NullPointerException
W/System.err( 4559): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 4559): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4559): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4559): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4559): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4559): stopSelfResult false
E/TodoTaskNotifyService( 4559): java.lang.NullPointerException
W/System.err( 4559): java.lang.NullPointerException
W/System.err( 4559): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4559): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 4559): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4559): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4559): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4559): mStartingService is null
D/PMS     (  907): releaseWL(4408a950): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): acquireWL(4305b7b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4559 10071 null
D/PMS     (  907): releaseWL(440b4440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  907): releaseWL(4305b7b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4559): stopSelfResult true
D/PMS     (  907): acquireWL(43a8a7e0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4125 10014 null
,D/PMS     (  907): releaseWL(44092530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(43a8a7e0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/Process (  907): killProcessQuiet, pid=4190
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4190:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4190
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{440f24d8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1252): AllAppsMgr addApps, already exist: ApplicationInfo(id=38, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/Launcher( 1252): Deferring update until onResume
,D/Launcher( 1252): waitUntilResume // bindAppsUpdated
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1252): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/Launcher( 1252): Deferring update until onResume
D/Launcher( 1252): waitUntilResume // bindAppsUpdated
,I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PMS     (  907): acquireWL(4229ef98): PARTIAL_WAKE_LOCK  AsyncService 0x1 3507 10160 null
,D/PMS     (  907): releaseWL(4229ef98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4628 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/dalvikvm-heap( 3507): Grow heap (frag case) to 13.508MB for 1821008-byte allocation
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/HtcFingerPrintQuickLaunchProvider( 4628): -onCreate()
,V/Settings:HtcSettingsApplication( 4628): [4628/4628] onCreate()
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4643 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3740
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3740:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3740
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/Settings:HtcWirelessFeatureFlags( 4628): id/is att sku: 99/false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/SystemReader( 4628): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
W/SystemReader( 4628): Cannot find support_harman, use default value instead
,W/SystemReader( 4628): Cannot find effect_manager_id, use default value instead
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,E/Settings:HtcWrapHeaderInfo( 4628): no such activity!
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/PackageManager(  907): Unable to load service info ResolveInfo{440f6cb8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4628): The wrap header doesn't exist in header list.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4643, uid=10074, userID:0
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/Settings:HtcWrapHeaderInfo( 4628): updateDevelopment, bPrefShow = true
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/Settings:HtcUmcWidgetEnabler( 4628): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]support         :false
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
,D/Finsky  ( 4643): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4643/10074)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/FingerprintManager( 4628): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4628): isSupportVoWifi: null
E/ActivityThread( 4628): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4643/10074)
,D/Finsky  ( 4643): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,W/Settings( 4643): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4643): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4643): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4643, uid=10074, userID:0
,D/Finsky  ( 4643): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 4643): Skipping gmscore version check
,D/Finsky  ( 4643): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4643): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4643): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4643): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
D/PMS     (  907): acquireWL(43c72518): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4405 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4628): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4628): updateDevelopment, bPrefShow = true
D/PMS     (  907): acquireWL(4259f078): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,E/Settings:HtcUmcWidgetEnabler( 4628): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportRecentAppsButton]support         :false
,D/Process (  907): killProcessQuiet, pid=4285
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(43c72518): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1961, uid=10029, userID:0
I/ActivityManager(  907): Killing 4285:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/PMS     (  907): releaseWL(4259f078): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4628): [supportHomeButton]support         :false
I/ActivityManager(  907): Resuming delayed broadcast
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/FingerprintManager( 4628): hasFingerprint() - sSensorCode = 0
,W/PackageManager(  907): Unable to load service info ResolveInfo{43057b70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  907): acquireWL(4329bf18): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4329bf18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4628): isSupportVoWifi: null
I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
E/ActivityThread( 4628): Failed to find provider info for com.htc.vowifi
D/PMS     (  907): acquireWL(4367ba70): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/PackageManager(  907): Unable to load service info ResolveInfo{439a61d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(43b6b280): PARTIAL_WAKE_LOCK  AsyncService 0x1 3507 10160 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4285
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
I/dalvikvm-heap( 3507): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
D/RemoteDisplayProvider(  907): start
D/PMS     (  907): releaseWL(43b6b280): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm-heap( 3507): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1961): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  907): acquireWL(430bbde8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3507 10160 null
,I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  907): releaseWL(430bbde8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42656b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42656b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-,err=8
D/libc    ( 4643): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4643): [NET] getaddrinfo-, 1
D/libc    ( 4643): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7c2c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  907): acquireWL(440efbb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(440efbb8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(4303d908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(430547c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4303d908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(430547c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 278
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4643): [NET] getaddrinfo_proxy-, success
,W/SQLiteConnectionPool( 1961): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 496 ms] updated apps [took 495 ms] 
,I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 +
,I/Prism.WidgetManager( 1252): onLoadItems() +
,I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 66 ms] updated apps [took 65 ms] 
,D/PMS     (  907): acquireWL(440e3960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{4246eb88: PendingIntentRecord{425965c0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451923469817, Int=0
,D/Finsky  ( 4643): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4643): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  907): releaseWL(440e3960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4643/10074)
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4643): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-,err=8
D/libc    ( 4643): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4643): [NET] getaddrinfo-, 1
D/libc    ( 4643): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3a4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4643): [NET] getaddrinfo_proxy-, success
I/global  ( 4643): call createSocket() return a new socket.
D/libc    ( 4643): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-, SUCCESS
,E/Prism.WidgetManager( 1252): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1252): onLoadItems() -
,I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 -
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/libc    ( 4643): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4643): [NET] getaddrinfo-,err=8
,I/Icing   ( 1961): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1961): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,W/NetworkManagementSocketTagger( 4643): untagSocket(73) failed with errno -22
,D/Finsky  ( 4643): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/Icing   ( 1961): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1961): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1961): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1961): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(4367ba70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/NetworkManagementSocketTagger( 4643): untagSocket(73) failed with errno -22
,D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1218): -- N1 =0
,D/PhoneApp( 1218): -- N2 =0
,D/PhoneApp( 1218): -- N3 =0
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 +
,I/Prism.WidgetManager( 1252): onLoadItems() +
,W/NetworkManagementSocketTagger( 4643): untagSocket(73) failed with errno -22
,E/Prism.WidgetManager( 1252): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1252): onLoadItems() -
,I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 -
,D/Finsky  ( 4643): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  ( 4643): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4643/10074)
,D/Finsky  ( 4643): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  907): acquireWL(42269a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{42348d08: PendingIntentRecord{42352908 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1451923472146, Int=0
,D/PMS     (  907): acquireWL(424d4be0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4643 10074 null
,D/WearableService( 1203): callingUid 10029, callindPid: 1203
,D/Finsky  ( 4643): [486] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  907): releaseWL(42269a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4643/10074)
,D/Finsky  ( 4643): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/DeviceConnectionService( 1203): client connected with version: 8296000
,D/Finsky  ( 4643): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.vending.verifier.VerifyInstalledPackagesReceiver
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4643): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4643): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1353): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(424d4be0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 +
,I/Prism.WidgetManager( 1252): onLoadItems() +
,D/PMS     (  907): acquireWL(44090520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44090520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PowerUI ( 1112): closing low battery warning: level=100
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/Prism.WidgetManager( 1252): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1252): onLoadItems() -
,I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 -
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(440f1090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{424b7888: PendingIntentRecord{439df508 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136104, Int=0
,D/PMS     (  907): releaseWL(440f1090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): acquireWL(44098d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=3 [96][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): acquireWL(43b73190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43b73190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(431a6b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44098d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42621b40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(42621b40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,I/PhenotypeConfigurator( 1203): Scheduling Phenotype for one-off execution 10510 seconds from now (1451923478480)
,D/GetConfigurationSnapshotOperation( 1203): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1203): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1203): Using platform SSLCertificateSocketFactory
,D/PMS     (  907): acquireWL(42562160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41ceeeb8: PendingIntentRecord{4248b200 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=136799, Int=0
,D/PMS     (  907): acquireWL(42fa7088): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(42562160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(420fd2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(42fa7088): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(420fd2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1203): [NET] getaddrinfo-, 1
D/libc    ( 1203): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =736 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1203): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
D/libc    ( 1203): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1203): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(431a6b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423ded20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(423ded20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4257a220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4025): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(4257a220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1296): service - has update message, not stop
,D/AutoSetting( 1296): service - mHandler: update timezone
,D/AutoSetting( 4125): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4125): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4125): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4125): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4125): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4125): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4125): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4125): service - mHandler: update timezone
,D/AutoSetting( 4125): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4125): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4125): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4125): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41becf70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 2 8 2 11
,D/PMS     (  907): acquireWL(43b25858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43b25858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44090bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{421de8a8: PendingIntentRecord{433eb170 com.android.vending startService}}, i=null, t=0, cnt=1, w=1451923486245, Int=0
,D/PMS     (  907): releaseWL(44090bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4643): [476] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4643): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43409c00 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(42595468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42595468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4268c770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41ceeeb8: PendingIntentRecord{4248b200 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=166807, Int=0
,D/PMS     (  907): acquireWL(43b6aff0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(4268c770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42fb9848): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4025): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4025): nl80211: survey data missing!
E/wpa_supplicant( 4025): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4025): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(43a97b68): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 907 1000 WorkSource{10029}
,D/PMS     (  907): releaseWL(43b6aff0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42fb9848): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42ff95b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42ff95b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1961): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(422d3140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/SyncManager(  907): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24388, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  907): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 167003, reason: UserStart
D/PMS     (  907): releaseWL(43a97b68): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  907): releaseWL(422d3140): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42ffadf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1538/10029)
,D/PMS     (  907): releaseWL(42ffadf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1296): service - handleMessage() stop self
,D/AutoSetting( 1296): service - onDestroy() END
,D/AutoSetting( 1296): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4165
,I/ActivityManager(  907): Killing 4165:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4165
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 4165): Died!
,D/AutoSetting( 4125): service - handleMessage() stop self
,D/AutoSetting( 4125): service - onDestroy() END
,D/AutoSetting( 4125): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4446
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4446:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4446
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(430f77a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(430f77a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(440468b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41ceeeb8: PendingIntentRecord{4248b200 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=196875, Int=0
,D/PMS     (  907): acquireWL(42fcf4c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(440468b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430564b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42fcf4c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(430564b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(43b092a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b092a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43b11698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b11698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ClearcutLoggerApiImpl( 1353): disconnect managed GoogleApiClient
,D/PMS     (  907): acquireWL(4359c760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4359c760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43baa100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43baa100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43c6e790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c6e790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(426472f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=338077, Int=0
,D/PMS     (  907): releaseWL(426472f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43b78ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b78ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(436d1360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/PMS     (  907): releaseWL(436d1360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4374b4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4374b4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43481c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43481c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4260a0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=458077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4260a0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43244440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43244440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4373e058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=518077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4373e058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(440ba9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440ba9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4312c0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=578077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4312c0a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43bb94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bb94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1218): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1218): sku_id=99
D/ContactMessageStore( 1218): start background delete task...
,D/ContactMessageStore( 1218): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
,D/PMS     (  907): acquireWL(424c7f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424c7f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4222
,I/ActivityManager(  907): Killing 4222:com.facebook.katana/u0a27 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4222
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(431f5a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431f5a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4359e1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=698077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4359e1e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42ffee08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42ffee08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4297d030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=758077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4297d030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(425cee98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425cee98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4303dc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=818077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4303dc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43071ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43071ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42fd93d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=878077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42fd93d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43055590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43055590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4363f0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=938077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4363f0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42672ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42672ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(433c4400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.644MB for 50416-byte allocation
D/PMS     (  907): releaseWL(433c4400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4375d430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41d278a0: PendingIntentRecord{42431228 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784485, Int=0
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4743 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4256fd68: PendingIntentRecord{425c1ae8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1451923558209, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{42345118: PendingIntentRecord{42344f78 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1451924278515, Int=900000
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4754 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  907): sending alarm PendingIntent{425105b8: PendingIntentRecord{43751d50 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1451924353525, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4743/10049)
,W/ContextImpl( 4754): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4754): call getInstance()
,D/PMS     (  907): acquireWL(42fc6758): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4754 1000 null
,D/PowerUsageList:PowerUsageHelper( 4754): MY_DEBUG = false
,D/SmartSyncUtils( 4754): isEpsOn(), nState = 0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(4375d430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4339
,I/ActivityManager(  907): Killing 4339:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): releaseWL(42fc6758): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4754): [updateNmRange] bManual = false
,D/PMS     (  907): acquireWL(43010e90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4754 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4754): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4754): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4754): SettingOnTime = 1451973600000, randomSettingOnTime = 1451971410000
D/SmartSyncScreenOnOffTimeReceiver( 4754): SettingOffTime = 1451959200000, randomSettingOffTime = 1451965078000
D/SmartSyncScreenOnOffTimeReceiver( 4754): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4754): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4754): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(43010e90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  907): Recipient 4339
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=4544
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Killing 4544:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4544
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42249fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{440e0130: PendingIntentRecord{439ac1d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1013008, Int=0
,D/PMS     (  907): acquireWL(41f781a0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41f781a0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42249fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43230458): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1353 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42fcb300): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1353 10029 WorkSource{0 com.google.android.gms}
,I/GCM     ( 1961): Message from null null
,E/GCM     ( 1961): Dropping message from null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/PMS     (  907): releaseWL(42fcb300): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{0 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1353/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1353/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023994
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024119
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024185
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024190
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025447
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025464
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028298
,D/PMS     (  907): releaseWL(43230458): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  907): acquireWL(42459e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42459e08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(423d4198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.692MB for 50416-byte allocation
D/PMS     (  907): releaseWL(423d4198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(420d0e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(420d0e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41cbbe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41cbbe90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43660410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1118077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43660410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424eba48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424eba48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(423e53c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(423e53c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b50108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1178077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b50108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4402a850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): releaseWL(4402a850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(42655760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42655760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44098780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1238077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44098780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41d84d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41d84d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(433c53e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(433c53e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42606c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1298077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.693MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(42606c28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(422ba4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(422ba4a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42ff6fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42ff6fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4347ffb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1358077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4347ffb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41f4ee20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41f4ee20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(423be760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(423be760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425ca300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1418077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425ca300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440bba58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(440bba58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b08490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b08490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b2a928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1478077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b2a928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43672b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43672b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425333f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1538077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425333f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(439a17f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(439a17f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(434596f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(434596f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42c26518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1598077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1252): Grow heap (frag case) to 12.693MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(42c26518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4256d630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4256d630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4365aa70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1658077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4365aa70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437506f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437506f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43437bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1718077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43437bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42fa15d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42fa15d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4359d540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1778077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4359d540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(440e7188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440e7188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(425cd380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425cd380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  907): Prepared write state in 44ms
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2016-01-03-15-35-00.bin
,D/PMS     (  907): acquireWL(425a3f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1838077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425a3f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440698d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440698d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43092960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4209a7a8: PendingIntentRecord{41e6fe60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1898077, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43092960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4793): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4793): ====startRecUseTime====
D/htc.customization.log.level( 4793):  is 
W/CustomizationLogLevel( 4793): Level value is invalid, use default level 2
D/CustomizationManager( 4793):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4793): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4793): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4793): Parsing tag category name = system
I/CustomizationCIDLoader( 4793): Parsing tag category name = application
I/CustomizationCIDLoader( 4793): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4793): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4793): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4793): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4793): Parsing tag category name = Settings
D/CustomizationManager( 4793):  Read CID file spent 0.161 (s)
D/CustomizationManager( 4793):  All configurations done spent 0.162 (s)
W/HtcNativeFlag( 4793): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4793): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4793): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4793): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4793, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3888
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3888:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{424f97d0 u0 com.test.thalitest/.MainActivity t2}
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3888 uid 10389
E/JavaBinder( 1190): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  907): Skipping PackageSetting{421bff50 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/InputDispatcher(  907): channel '42321d98 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '42321d98 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '42321d98 com.test.thalitest.MainActivity (s)'
I/WindowState(  907): WIN DEATH: Window{42321d98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
I/WindowManager(  907): WINDOW DIED Window{42321d98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
W/SystemReader( 1237): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1280): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(43d83050): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43d83050): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/Launcher( 1252): Deferring update until onResume
D/Launcher( 1252): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/[PluginManager]RegisterService( 1296): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1296): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1252): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4809 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(43edf298): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43edf298): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43bd4e38): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 269 ms] updated apps [took 269 ms] 
E/SQLiteDatabase( 4809): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4809): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4809): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4809): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4809): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4809): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4809): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4809): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4809): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4809): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4809): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4809): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4809): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4809): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4809): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4809): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4809): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4809): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4809): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4809): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4809): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4809): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4809): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4809): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4809): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4809): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4809): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4809): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4809): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4809): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4809): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4809): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4809): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4809): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4809): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4809): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4809): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4809): threadid=11: thread exiting with uncaught exception (group=0x41669e30)
E/AndroidRuntime( 4809): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4809): Process: com.google.android.apps.docs, PID: 4809
E/AndroidRuntime( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4809): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4809): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4809): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4809): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4809): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  907): Can't write: system_app_crash
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
D/Process ( 4809): killProcess, pid=4809
D/Process ( 4809): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4827 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4809
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4809) has died.
W/ContextImpl( 4827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4827): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4827): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4827): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4827): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4827): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4827): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4827): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4827): threadid=10: thread exiting with uncaught exception (group=0x41669e30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4840 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4827): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4827): Process: com.android.keychain, PID: 4827
E/AndroidRuntime( 4827): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4827): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4827): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4827): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4827): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4827): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4827): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4827): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4827): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4840): getInstance(Context context)
D/AppTag  ( 4840): getInstance(Context context)
D/Process ( 4827): killProcess, pid=4827
D/Process ( 4827): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1451925253486.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4840): onCreate()
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  907): Recipient 4827
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4827) has died.
D/PMS     (  907): acquireWL(431068f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3507 10160 null
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(431068f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4643): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1961): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1961): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1961): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1961): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6dbd8cb8
E/SQLiteLog( 1961): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1961): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66060db0
W/dalvikvm( 1961): threadid=49: thread exiting with uncaught exception (group=0x41669e30)
E/DriveAsyncService( 1961): disk I/O error (code 3850)
E/DriveAsyncService( 1961): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1961): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1961): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1961): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1961): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1961): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1961): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1961): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1961): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1961): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 1961): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1961): Process: com.google.android.gms, PID: 1961
E/AndroidRuntime( 1961): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1961): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1961): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1961): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1961): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1961): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1961): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1961): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1961): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1961): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1961): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1961): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1961): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1961): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 1961): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1961): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1961): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1961): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 1961): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1961): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1961): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1961): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1961): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1961): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 1961): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 1961): killProcess, pid=1961
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1961): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1252): loadItems() com.htc.launcher.pageview.WidgetManager@41b2beb0 +
I/Prism.WidgetManager( 1252): onLoadItems() +
I/ActivityManager(  907): Recipient 1961
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 1961) has died.
D/WifiService(  907): Client connection lost with reason: 4
D/PMS     (  907): handleWLDeath(43bd4e38): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10997ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10996ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10992ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10991ms
E/SQLiteLog( 1353): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1353): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x66335520
W/dalvikvm( 1353): threadid=1: thread exiting with uncaught exception (group=0x41669e30)
E/AndroidRuntime( 1353): FATAL EXCEPTION: main
E/AndroidRuntime( 1353): Process: com.google.process.gapps, PID: 1353
E/AndroidRuntime( 1353): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1353): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1353): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1353): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1353): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1353): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1353): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1353): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1353): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1353): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1353): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1353): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1353): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1353): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1353): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1353): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1353): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1353): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1353): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1353): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
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
D/Process ( 1353): killProcess, pid=1353
D/Process ( 1353): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4869 uid=10098 gids={50098, 3003, 5012}

```
