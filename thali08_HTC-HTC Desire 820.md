#### Test 50650278c0f6ec2_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  905): acquireWL(43750ea0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  905): releaseWL(43750ea0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(4371aca8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  905): releaseWL(4371aca8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  905): acquireWL(436fbbf8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  905): releaseWL(436fbbf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,--------- beginning of /dev/log/main
I/SensorManager(  905): mEventCount = 1050
E/cutils-trace( 3868): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3868): ====startRecUseTime====
D/htc.customization.log.level( 3868):  is 
W/CustomizationLogLevel( 3868): Level value is invalid, use default level 2
D/CustomizationManager( 3868):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3868): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3868): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3868): Parsing tag category name = system
I/CustomizationCIDLoader( 3868): Parsing tag category name = application
I/CustomizationCIDLoader( 3868): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3868): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3868): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3868): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3868): Parsing tag category name = Settings
D/CustomizationManager( 3868):  Read CID file spent 0.089 (s)
D/CustomizationManager( 3868):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 3868): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3868): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3868): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3868): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3868
D/PMS     (  905): acquireHCC(43ce3788): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(43c74e08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
W/asset   (  905): Copying FileAsset 0x6f1c4c48 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1139370136
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bd8a48
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
D/PMS     (  905): acquireWL(4359ac28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3879 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
W/asset   ( 3879): Copying FileAsset 0x5c7c6690 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 3879): Binding Chromium to main looper Looper (main, tid 1) {41a936b0}
I/LibraryLoader( 3879): Expected native library version number "",actual native library version number ""
I/chromium( 3879): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3879): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423e5528:true
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3879): 1101697256: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): acquireWL(433975f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(43396e10): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(43396e10): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3879): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3879): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3879): Local Branch: 
I/Adreno-EGL( 3879): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3879): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3879):                  aa63bbd948f41d15fc72f585e
W/chromium( 3879): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3879): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3879): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3879): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3879): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3879): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3879): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3879): CordovaWebView is running on device made by: HTC
,W/AwContents( 3879): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  905): Disable input method client, pid=1247
,I/InputMethodManagerService(  905): Enable input method client, pid=3879
W/ResourceType( 3879): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3879): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ada670, mServedView=org.apache.cordova.engine.SystemWebView{41aa0400 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1183): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1183): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1183): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 3879): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  905): Displayed com.test.thalitest/.MainActivity: +273ms
,D/PMS     (  905): releaseWL(4359ac28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3879): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3879): JniHelper::setJavaVM(0x41568048), pthread_self() = 1662090112
,D/JX-Cordova( 3879): jxcore cordova android initializing
,W/dalvikvm( 3879): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 11.552MB for 95956-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 11.630MB for 143930-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 11.746MB for 215890-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 11.919MB for 323830-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 12.193MB for 485740-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 13.193MB for 1092904-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 14.068MB for 1639352-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 15.433MB for 2459024-byte allocation
,I/dalvikvm-heap( 3879): Grow heap (frag case) to 17.446MB for 3688532-byte allocation
,W/jxcore-log( 3879): Initializing JXcore engine
,W/jxcore-log( 3879): JXcore engine is ready
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(43ce3788): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(43c74e08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3879): Starting JXcore engine
,W/jxcore-log( 3879): Platform android
W/jxcore-log( 3879): 
,W/jxcore-log( 3879): Process ARCH arm
W/jxcore-log( 3879): 
,I/jxcore-log( 3879): JXcore Cordova bridge is ready!
I/jxcore-log( 3879): 
,W/jxcore-log( 3879): JXcore engine is started
,I/chromium( 3879): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3879): Toggling radios to true
I/jxcore-log( 3879): 
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): checking for enable restriction...
,D/BluetoothManagerService(  905): checkBTEasState, ret=true
,I/BluetoothManagerService(  905): isBluetoothRestricted(): false
D/BluetoothManagerService(  905): enable(): region ID = 6
,D/BluetoothManagerService(  905): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 1
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1262
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  905): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3879): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  905): New client listening to asynchronous messages
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on,
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 2
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1333
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
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 2(ms)
D/WifiService(  905): setWifiEnabled: true pid=3879, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  905): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3926 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3879): disconnect: Base Package Name=com.test.thalitest, uid=10348
,D/WifiManager( 3879): reconnect: Base Package Name=com.test.thalitest, uid=10348
,D/PMS     (  905): acquireWL(42592360): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
I/jxcore-log( 3879): Radios toggled
I/jxcore-log( 3879): 
,D/PMS     (  905): releaseWL(433975f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/AdapterServiceConfig( 3926): Adding HeadsetService
D/AdapterServiceConfig( 3926): Adding A2dpService
D/AdapterServiceConfig( 3926): Adding HidService
D/AdapterServiceConfig( 3926): Adding HealthService
D/AdapterServiceConfig( 3926): Adding PanService
,D/AdapterServiceConfig( 3926): Adding GattService
,W/linker  ( 3926): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3926): REFCOUNT: CREATED. INSTANCE_COUNT1
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422d4f80:true
,D/BluetoothAdapterState( 3926): make
,I/BluetoothAdapterState( 3926): Entering OffState
,I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3926): Address is:80:01:84:8A:B3:68
,I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  905): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapter( 1108): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41eb47c0
,D/BluetoothAdapter( 1108): onBluetoothServiceUp done
,D/BluetoothAdapter( 1213): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bf17c8
,D/BluetoothAdapter( 1213): onBluetoothServiceUp done
,D/BluetoothAdapter( 1751): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@420a5b28
,D/BluetoothAdapter( 1751): onBluetoothServiceUp done
D/BluetoothAdapter( 3926): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41aabfc0
,D/BluetoothAdapter( 3926): onBluetoothServiceUp done
D/BluetoothAdapter( 1395): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41d0fab0
,D/BluetoothAdapter( 1395): onBluetoothServiceUp done
D/BluetoothAdapter( 3879): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@425ec918
D/BluetoothAdapter( 3879): onBluetoothServiceUp done
D/BluetoothAdapter(  905): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@422b2f00
,D/BluetoothAdapter(  905): onBluetoothServiceUp done
D/BluetoothAdapter( 1223): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bcc2a8
D/BluetoothAdapter( 1223): onBluetoothServiceUp done
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3926): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3926): Setting state to 11
I/BluetoothAdapterState( 3926): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3926): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  905): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothBondStateMachine( 3926): make
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/BluetoothBondStateMachine( 3926): StableState(): Entering Off State
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3951 uid=10037 gids={50037, 3002, 3001}
,D/HeadsetService( 3926): Received start request. Starting profile...
D/HeadsetStateMachine( 3926): Version 1.6
,D/HeadsetStateMachine( 3926): make
,I/BluetoothAdapterState( 3926): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3926): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3926): Received start request. Starting profile...
V/Avrcp   ( 3926): make
,D/Avrcp   ( 3926): fillIntentFilter()
,I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3926): make
,D/HtcBtWidget_BTWidgetProvider( 3951): onBTStateChanged() for widget: 
,D/A2dpStateMachine( 3926): Enter Disconnected: -2
,D/HtcBtWidget_BTWidgetProvider( 3951): updateWidget(context) for widget: 
,D/HidService( 3926): Received start request. Starting profile...
,D/HealthService( 3926): Received start request. Starting profile...
D/Process (  905): killProcessQuiet, pid=1477
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PanService( 3926): Received start request. Starting profile...
,I/ActivityManager(  905): Killing 1477:com.htc.bgp/u0a14 (adj 15): empty #17
D/BluetoothTethering(  905): supplyMessenger
D/BluetoothTethering(  905): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  905): got MESSAGE_CONNECT_PANSERVICE, call connect
D/PanService( 3926): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothTethering(  905): got CMD_CHANNEL_HALF_CONNECTED
,D/BtGatt.DebugUtils( 3926): handleDebugAction() action=null
D/BtGatt.GattService( 3926): Received start request. Starting profile...
,D/BtGatt.GattService( 3926): start()
,V/BluetoothPbapService( 3926): Pbap Service onCreate
,V/BluetoothPbapService( 3926): Starting PBAP service
I/ActivityManager(  905): Recipient 1477
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 11
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 11
E/BluetoothMasService( 3926): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3926): Add permission for SmsProvider.
V/BluetoothMasService( 3926): Starting MAS instances
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 11
I/MailMessageReceiver( 3926): reg:com.android.bluetooth.btservice.AdapterApp@41a9f528 with com.htc.util.mail.MailMessageReceiver@41adf368
I/MailManager( 3926): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41adf368
V/EmailUtils( 3926): Manager Instance is not NULL
,I/ActivityManager(  905): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3970 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  905): interfaceAdded wlan0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): wlan0 is not a tetherable iface, ignoring
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Tethering(  905): interfaceAdded p2p0
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/PMS     (  905): releaseWL(42592360): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/EmailUtils( 3926): ============NULL aList========
,V/EmailUtils( 3926): <-getEmailAccountIdList
,V/BluetoothMasService( 3926): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 11
,V/BluetoothMasService( 3926): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3926): Manager Instance is not NULL
,D/EmailUtils( 3926): ============NULL aList========
,V/EmailUtils( 3926): <-getEmailAccountIdList
,V/BluetoothSapService( 3926): Sap Service onCreate
V/BluetoothSapService( 3926): initBinder
,V/BluetoothSapService( 3926): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41ae4758
,V/BluetoothSapReceiver( 3926): BluetoothSapReceiver init
,D/BluetoothSapService( 3926): setSapService()
V/BluetoothSapService( 3926): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3926): state: 12
,D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 11
,D/HeadsetPhoneState( 3926): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3926): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3926): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3926): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3926): Profile still not running:com.android.bluetooth.pan.PanService
,D/PanService( 3926): CMD_CHANNEL_FULL_CONNECTION
,D/BluetoothTethering(  905): got CMD_CHANNEL_FULLY_CONNECTED
,D/BluetoothAdapterService( 3926): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3926): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,D/Process (  905): killProcessQuiet, pid=3074
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  905): Killing 3074:com.android.defcontainer/u0a19 (adj 15): empty #17
D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 11
,I/ActivityManager(  905): Recipient 3074
,I/qcom-bluetooth( 3989): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3990 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 4007): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 4008): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 4010): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3990): Received state change = 11
,I/qcom-bluetooth( 4011): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4013): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4015): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WifiService(  905): New client listening to asynchronous messages
,I/wpa_supplicant( 4014): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4014): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4014): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4014): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4014): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4014): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4014): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4014): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4014): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4014): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4014): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4014): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4014): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4014): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4014): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4014): update_config=1
D/wpa_supplicant( 4014): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4014): device_name='Android_63cc'
D/wpa_supplicant( 4014): manufacturer='HTC'
D/wpa_supplicant( 4014): model_name='HTC_PHONE'
D/wpa_supplicant( 4014): model_number='1234'
D/wpa_supplicant( 4014): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4014): p2p_oper_reg_class=126
D/wpa_supplicant( 4014): p2p_oper_channel=36
D/wpa_supplicant( 4014): p2p_ssid_postfix='-Android_63cc'
,D/wpa_supplicant( 4014): persistent_reconnect=1
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4014): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4014): nl80211: RFKILL status not available
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4014): nl80211: Using driver-based roaming
D/wpa_supplicant( 4014): nl80211: TDLS supported
D/wpa_supplicant( 4014): nl80211: TDLS external setup
D/wpa_supplicant( 4014): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4014): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4014): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4014): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4014): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4014): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4014): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8989758
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8989758
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4014): htc_wext_command_init +
E/wpa_supplicant( 4014): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4014): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4014): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4014): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4014): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4014): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4014): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4014): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/Process (  905): killProcessQuiet, pid=3385
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3385:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/WifiMonitor(  905): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4019 uid=10048 gids={50048}
,I/ActivityManager(  905): Recipient 3385
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 3385): Died!
,D/HtcWiFiWidget_WiFiWidgetProvider( 4019): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4019): updateWidget(context) for widget: 
,I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/wpa_supplicant( 4014): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4014):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4014):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4014):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): nl80211: Flush PMKIDs
E/wpa_supplicant( 4014): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4014): State: DISCONNECTED -> INACTIVE
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4031 uid=10077 gids={50077}
,D/Process (  905): killProcessQuiet, pid=3368
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/PMS     (  905): acquireWL(420f5858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10077}
I/ActivityManager(  905): Killing 3368:com.htc.mediamanager/u0a32 (adj 15): empty #17
V/AlarmManager(  905): sending alarm PendingIntent{42172428: PendingIntentRecord{41f40448 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449748636978, Int=60000
D/PMS     (  905): releaseWL(420f5858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,I/qcom-bluetooth( 4043): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 80:01:84:8a:b3:68 
,I/qcom-bluetooth( 4044): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/SMSBackup( 4031): SMSBackupAgentService started
,D/SMSBackup( 4031): Checking restore status
D/SMSBackup( 4031): Restore complete
,D/SMSBackup( 4031): cancelCheckAlarm
W/ProcessCpuTracker(  905): Skipping unknown process pid 3988
,W/ProcessCpuTracker(  905): Skipping unknown process pid 4044
D/SMSBackup( 4031): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  905): killProcessQuiet, pid=3741
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3741:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3741
,I/bt-btu  ( 3926): btu_task pending for preload complete event
D/wpa_supplicant( 4014): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4014): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4014): WPS: Set UUID for interface p2p0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3368
,D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4014): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): Using existing control interface directory.
D/wpa_supplicant( 4014): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4014): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4014): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4014): P2P: Own listen channel: 6
D/wpa_supplicant( 4014): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4014): P2P: Add operating class 81
I/wpa_supplicant( 4014): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4014): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4014): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4014): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4014): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4014): disable_scan_offload=1
D/wpa_supplicant( 4014): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4014): update_config=1
D/wpa_supplicant( 4014): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4014): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4014): manufacturer='HTC'
D/wpa_supplicant( 4014): model_name='HTC Desire 820'
D/wpa_supplicant( 4014): model_number='HTC Desire 820'
D/wpa_supplicant( 4014): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4014): persistent_reconnect=1
D/wpa_supplicant( 4014): p2p_disabled=1
D/wpa_supplicant( 4014): hs20=1
D/wpa_supplicant( 4014): interworking=1
D/wpa_supplicant( 4014): Line: 18 - start of a new network block
D/wpa_supplicant( 4014): key_mgmt: 0x2
D/wpa_supplicant( 4014): priority=1 (0x1)
,D/wpa_supplicant( 4014): signinfail=0 (0x0),
,D/wpa_supplicant( 4014): Priority group 1
D/wpa_supplicant( 4014):    id=0 ssid='NG700'
I/wpa_supplicant( 4014): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4014): nl80211: RFKILL status not available
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4014): nl80211: Using driver-based roaming
D/wpa_supplicant( 4014): nl80211: TDLS supported
D/wpa_supplicant( 4014): nl80211: TDLS external setup
D/wpa_supplicant( 4014): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4014): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4014): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4014): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4014): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4014): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4014): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8999718
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4014): htc_wext_command_init +
I/wpa_supplicant( 4014): htc_wext_command_init -
I/wpa_supplicant( 4014): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4014): Don't set 00 to countryID.conf
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10,
D/wpa_supplicant( 4014): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4014): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4014): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4014): nl80211: 2457-2482 @ 40 MHz,
D/wpa_supplicant( 4014): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4014): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4014): nl80211: Added 802.11b mode based on 802.11g information,
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4014): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4014):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4014):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 4014):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4014): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4014): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4014): TDLS: Driver uses external link setup
D/wpa_supplicant( 4014): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4014): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4014): Using existing control interface directory.
,I/wpa_supplicant( 4014): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4014): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4014): Auto country group 1: ch36
I/wpa_supplicant( 4014): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4014): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 4014): Get randomness: len=20 entropy=0
V/RegulatoryObserver(  905): uevent:
V/RegulatoryObserver(  905): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  905): Regulatory Country Code:DE
D/wpa_supplicant( 4014): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4014): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_905-2
D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4014): nl80211: Event message available
D/wpa_supplicant( 4014): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4014): nl80211: Regulatory domain change
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4014): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4014): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4014): P2P: Add operating class 81
D/wpa_supplicant( 4014): P2P: Add operating class 115
D/wpa_supplicant( 4014): P2P: Add operating class 116
D/wpa_supplicant( 4014): P2P: Add operating class 117
D/wpa_supplicant( 4014): P2P: Update channel list
D/wpa_supplicant( 4014): p2p0: Updating hw mode
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4014): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4014): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4014): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 31
,D/wpa_supplicant( 4014): nl80211: Added 802.11b mode based on 802.11g information
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): set wifi ON
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: DRIVER MACADDR
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiConfigStore(  905): Loading config and enabling all networks
D/WifiNative-wlan0(  905): doString: LIST_NETWORKS
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): list_network_info: ret=0x1, pos=0xb899c117 buf=0xb899c0e8
I/wpa_supplicant( 4014): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4014): 0	NG700	any	
,D/WifiNative-wlan0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  905): 0	NG700	any	
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 bssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 priority
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
,D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
V/RegulatoryObserver(  905): Start wifi-crda service to run crda.
V/RegulatoryObserver(  905): Country Code is DE
V/RegulatoryObserver(  905): Send broadcast country code message.
I/RegulatoryObserver(  905): Broadcast intent for crda country code: DE
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4014): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 proto
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  905): Failed to look-up a string: W
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NET,WORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/HtcWiFiWidget_WiFiWidgetProvider( 4019): onWiFiStateChanged() for widget: 
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 group
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  905): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_cert
D/HtcWiFiWidget_WiFiWidgetProvider( 4019): updateWidget(context) for widget: 
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  905): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 limited
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 eap
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 phase2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 password
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 key_id
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  905): doString: GET_NETWORK 0 private_key
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4014): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  905): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  905): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4014): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4014): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET manufacturer HTC
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4014): manufacturer='HTC'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4014): model_name='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4014): model_number='HTC Desire 820'
D/WifiNative-wlan0(  905):    returned true
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4014): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DISABLE_OFFLOAD
I/wpa_supplicant( 4014): wpa_supplicant_scan enter
I/wpa_supplicant( 4014): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4014): ap_scan=1 , scan_req =1
I/wpa_supplicant( 4014): wpa_supplicant_trigger_scan +
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4014): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 4014): WiFioffload: DISABLE OFFLOAD to 3G
D/wpa_supplicant( 4014): nl80211: Event message available
D/wpa_supplicant( 4014): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE UNINITIALIZED
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SET auto_interworking 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4014): auto_interworking=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: RECONNECT
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): SET_SCREEN_ON:On
I/wpa_supplicant( 4014): htc_wext_set_keepalive +
I/wpa_supplicant( 4014): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4014): getPrivFuncNum +	
I/wpa_supplicant( 4014): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wl,an0(  905): doBoolean: SET ps 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4014): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  905): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  905): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): SETBAND: 0
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4014): P2P: Add operating class 81
D/wpa_supplicant( 4014): P2P: Add operating class 115
D/wpa_supplicant( 4014): P2P: Add operating class 116
D/wpa_supplicant( 4014): P2P: Add operating class 117
D/wpa_supplicant( 4014): P2P: Update channel list
I/wpa_supplicant( 4014): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
D/libc    (  905): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
I/wpa_supplicant( 4014): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4014): Get_p2p_auto_channel: Auto country group 1: ch36
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 4014): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4014): p2p_oper_reg_class=126
D/wpa_supplicant( 4014): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4014): P2P: New SSID postfix: -Android_63cc
E/wpa_supplicant( 4014): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4014): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4014): p2p_oper_channel=36
E/wpa_supplicant( 4014): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4014): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4014): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4014): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4014): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: BSS_FLUSH 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/WifiMonitor(  905): startMonitoring(p2p0) with mConnected = true
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: SCAN
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/WifiNative-p2p0(  905): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  905):    returned false
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4014): persistent_reconnect=1
I/wpa_supplicant( 4014): Recv Cmd 2: SET persistent_reconnect=1
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  905): doBoolean: SET pno 0
D/WifiNative-p2p0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/WifiNative-p2p0(  905): doBoolean: SET device_name Android_63cc
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4014): wpa_supplicant_scan enter
D/WifiNative-wlan0(  905):    returned true
D/WifiP2pService(  905): P2pEnablingState
D/WifiP2pService(  905): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2p socket connection successful
D/WifiP2pService(  905): P2pEnabledState
D/WifiP2pService(  905): sending p2p connection changed broadcast
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiStateMachine(  905): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiDisplayController(  905): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  905): mWfdEnabled :false, networkInfo.isConnected() :false
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_name Android_63cc"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'device_name'='Android_63cc'
D/wpa_supplicant( 4014): device_name='Android_63cc'
I/wpa_supplicant( 4014): Recv Cmd 2: SET device_name=Android_63cc
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET p2p_ssid_postfix -Android_63cc
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_63cc"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_63cc'
D/wpa_supplicant( 4014): p2p_ssid_postfix='-Android_63cc'
D/wpa_supplicant( 4014): P2P: New SSID postfix: -Android_63cc
I/wpa_supplicant( 4014): Recv Cmd 2: SET p2p_ssid_postfix=-Android_63cc
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4014): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4014): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4014): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4014): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4014): Single channel concurrency preference: sta
I/wpa_supplicant( 4014): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: STATUS
W/WifiHW  (  905): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  905): doBoolean: P2P_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4014): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4014): P2P: Stopping find
D/wpa_supplicant( 4014): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4014): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4014): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  905): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4014): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4014): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doString: LIST_NETWORKS
W/WifiHW  (  905): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4014): list_network_info: ret=0x22, pos=0xb899c10a buf=0xb899c0e8
I/wpa_supplicant( 4014): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4014): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  905):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  905): doBoolean: AP_SCAN 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "AP_SCAN 1"
,D/WifiNative-p2p0(  905):    returned false
D/WifiP2pService(  905): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  905):  deviceAddress: 82:01:84:6b:e8:5d
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
D/WifiP2pService(  905): InactiveState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0(  905): doBoolean: SET wifi_display 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4014): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4014): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4014): WFD: Update WFD IE
I/wpa_supplicant( 4014): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4014): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  905):    returned true
D/WifiNative-p2p0(  905): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  905): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4014): WFD: Set subelement 0
D/wpa_supplicant( 4014): WFD: Update WFD IE
I/wpa_supplicant( 4014): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4014): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  905):    returned true
I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  905): convertEffect before=902
D/HtcEffectManager(  905): convertEffect after=902
D/WifiP2pService(  905): P2pEnabledState{ when=-14ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  905):  WFD CtrlPort: 7236
D/WifiP2pService(  905):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  905): Successfully set WFD info.
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_63cc
D/WifiDisplayController(  905):  deviceAddress: 82:01:84:6b:e8:5d
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
,D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4014): nl80211: Event message available
D/wpa_supplicant( 4014): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4014): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4014): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 4014): nl80211: Survey data missing
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4014): Sorted scan results
I/wpa_supplicant( 4014): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 4014): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 4014): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 4014): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
I/wpa_supplicant( 4014): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
D/wpa_supplicant( 4014): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 4014): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4014): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4014): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4014): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4014): Add randomness: count=6 entropy=4
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 4014): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4014): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4014): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4014): wpa_supplicant_pick_network+
I/wpa_supplicant( 4014): Selecting BSS from priority group 1
I/wpa_supplicant( 4014): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4014): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4014): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4014): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4014): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4014):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4014):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 4014): Start print parameters
I/wpa_supplicant( 4014): wpa_s->wpa_state is 3
I/wpa_supplicant( 4014): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4014): isConcurrentMode() is 0
I/wpa_supplicant( 4014): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4014): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4014): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4014): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4014): wpa_s->reassociate is 0
I/wpa_supplicant( 4014): wpa_s->is_screen_on 1
I/wpa_supplicant( 4014): wpa_s->ifname wlan0
I/wpa_supplicant( 4014): End print parameters
I/wpa_supplicant( 4014): selected network = 2
D/wpa_supplicant( 4014): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb899a4e8  current_ssid=0x0
D/wpa_supplicant( 4014): w,lan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4014): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4014): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4014): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4014): check if in concurrent case
,I/wpa_supplicant( 4014): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4014): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4014): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4014): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4014): RSN: PMKSA cache search - network_ctx=0xb899a4e8 try_opportunistic=0
D/wpa_supplicant( 4014): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4014): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4014): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4014): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4014): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4014): nl80211: Unsubscribe mgmt frames handle 0xb8999718 (mode change)
D/wpa_supplicant( 4014): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8999718
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 4014): nl80211: Register frame type=0xd0 nl_handle=0xb8999718
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4014): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4014):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4014):   * freq=2412
D/wpa_supplicant( 4014):   * Auth Type 0
D/wpa_supplicant( 4014):   * WPA Versions 0x2
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 4014): nl80211: Connect request send successfully
D/wpa_supplicant( 4014): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): RSN: Ignored PMKID candidate without preauth flag
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  905): doString: LIST_DONGLES
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  905): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4014): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 4014): reply (636) for get BSS: id=0
I/wpa_supplicant( 4014): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4014): freq=5220
I/wpa_supplicant( 4014): level=-46
I/wpa_supplicant( 4014): tsf=0000000104951023
I/wpa_supplicant( 4014): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4014): ssid=NG7005g
I/wpa_supplicant( 4014): ====
I/wpa_supplicant( 4014): id=1
I/wpa_supplicant( 4014): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4014): freq=2412
I/wpa_supplicant( 4014): level=-47
I/wpa_supplicant( 4014): tsf=0000000104951033
I/wpa_supplicant( 4014): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4014): ssid=01ABC
I/wpa_supplicant( 4014): ====
I/wpa_supplicant( 4014): id=2
I/wpa_supplicant( 4014): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4014): freq=2412
I/wpa_supplicant( 4014): level=-47
I/wpa_supplicant( 4014): tsf=0000000104951036
I/wpa_supplicant( 4014): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4014): ssid=NG700
I/wpa_supplicant( 4014): ====
I/wpa_supplicant( 4014): id=3
I/wpa_supplicant( 4014): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4014): freq=2427
I/wpa_supplicant( 4014): level=-76
I/wpa_supplicant( 4014): tsf=0000000104951041
I/wpa_supplicant( 4014): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4014): ssid=Gonzos
I/wpa_supplicant( 4014): ====
I/wpa_supplicant( 4014): id=4
I/wpa_supplicant( 4014): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 4014): freq=2437
I/wpa_supplicant( 4014): level=-89
I/wpa_supplicant( 4014): tsf=0000000104951044
I/wpa_supplicant( 4014): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 4014): ssid=UPC4688432
I/wpa_supplicant( 4014): ####
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/WifiStateMachine(  905): == begin of scan result ==
,D/WifiStateMachine(  905): == (5) end of scan result ==
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/WifiStateMachine(  905): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 104951023, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 104951033, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiStateMachine(  905): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 104951036, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 104951041, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 104951044, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  905): add 5 to mScanResults
D/WifiNotificationController(  905): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4014): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4014): nl80211: Event message available
D/wpa_supplicant( 4014): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4014): nl80211: Connect event
D/wpa_supplicant( 4014): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4014): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4014): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4014): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4014): Add randomness: count=7 entropy=5
I/wpa_supplicant( 4014): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4014): TDLS: Remove peers on association
D/wpa_supplicant( 4014): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4014): htc_wext_set_keepalive +
I/wpa_supplicant( 4014): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4014): getPrivFuncNum +	
I/wpa_supplicant( 4014): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 4014): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  905): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  905): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  905): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,D/HTCRequest(  905): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  905): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  905): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  905): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  905): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,D/WifiStateMachine(  905): Enter handleAssociatedWithEvent
D/WifiStateMachine(  905): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  905): Associated
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  905): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  905): Exit handleAssociatedWithEvent
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/bt-btu  ( 3926): btu_task received preload complete event
,D/bt-btm  ( 3926): btm_acl_device_down
D/bt-btm  ( 3926): btm_acl_reset_paging
,D/bt-btm  ( 3926): btm_acl_set_discing
,I/wpa_supplicant( 4014): State: ASSOCIATED -> 4WAY_HANDSHAKE,
D/wpa_supplicant( 4014): Get randomness: len=32 entropy=6
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  905): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
D/wpa_supplicant( 4014): EAPOL: disable timer tick
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,I/bt-btm  ( 3926): btm_reset_complete
,I/bt-btm  ( 3926): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3926): Start reading local supported commands
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/bt-btm  ( 3926): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3926): BTM reads next extended features page (1)
,D/bt-btm  ( 3926): BTM reads next extended features page (2)
,I/wpa_supplicant( 4014): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb89999f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4014):    addr=c0:ff:d4:d3:aa:48
D/bt-btm  ( 3926): BTM reached last extended features page (2)
,D/bt-btm  ( 3926): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4014): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f43b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 4014):    broadcast key
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/bt-btm  ( 3926): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
D/bt-btm  ( 3926): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4014): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4014): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4014): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4014): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4014): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4014): set send_ind_to_ndc = 0
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4014): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4014): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4014): EAPOL authentication completed successfully
I/wpa_supplicant( 4014): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4014): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4014): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4014): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  905): interfaceLinkStateChanged wlan0, true
D/Tethering(  905): interfaceStatusChanged wlan0, true
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/bt-btm  ( 3926): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 3926): btm_read_ble_wl_size 
D/bt-btm  ( 3926): btm_read_white_list_size_complete ,
D/bt-btm  ( 3926): btm_get_ble_buffer_size 
D/bt-btm  ( 3926): btm_read_ble_buf_size_complete 
D/bt-btm  ( 3926): btm_read_ble_local_supported_features 
D/bt-btm  ( 3926): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3926): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3926): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3926): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3926): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3926): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3926): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3926): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3926): BTM_SetInquiryMode
I/bt-btm  ( 3926): BTM_SetPageScanType
I/bt-btm  ( 3926): BTM_SetInquiryScanType
D/bt-btm  ( 3926): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3926): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3926): BTM_BleLoadLocalKeys
D/bt-btm  ( 3926): BTM_BleLoadLocalKeys
I/bt-btm  ( 3926): BTM_Sec: application registered
E/bt-btm  ( 3926): BTM_SecRegister:p_cb_info->p_le_callback == 0x61f4e941 
I/bt-btm  ( 3926): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3926): SMP_Register state=0
E/bt-btm  ( 3926): BTM_SecRegister: btm_cb.api.p_le_callback = 0x61f4e941 
I/bt-btm  ( 3926): BTM_Sec: application registered
D/bt-btm  ( 3926): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3926): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3926): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3926): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3926): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3926): BTM_RegBusyLevelNotif
I/bt-att  ( 3926): GATT_Register
D/bt-att  ( 3926): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3926): allocated gatt_if=3
I/bt-att  ( 3926): GATT_StartIf gatt_if=3
D/bt-att  ( 3926): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3926): gatt_find_the_connected_bda found=0 found_idx=7
,D/WifiStateMachine(  905): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  905): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  905): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  905): This record is existed, only update it...
,D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
E/bt-btif ( 3926): Calling BTA_HhEnable
I/bt-btm  ( 3926): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3926): BTM_AllocateSCN
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3926): BTM_AllocateSCN
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3926):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3926):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:5,
I/bt-avp  ( 3926): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3926): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
,D/bt-avp  ( 3926): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3926): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
,I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 3926): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3926):                : sec: 0x80, service name [] (up to 21 chars saved)
E/bt-btif ( 3926): btif_storage_get_adapter_property service_mask:0x140040
D/bt-btm  ( 3926): HAL bt_hal_cbacks->a
,I/bt-btif ( 3926): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3926): BTM_SecAddDevice()  BDA: b4:ce:f6:ab:a4:6a
D/bt-btm  ( 3926): BTM_SecAddDevice : rmt_io_caps is 0 
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:2 len:6
D/bt-btm  ( 3926): BTM_GetHCIConnHandle
,I/bt-btm  ( 3926): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3926): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3926): BTM_GetHCIConnHandle
I/bt-btm  ( 3926): BTM_SecAddDevice()  BDA: 34:fc:ef:9d:93:0b
D/bt-btm  ( 3926): BTM_SecAddDevice : rmt_io_caps is 0 
,D/bt-btm  ( 3926): BTM_GetHCIConnHandle
I/bt-btm  ( 3926): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3926): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3926): BTM_GetHCIConnHandle
I/bt-btm  ( 3926): BTM_SecAddDevice()  BDA: 58:2a:f7:ed:96:be
D/bt-btm  ( 3926): BTM_SecAddDevice : rmt_io_caps is 0 
,I/bt-att  ( 3926): GATT_Register
D/bt-att  ( 3926): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3926): allocated gatt_if=4
I/bt-att  ( 3926): GATT_StartIf gatt_if=4
D/bt-att  ( 3926): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3926): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3926): Address is:80:01:84:8A:B3:68
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:1 len:14
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:7 len:4
D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
,D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/BluetoothAdapterProperties( 3926): Scan Mode:20
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3926): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:8 len:30
,D/BluetoothAdapter( 3926): getBluetoothService(): entry
D/BluetoothAdapter( 3926): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3926): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41aefa50
D/BluetoothDevice( 3926): getService : Register callback
D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BluetoothAdapterProperties( 3926): Adding bonded device:B4:CE:F6:AB:A4:6A
D/BluetoothAdapterProperties( 3926): Adding bonded device:08:EC:A9:50:76:27
D/WifiStateMachine(  905): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  905): updateConnectedAP...
,D/BluetoothAdapterProperties( 3926): Adding bonded device:34:FC:EF:9D:93:0B
,D/WifiService(  905): New client listening to asynchronous messages
D/BluetoothAdapterProperties( 3926): Adding bonded device:7C:F9:0E:34:8A:A0
D/BluetoothAdapterProperties( 3926): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:3 len:48
I/bt-btif ( 3926): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3926): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/BluetoothRemoteDevices( 3926): Remote class is:5898764
I/bt-btif ( 3926): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 3926): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
D/BluetoothRemoteDevices( 3926): Remote class is:5898764
D/DhcpStateMachine(  905): [StoppedState] Start DHCP
D/WifiStateMachine(  905): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/bt-btif ( 3926): HAL bt_hal_cbacks->remote_device_properties_cb
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,E/BluetoothRemoteDevices( 3926): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BluetoothRemoteDevices( 3926): Remote class is:5898764
D/WifiStateMachine(  905): WiFioffload: set mMobileNetworkType= Unknown
,D/WifiNative-wlan0(  905): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4014): WiFioffload: update mobile network = Unknown
D/WifiNative-wlan0(  905):    returned true
,I/bt-btif ( 3926): HAL bt_hal_cbacks->remote_device_properties_cb
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  905): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  905): acquireWL(4256e540): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): Power_Mode_Type mode = 1
I/wpa_supplicant( 4014): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,E/BluetoothRemoteDevices( 3926): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
D/BluetoothRemoteDevices( 3926): Remote class is:5898764
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
,I/bt-btif ( 3926): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3926): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothRemoteDevices( 3926): Remote class is:5898764
,I/bt-btif ( 3926): BTA_JvEnable
D/WifiStateMachine(  905): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43f1b150 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43f1b150 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btm  ( 3926): BTM_ReadConnectability
I/bt-btm  ( 3926): BTM_ReadDiscoverability
I/bt-btm  ( 3926): BTM_SetDiscoverability
I/bt-btm  ( 3926): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3926): br_edr_supported=0x2
I/bt-btm  ( 3926): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3926): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3926): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_SetConnectability
I/bt-btm  ( 3926): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3926): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_SetDiscoverability
I/bt-btm  ( 3926): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3926): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3926): br_edr_supported=0x0
I/bt-btm  ( 3926): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3926): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3926): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3926): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3926): BTM_SetConnectability
I/bt-btm  ( 3926): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3926): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3926): bta_pan_co_init
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3926): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3926):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3926):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3926): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3926):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3926): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3926):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
E/bt_mct  ( 3926): hci lib postload completed
,D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3926): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3926): ScanMode =  20
D/BluetoothAdapterProperties( 3926): State =  11
D/BluetoothAdapterProperties( 3926): Setting state to 12
I/BluetoothAdapterState( 3926): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3926): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btm  ( 3926): BTM_SetDiscoverability
I/bt-btm  ( 3926): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 3926): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3926): br_edr_supported=0x0
I/bt-btm  ( 3926): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3926): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3926): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3926): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_SetConnectability
I/bt-btm  ( 3926): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3926): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3926): HAL bt_hal_cbacksv_flag old=0x4,
I/bt-btif ( 3926): always disable adv in non-discoverable n
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3926): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,I/BluetoothAdapterState( 3926): Entering On State
D/BluetoothAdapterProperties( 3926): Scan Mode:21
I/bt-btif ( 3926): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3926): Discoverable Timeout:120
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1101698128)( 3926): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3926): getBondedDevices: length=5
,D/BluetoothHeadset( 1213): Proxy object connected
,D/BluetoothPan(  905): onBluetoothStateChange(on) call bindService
,I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothHeadset( 1108): onBluetoothStateChange: up=true
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothPan(  905): BluetoothPAN Proxy object connected
D/BluetoothAdapterService(1101698128)( 3926): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3926): getBondedDevices: length=5
D/BluetoothHeadset( 1108): Proxy object connected
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
I/QuickSettingMiniLite( 1108): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41da2658
D/BluetoothHeadset(  905): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1213): Proxy object connected
D/BluetoothPhoneService( 1213): BluetoothHeadset onServiceConnected
,D/BluetoothA2dp(  905): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  905): Proxy object connected
,D/BluetoothAdapter( 1213): 1103008912: getState(). Returning 12
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 11 -> 12
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3926): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3926): ***********state = 12
,D/BluetoothAdapter(  905): 1111177568: getState(). Returning 12
,D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 12
,D/BluetoothA2dp(  905): Proxy object connected
,V/BluetoothSapReceiver( 3926): SapReceiver onReceive 
D/PMS     (  905): acquireWL(4263ec00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
V/BluetoothSapReceiver( 3926): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3926):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3926): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter(  905): 1111177568: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3951): onBTStateChanged() for widget: 
D/BluetoothManagerService(  905): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 12
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/HtcBtWidget_BTWidgetProvider( 3951): updateWidget(context) for widget: 
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 12
V/BluetoothMasService( 3926): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3926): Manager Instance is not NULL
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  905): releaseWL(4263ec00): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  905): acquireWL(425aadd8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42cd4698:true
I/LocationAgent( 3316): new LocationAgent instance!!
D/HtcTagManager( 3316): HtcTagManager construction complete
D/EmailUtils( 3926): ============NULL aList========
V/EmailUtils( 3926): <-getEmailAccountIdList
V/BluetoothSapService( 3926): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3926): state: 12
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 12
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
W/ContextImpl( 3926): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3926): Starting SAP server process
D/BluetoothInputDevice( 3316): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
V/BluetoothPbapService( 3926): Handler(): got msg=1
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
D/BluetoothInputDevice( 3316): BluetoothInputDevice(): Binding service...
,V/BluetoothPbapService( 3926): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3926): Pbap Service initSocket
V/BluetoothMasService( 3926): handleMessage: mIsEmailEnabledtrue
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothPan( 3316): BluetoothPan()
D/BluetoothAdapter( 3926): getBluetoothService(): entry
W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
,V/BtMns   ( 3926): BluetoothMns: isEmailEnabled: true
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 8
E/BluetoothServiceJni( 3926): SOCK FLAG = 1 ***********************
,I/bt-btif ( 3926): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
,I/bt-btm  ( 3926):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3926): Succeed to create listening socket 
V/BluetoothPbapService( 3926): Accepting socket connection...
,D/BluetoothMasService( 3926): Map_prev 1
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
D/BluetoothPan( 3316): BluetoothPan(): Binding service...
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3926): getBluetoothService(): entry
,W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3926): SOCK FLAG = 3 ***********************
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
I/bt-btif ( 3926): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3926):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothMap( 3316): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothMap( 3316): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothAdapter( 3926): getBluetoothService(): entry
W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  905): Registered receivers: 9
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothSap( 3316): BluetoothSap() call bindService
E/BluetoothServiceJni( 3926): SOCK FLAG = 3 ***********************
I/bt-btif ( 3926): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3926):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 10
,D/BluetoothPbap( 3316): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 11
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
,D/BluetoothPbap( 3316): BluetoothPbap(): Binding service...
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothAdapter( 1108): 1104405464: getState(). Returning 12
D/BluetoothA2dp( 3316): BluetoothA2dp()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 12
D/BluetoothAdapter( 1108): 1104405464: getState(). Returning 12
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
,D/BluetoothA2dp( 3316): BluetoothA2dp(): Binding service...
,I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1108): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothHeadset( 3316): BluetoothHeadset()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothSapService( 3926): Sap_prev 1
V/BluetoothSapService( 3926): SAP Service startRfcommListenerThread
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
D/BluetoothHeadset( 3316): BluetoothHeadset(): Binding service...
V/BluetoothSapService( 3926): Sap Service initRfcommSocket
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HtcTagManager( 3316): startProxy
D/BluetoothAdapter( 3926): getBluetoothService(): entry
,W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
V/TAG     ( 3926): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3926): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ae5e98
,E/BluetoothServiceJni( 3926): SOCK FLAG = 3 ***********************
I/bt-btif ( 3926): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 3926):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
W/ContextImpl( 3316): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
V/BluetoothSapService( 3926): Succeed to create listening socket 
,V/BluetoothSapService( 3926): Accepting socket connection...
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3316): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3316): finishStartingService: stopping service
,D/BluetoothPan( 3316): BluetoothPAN Proxy object connected
D/PanProfile( 3316): Bluetooth service connected
D/BluetoothA2dp( 3316): Proxy object connected
D/A2dpProfile( 3316): Bluetooth service connected
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
V/BluetoothPbapService( 3926): Pbap Service onBind
D/BluetoothHeadset( 3316): Proxy object connected
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): onCreate: going to find gatt base service first.
D/HeadsetProfile( 3316): Bluetooth service connected
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
D/BluetoothInputDevice( 3316): Proxy object connected
D/HidProfile( 3316): Bluetooth service connected
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/BluetoothFtpService( 3926): Ftp Service onCreate
D/BluetoothAdapter( 1108): 1104405464: getState(). Returning 12
D/BluetoothAdapter( 3316): 1103289640: getState(). Returning 12
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 12
D/BluetoothAdapter( 3926): getBluetoothService(): entry
W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 12
D/SapServerProfile( 3316): Bluetooth service connected
I/QuickSettingMiniLite( 1108): updateLiteState:no connect device!
D/BluetoothFtpService( 3926): Ftp_prev 1
D/BluetoothPbap( 3316): Proxy object connected
,D/PbapServerProfile( 3316): Bluetooth service connected
,E/BluetoothServiceJni( 3926): SOCK FLAG = 0 ***********************
I/bt-btif ( 3926): BTA_JvCreateRecordByUser
W/System.err(  905): java.lang.Throwable: stack dump
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3926):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
I/BtOppRfcommListener( 3926): Accept thread started.
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3926): getBluetoothService(): entry
,W/BluetoothAdapter( 3926): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3926): SOCK FLAG = 1 ***********************
I/bt-btif ( 3926): BTA_JvCreateRecordByUser
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43eb98a0:true
D/bt-sdp  ( 3926): SDP_CreateRecord ok, num_records:16
,I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btif ( 3926): BTA_JvRfcommStartServer
I/bt-btm  ( 3926): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 3926):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3926): Run Accept thread
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 12
,D/PMS     (  905): releaseWL(425aadd8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothMasService( 3926): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3926): Manager Instance is not NULL
D/[HTC_BLE][Constants]( 3990):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3990):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3990):  + discoverServicesOnBonded = false
D/EmailUtils( 3926): ============NULL aList========
V/EmailUtils( 3926): <-getEmailAccountIdList
D/BluetoothMasService( 3926): Map_prev 1
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf3a8
D/[HTC_BLE][Constants]( 3990): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3990): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3990): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3990): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3990): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
D/[HTC_BLE][Constants]( 3990): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3990): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3990): Received state change = 12
D/HtcTagManager( 3316): onServiceConnected
D/HtcTagProfile( 3316): setup proxy
D/HtcPxpProfile( 3316): setup proxy
D/HtcFmpProfile( 3316): setup proxy
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf3a8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3990): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf3a8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3990): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf3a8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abad60
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3990): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41aaf3a8
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425a8050:true
I/LocationAgent( 3840): new LocationAgent instance!!
D/HtcTagManager( 3840): HtcTagManager construction complete
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothInputDevice( 3840): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 14
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/BluetoothInputDevice( 3840): BluetoothInputDevice(): Binding service...
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3840): BluetoothPan()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 15
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/BluetoothPan( 3840): BluetoothPan(): Binding service...
,D/BluetoothMap( 3840): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 16
,E/BluetoothMap( 3840): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,D/RingtoneManager( 3990): getExternalStorageState=mounted
,D/wpa_supplicant( 4014): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4014): EAPOL: disable timer tick
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 17
,D/BluetoothSap( 3840): BluetoothSap() call bindService
,D/BluetoothPbap( 3840): BluetoothPbap()
,D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/BluetoothPbap( 3840): BluetoothPbap(): Binding service...
,D/BluetoothManagerService(  905): Registered receivers: 18
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothA2dp( 3840): BluetoothA2dp()
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3990):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 19
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothA2dp( 3840): BluetoothA2dp(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3990): BleProfilesStateMachine is initialized...
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): initScanModeInterface: true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3990): Enter IdleState
,D/BluetoothHeadset( 3840): BluetoothHeadset()
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ca8260:true
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 20
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothHeadset( 3840): BluetoothHeadset(): Binding service...
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE][Constants]( 3990):  + defaultServices = 0
,D/[HTC_BLE][Constants]( 3990):  + enableOnBonded = false
,D/HtcTagManager( 3840): startProxy
,D/[HTC_BLE][Constants]( 3990):  + discoverServicesOnBonded = false
,W/ContextImpl( 3840): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3840): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3840): setBluetoothStateOn
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/HtcTagManager( 3840): startProxy
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothAdapterService(1101698128)( 3926): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3926): getBondedDevices: length=5
D/BluetoothAdapter( 3840): getBluetoothService(): entry
D/BluetoothAdapter( 3840): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3840): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41aeab28
D/BluetoothDevice( 3840): getService : Register callback
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abad60
E/BluetoothDevice( 3840): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/HtcTagManager( 3840): addHtcTagProfiles
,E/BluetoothDevice( 3840): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/HtcTagManager( 3840): addHtcTagProfiles
,E/BluetoothDevice( 3840): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/HtcTagManager( 3840): addHtcTagProfiles
,E/BluetoothDevice( 3840): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/HtcTagManager( 3840): addHtcTagProfiles
,E/BluetoothDevice( 3840): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/HtcTagManager( 3840): addHtcTagProfiles
,D/BluetoothInputDevice( 3840): Proxy object connected
,D/HidProfile( 3840): Bluetooth service connected
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
D/BluetoothPan( 3840): BluetoothPAN Proxy object connected
,D/PanProfile( 3840): Bluetooth service connected
D/SapServerProfile( 3840): Bluetooth service connected
D/BluetoothPbap( 3840): Proxy object connected
D/PbapServerProfile( 3840): Bluetooth service connected
D/BluetoothA2dp( 3840): Proxy object connected
,D/A2dpProfile( 3840): Bluetooth service connected
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/BluetoothHeadset( 3840): Proxy object connected
,D/HeadsetProfile( 3840): Bluetooth service connected
,D/BluetoothAdapter( 3840): 1101730864: getState(). Returning 12
,D/HtcTagManager( 3840): onServiceConnected
,D/HtcTagProfile( 3840): setup proxy
D/HtcPxpProfile( 3840): setup proxy
,D/HtcFmpProfile( 3840): setup proxy
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4014): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(4256e540): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4014): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): gateway: /192.168.1.1
,D/WifiNative-wlan0(  905): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4014): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  905): VerifyingLinkState enter
D/WifiStateMachine(  905): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  905): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  905): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19722 delay=15s
,D/WifiWatchdogStateMachine(  905): WAN detection
V/NetworkPolicy(  905): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/ConnectivityService(  905): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  905): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  905): default: teardown()
D/MDST    (  905): default: setTeardownRequested(true)
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  905): default: setEnableApn apnType =default , enable=false
D/MDST    (  905): default: setTeardownRequested(true)
D/ConnectivityService(  905): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  905): Unexpected mtu value: android.net.wifi.WifiStateTracker@423b9528
,D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  905): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  905): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  905): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  905): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  905): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  905): acquireWL(42c846f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  905): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,I/QuickSettingWifi( 1108): receive.wifiConnect:true wifiAPname:NG700 elapse:2
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  905): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42c846f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4122 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1247/10075)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1769/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1395/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3771/10100)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
V/Tethering(  905): bSetPropertyMultiRAB:false
,D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3421/10051)
I/Tethering(  905): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/ConnectivityHelper( 1247): [onReceive] WIFI(1): CONNECTED
I/Tethering(  905): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  905): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/CaptivePortalTracker(  905): NoActiveNetworkState
I/Tethering(  905): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  905): Found interface wlan0
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1209 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4283dfe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.docs (3771/10100)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(422b65a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(425808e0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
I/ActivityManager(  905): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4139 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/PMS     (  905): releaseWL(425808e0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,D/PMS     (  905): acquireWL(41fc4300): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  905): releaseWL(422b65a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/MusicStore( 4122): Database version: 95
,W/ContextImpl( 4122): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(428e07e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ca08 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(428e07e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/ContextImpl( 4122): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4122): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(429a2870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/DelayedSyncController( 4139): Delaying sync.
D/PMS     (  905): releaseWL(429a2870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4251fe78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(41fc4300): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4122): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4122): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): acquireWL(42589470): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 905 1000 WorkSource{10096}
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  905): releaseWL(4251fe78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(424a3700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/DelayedSyncController( 4139): Delaying sync.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4122, uid=10154, userID:0
D/PMS     (  905): releaseWL(424a3700): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(420440d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42589470): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  905): releaseWL(420440d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4122): Registered
,I/MediaRouter( 4122): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2211/10021)
,I/NetworkMonitor( 4122): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4122/10154)
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 149
D/libc    (  365): [NET]res_nsend:resplen=104
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [1][0][0]
I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4168 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/libc    (  365): [NET]res_nsend:resplen=104
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/GpsLocationProvider(  905): NTP server returned: 1449748641497 (Thu Dec 10 12:57:21 CET 2015) reference: 107509 certainty: 12 system time offset: 959
,D/GpsLocationProvider(  905): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  905): releaseWL(4283dfe0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MediaRouter( 4122): getSelectedRoute
,I/NetworkMonitor( 4122): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4122/10154)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1108): receive(android.intent.action.TIME_SET,4,false)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
I/FeedActionBar( 1247): updateLastUpdatedTime(in String) LAST UPDATED 12:56
,D/DotMatrix( 1530): [EventService] EVENT_RESET_THEME_TIMESTAMP
D/Process (  905): killProcessQuiet, pid=1379
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DotMatrix( 1530): [EventService] isTheSameDay:false,timestamp is early than today:true
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4122, uid=10154, userID:0
I/ActivityManager(  905): Killing 1379:com.htc.sense.hsp/u0a53 (adj 15): empty #17
,D/ACRA    ( 4168): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4168): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4168): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4168): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4168): Preparing secondary program dexes.
,I/SensorManager(  905): mEventCount = 1200
V/DexLibLoader( 4168): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4168): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4168): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4168): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4168): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4168): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4168): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4168): Dex already copied
D/OdexVerifier( 4168): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4168): Creating class loader
,I/ActivityManager(  905): Recipient 1379
,V/DexLibLoader( 4168): Finished creating class loader
,V/DexLibLoader( 4168): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4168): Dex already copied
D/OdexVerifier( 4168): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4168): Creating class loader
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/DexLibLoader( 4168): Finished creating class loader
V/DexLibLoader( 4168): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4168): Dex already copied
D/OdexVerifier( 4168): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4168): Creating class loader
,V/DexLibLoader( 4168): Finished creating class loader
,V/DexLibLoader( 4168): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4168): Dex already copied
D/OdexVerifier( 4168): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4168): Creating class loader
,V/DexLibLoader( 4168): Finished creating class loader
,V/DexLibLoader( 4168): Verifying classes from secondary dexes.
,D/DexLibLoader( 4168): DexLibLoader.ensureDexLoaded took 95 ms
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  905): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4014): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1108): WifiActivity: 3
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/dalvikvm( 4168): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4168): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4168): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4168): Verify
,E/BTIF_CORE( 3926): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3926): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3926): Wake lock released
,D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  365): [NET] +++++ res_nsend xid =ecb9 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4168/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4168): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4168): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/WifiStateMachine(  905): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  905): Find DNS Address www.htc.com/23.59.123.86
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,W/ActivityManager(  905): Disable JIT of com.htc.bgp
,I/ActivityManager(  905): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4189 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
D/Process (  905): killProcessQuiet, pid=3771
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3771:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3771
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 4189): Created com.android.providers.calendar.CalendarAlarmManager@41acb990(com.android.providers.calendar.HtcCalendarProvider@41ab3d18)
,D/CalendarProvider2( 4189): wait start:true
,D/CalendarProvider2( 4189): wait end:false
D/PMS     (  905): acquireWL(426f0278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  905): acquireWL(433a1030): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(426f0278): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/fb4a(:<default>):UserScope( 4168): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4168): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/GCM     ( 1341): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,W/fb4a(:<default>):UserScope( 4168): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  905): releaseWL(433a1030): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420b31a8
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420b31a8, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42171ac0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@42577890
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
I/PMS     (  905): Going to sleep due to screen timeout...
I/ActivityManager(  905): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,W/PMS     (  905): mWirelessDisplayManager is null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1341): [NET] getaddrinfo-,err=8
D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1341): [NET] getaddrinfo-, 1
,D/libc    ( 1341): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c478 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  905): acquireWL(439cb560): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1341 10028 null
,I/ActivityManager(  905): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4213 uid=10053 gids={50053, 1023, 3003, 5012}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 12
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1341): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1341): [NET] getaddrinfo-,err=8
W/ActivityThread( 1341): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): acquireWL(4330b488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): releaseWL(4330b488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1341): Connected
D/PMS     (  905): acquireWL(424fc560): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/PMS     (  905): releaseWL(439cb560): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/PMS     (  905): releaseWL(424fc560): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  905): acquireWL(42564548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1341): Message class mpf
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1341/10028)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): releaseWL(42564548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  905): acquireWL(433ca528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(433ca528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 371ms
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
D/PMS     (  905): OOBE c monitor 11
V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43ebb380)
D/NfcService( 1223): ScreenObserver: OFF
,D/NfcService( 1223): applyRouting - 0
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
,D/NfcService( 1223): applyRouting -2
D/PMN     (  905): wakingUp
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=3879
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): acquireWL(425e7970): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1223 1027 null
D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  905): releaseWL(425e7970): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  905): onScreenOn
,D/PMS     (  905): acquireWL(42c824f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42c824f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/MtpService( 2211): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2211): [MTP][onReceive]-
,D/NfcService( 1223): applyRouting - 0
,D/NfcService( 1223): applyRouting -2
D/PMS     (  905): acquireWL(4398ab18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1223 1027 null
D/PMS     (  905): releaseWL(4398ab18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  905): updateBatteryInfo
D/AlarmManager(  905): ACTION_SCREEN_ON
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19723 delay=15s
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/ClockThread( 1108): stop update clock
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [14][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): SET_SCREEN_ON:On
I/wpa_supplicant( 4014): htc_wext_set_keepalive +
I/wpa_supplicant( 4014): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4014): getPrivFuncNum +	
I/wpa_supplicant( 4014): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  905):    returned true
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WIFI_ICON( 1108): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  905): updateScreenOn: false
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(43e555b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1395 10028 null
D/PMS     (  905): releaseWL(43e555b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): onScreenOn: 1449748644059
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3990): onScreenOn: 1449748644060
I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42171ac0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42171ac0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@42577890
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
D/PMS     (  905): acquireWL(428927b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/AlarmManager(  905): ACTION_SCREEN_OFF
,I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19723 mDataStallAlarmIntent=PendingIntent{41ec3e50: PendingIntentRecord{424f9b30 android broadcastIntent}}
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): SET_SCREEN_ON:Off
I/wpa_supplicant( 4014): htc_wext_set_keepalive +
I/wpa_supplicant( 4014): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4014): getPrivFuncNum +	
I/wpa_supplicant( 4014): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4014): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4014): get_ip_address source addr = c0a80176
I/wpa_supplicant( 4014): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 4014): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  905): acquireWL(43ec7ca0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/NetworkPolicy(  905): updateScreenOn: false
D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
D/ContactMessageStore( 1213): Background delete complete
,D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(43ec7ca0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,E/dalvikvm( 4168): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4168): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4168): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4168): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4168): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4168): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4168): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4168): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4168): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4168): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4168): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4168): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4168): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4168): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4168): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4168): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3990): onScreenOff
D/PMS     (  905): acquireWL(437fea88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1395 10028 null
D/PMS     (  905): releaseWL(437fea88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 9.959MB for 84664-byte allocation
W/dalvikvm( 4168): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4168): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PluginProvider( 4213): PluginProvider onCreate
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 9.986MB for 39954-byte allocation
,D/PluginProvider( 4213): current plugin count: 19
,D/HtcAppUPService( 4213): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 10.062MB for 79892-byte allocation
,D/AutoSetting( 4213): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 10.089MB for 28144-byte allocation
D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/Process (  905): killProcessQuiet, pid=3791
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4238 uid=10078 gids={50078, 3003, 5012}
I/ActivityManager(  905): Killing 3791:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4213/10053)
,D/ContactMessageStore( 1213): notify MmsSms
D/AccFlag ( 1213): sense_version=6.0
D/AccFlag ( 1213): sku_id=99
,D/AutoSetting( 4213): service - onCreate()
,D/AutoSetting( 4213): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4213): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 4213): service - onStartCommand() screen is off, don't request location
,D/LocationManagerService(  905): request 42402748 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4213): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4213): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4213/10053)
,D/MobileConnectivityChangeReceiver( 4238): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4238): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4238): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4238): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  905): Recipient 3791
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4238/10078)
,I/dalvikvm-heap( 4168): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4255 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4238/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4238/10078)
,D/PMS     (  905): acquireWL(42a44be8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4168/10026)
,D/PMS     (  905): acquireWL(43ebe398): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e38f90 u0 ReceiverList{432e9538 4168 com.facebook.katana/10026/u0 remote:42594428}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e38f90 u0 ReceiverList{432e9538 4168 com.facebook.katana/10026/u0 remote:42594428}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4358a228 u0 ReceiverList{4358a1c8 4168 com.facebook.katana/10026/u0 remote:431e0860}}
,D/PMS     (  905): releaseWL(42a44be8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/CheckinService( 1199): Preparing to send checkin request
,I/EventLogService( 1199): Accumulating logs since 1449747000160
,I/CalendarProvider2( 4189): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4189): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4168/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4168/10026)
,I/ActivityManager(  905): Killing 3758:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/Process (  905): killProcessQuiet, pid=3758
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4168/10026)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4255): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4255): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  905): Recipient 3758
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(426c0550): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,W/GAV2    ( 4255): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  905): releaseWL(426c0550): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ContextImpl( 4255): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4255): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/GCoreFlp( 1395): Unknown pending intent to remove.
W/EventLogAggregator( 1199): Unknown tag: install_package_attempt
W/EventLogAggregator( 1199): Unknown tag: snet
,W/EventLogAggregator( 1199): Unknown tag: snet_gcore
D/PMS     (  905): acquireWL(42738fe8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
D/PMS     (  905): releaseWL(42738fe8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/ActivityManager(  905): Activity pause timeout for ActivityRecord{41aa0710 u0 com.test.thalitest/.MainActivity t2}
,I/GoogleHttpClient( 1199): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1199): Using GMS GoogleHttpClient
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4255/10151)
,V/WebViewChromiumFactoryProvider( 4255): Binding Chromium to main looper Looper (main, tid 1) {41a94fb8}
,I/LibraryLoader( 4255): Expected native library version number "",actual native library version number ""
,I/chromium( 4255): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4255): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(43e8d878): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4255): BLUETOOTH permission is missing!
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4168): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  905): acquireWL(43edee78): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(43e8d878): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
I/Adreno-EGL( 4255): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4255): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4255): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4255): Local Branch: 
I/Adreno-EGL( 4255): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4255): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4255):                  aa63bbd948f41d15fc72f585e
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4168): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4168): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 4255): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4255/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4255/10151)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3661/10160)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3661/10160)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4014): environment dirty rate=0 [0][0][0]
,D/Process (  905): killProcessQuiet, pid=3807
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3807:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
,I/ActivityManager(  905): Recipient 3807
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,D/AlertReceiver( 3826): beginStartingService
D/PMS     (  905): acquireWL(434629c0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3826 10013 null
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/PMS     (  905): acquireWL(4341f068): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  905): releaseWL(4341f068): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 3826): start to updateAlertNotification!
I/NotificationStore( 1341): System rebooted after Notification storage file was last written
,I/NotificationStore( 1341): Deleting the file
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4305 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/CheckinRequestBuilder( 1199): awaiting user notification for token
D/AlertService( 3826): No fired or scheduled alerts
,D/HtcAlertUtils( 3826): -- cancelReminderNotification --
,D/HtcAlertUtils( 3826): broadcastExistReminder!
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  905): releaseWL(434629c0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/AlertReceiver( 3826): stopSelfResult true
,W/WeatherRequest( 1108): request cur loc, but there is no sys cur
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41aa3c58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 2 8 3 12
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4320 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4305): can't get weather sync account
,W/WeatherRequest( 4305): request cur loc, but there is no sys cur
,W/Settings( 4305): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  905): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4332 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  905): acquireWL(42ac4fd0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4320 10070 null
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  905): acquireWL(427fa570): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4320 10070 null
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 8 17
D/PMS     (  905): releaseWL(42ac4fd0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/MultiDex( 4332): install
,I/MultiDex( 4332): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4332): loading existing secondary dex files
,I/MultiDex( 4332): load found 1 secondary dex files
,I/MultiDex( 4332): install done
,I/TodoTaskNotifyService( 4320): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TodoTaskshortcut( 4320): update TASK shortcut>
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4349 uid=10090 gids={50090, 3003, 5012, 1028}
I/ProviderInstaller( 4332): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/TodoTaskNotifyService( 4320): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4320): stopSelfResult true
,D/Process (  905): killProcessQuiet, pid=3534
D/PMS     (  905): releaseWL(427fa570): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  905): Killing 3534:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/WorldClock.Global( 4349): isHtcDevice = true
,I/WorldClock.Global( 4349): isHtcDevice = true
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 4349): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 4349): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 4349): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4364 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IntentController( 1108): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3534
,D/TimeService( 4364): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748645258
,D/Process (  905): killProcessQuiet, pid=3625
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3625:com.android.vending/u0a73 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3625
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4031
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4031:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  905): Recipient 4031
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4379 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4379): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4379): MmsConfig.loadMmsSettings
,E/dalvikvm( 4379): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4379): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (4332/10028)
E/dalvikvm( 4379): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 4379): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 4379): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,I/ActivityManager(  905): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4402 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4379, uid=10111, userID:0
,W/Settings( 4379): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4402): onCreate
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4379, uid=10111, userID:0
,V/GetPrviateResource( 4402): GetPrviateResource
,V/GetPrviateResource( 4402): GetPrviateResource
,D/MmsCustomizationProvider( 4402): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4379, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4379, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4379, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4379, uid=10111, userID:0
,D/MmsCustomizationProvider( 4402): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4379): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4379): MmsConfig.loadFromDatabase
,E/Babel   ( 4379): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4379): MmsConfig.loadFromResources
,E/Babel   ( 4379): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4379): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,I/ProviderInstaller( 4379): Installed default security provider GmsCore_OpenSSL
,D/Process (  905): killProcessQuiet, pid=4019
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Killing 4019:com.htc.widget.process2/u0a48 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4019
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4379/10111)
,D/MessageCustFlag( 4402): sense_version=6.0
,D/BTAccessoryUtil( 4402): createReceiver
,D/BTAccessoryUtil( 4402): registerReceiver return intent = null
D/MessageCustFlag( 4402): sku_id=99
,W/SystemReader( 4402): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4402): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4402): networkCode: 
,D/MessageCustFlag( 4402): sku_id=99
D/MmsConfig( 4402): SIE smsPri: null
,D/MmsConfig( 4402): networkCode: 
D/HtcTelephonyCapability( 4402): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4402): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4402): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4402): Cannot find qct_8960_interface, use default value instead
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4379/10111)
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4379): UserRecoverableAuthException.
,E/Babel   ( 4379): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4379): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4379): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4379): Error getting auth token
,E/Babel   ( 4379): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4379): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4379): Account registration failedRedacted-21
E/Babel   ( 4379): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4379): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,I/Babel   ( 4379): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4379): Account sign in complete with state 106account: Redacted-21
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.talk (4379/10111)
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4379): Unexpected exception while authenticating.
,E/Babel   ( 4379): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4379): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4379): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4379): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4379): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4379): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4379): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4379): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4379): 	at java.lang.Thread.run(Thread.java:864)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41af11f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 8 2 12
,W/Settings( 4332): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3951
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 4213): receiver - intent: android.intent.action.USER_PRESENT
I/ActivityManager(  905): Killing 3951:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
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
,D/AutoSetting( 4213): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3316): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Recipient 3951
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SmartNS_PSService( 3316): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3316):  defaultType:0
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4427 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/Adreno-EGL( 4332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4332): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4332): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4332): Local Branch: 
I/Adreno-EGL( 4332): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4332): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4332):                  aa63bbd948f41d15fc72f585e
,W/ContextImpl( 4427): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4427): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(4249fd10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4427 1000 null
,I/Adreno-EGL( 4332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4332): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4332): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4332): Local Branch: 
I/Adreno-EGL( 4332): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4332): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4332):                  aa63bbd948f41d15fc72f585e
D/PMS     (  905): releaseWL(4249fd10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4427): getMobilePolicyEnabled, result = true
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/Adreno-EGL( 4332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4332): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4332): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4332): Local Branch: 
I/Adreno-EGL( 4332): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4332): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4332):                  aa63bbd948f41d15fc72f585e
,W/ContextImpl( 4427): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4427): isEpsOn(), nState = 0
D/SmartSyncUtils( 4427): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4427): isEpsOn(), nState = 0
D/WifiService(  905): New client listening to asynchronous messages
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42577890
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/ProviderChangeReceiver( 3826): ---------------------------------------------------
,D/ProviderChangeReceiver( 3826): ProviderChangeReceiver onReceive, start to update notification!
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42577890, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42577890, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42577890
,D/AlertService( 3826): start to updateAlertNotification!
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42577dd8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42577dd8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/AlertService( 3826): No fired or scheduled alerts
D/HtcAlertUtils( 3826): -- cancelReminderNotification --
,D/HtcAlertUtils( 3826): broadcastExistReminder!
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4346ceb8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4320 10070 null
,D/PMS     (  905): acquireWL(425253a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4320 10070 null
,D/Process (  905): killProcessQuiet, pid=3970
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3970:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,D/PMS     (  905): releaseWL(4346ceb8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/TodoTaskNotifyService( 4320): java.lang.NullPointerException
,W/System.err( 4320): java.lang.NullPointerException
W/System.err( 4320): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4320): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4320): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4320): stopSelfResult true
I/ActivityManager(  905): Recipient 3970
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.google.android.gms/.gcm.ServiceAutoStarter
D/PMS     (  905): releaseWL(425253a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/CheckinTask( 1199): Sending checkin request (8964 bytes)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4376ff70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4320 10070 null
,D/PMS     (  905): acquireWL(4450c618): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4320 10070 null
,W/ActivityThread( 1199): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 4320): java.lang.NullPointerException
,W/System.err( 4320): java.lang.NullPointerException
W/System.err( 4320): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4320): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4320): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): releaseWL(4376ff70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(4450c618): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,W/NotifyReceiver( 4320): stopSelfResult true
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4456 uid=10038 gids={50038}
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1199): [NET] getaddrinfo-,err=8
D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1199): [NET] getaddrinfo-, 1
D/libc    ( 1199): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =aed6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 204
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1199): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1199): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1199): [NET] getaddrinfo-,err=8
,I/jxcore-log( 3879): Test app app.js loaded
I/jxcore-log( 3879): 
,D/Process (  905): killProcessQuiet, pid=4122
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/Choreographer( 3879): Skipped 544 frames!  The application may be doing too much work on its main thread.
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4471 uid=10077 gids={50077}
I/ActivityManager(  905): Killing 4122:com.google.android.music:main/u0a154 (adj 15): empty #17
,W/ResourceType( 3879): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3879): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa0400 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  905): releaseWL(428927b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 3879): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SMSBackup( 4471): Got a database change event
,D/Process (  905): killProcessQuiet, pid=4168
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 4168:com.facebook.katana/u0a26 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4122
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.music (pid 4122): Died!
,I/ActivityManager(  905): Recipient 4168
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  905): Client connection lost with reason: 4
,D/PMS     (  905): acquireWL(43af6c78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,D/PMS     (  905): acquireWL(43af02e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,D/PMS     (  905): releaseWL(43af6c78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(43af02e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): acquireWL(439d99f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(439d99f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  905): getNetworkInfo networkType=9 called by com.google.android.gms (1199/10028)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.gms (1199/10028)
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: survey data missing!
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4014): environment dirty rate=0 [18][0][0]
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1199): awaiting user notification for token,
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41d93a80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 11 3 12
,I/CheckinTask( 1199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1199): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  905): releaseWL(43ebe398): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1199): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b5baa8 that was originally bound here
E/ActivityThread( 1199): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b5baa8 that was originally bound here
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
,I/GCM     ( 1341): GCM config loaded
,D/Messaging( 4402): mNeedToUpdateDate2 start
,D/MmsConfig( 4402): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4402): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4402): 
D/MmsAsyncWorkHandler( 4402): HM tk = 20001
,D/ReportIndicatorCache( 4402): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4402): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a9a688
,I/Messaging( 4402): mccmnc> 
D/DraftCache( 4402): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4402): [DraftCache/1] refresh
,D/MmsConfig( 4402): networkCode: 
,D/Messaging( 4402): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4402): sense_version=6.0
,D/Jerry   ( 4402): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4402): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4402): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4402): createReceiver
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1213): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,V/MmsProvider( 1213): Update uri=content://mms, match=0
V/MmsProvider( 1213): selection=st=129 AND m_type!=134
,D/Messaging( 4402): mNeedToUpdateDate2: false
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1213): sku_id=99
,D/Messaging( 4402): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4402): TransactionService is going to be woken up.
,D/DraftCache( 4402): [DraftCache/454] rebuildCache
,V/TransactionService( 4402): 1-Creating TransactionService
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,V/TransactionService( 4402): onStartCommand: 1
,D/MmsSystemEventReceiver( 4402): unRegisterForConnectionStateChanges
,V/TransactionService( 4402): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4402): Loading previous transactions.
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/Jerry   ( 1213): URI_DRAFT
D/Messaging( 4402): ViewCache CreatePreload
,D/Messaging( 4402): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1213): device_type: 1
D/DraftCache( 4402): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4402): [DraftCache/454] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4402): 
D/MmsAsyncWorkHandler( 4402): HM tk = 20002
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1213):  phoneType = -1
D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Cust_MMSMS( 4402): _has_set_default_values_2=true
D/TransactionService( 4402): Force set service start id to 1
V/TransactionService( 4402): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4402): unRegisterForConnectionStateChanges
V/TransactionService( 4402): Destroying TransactionService
,D/TransactionService( 4402): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4402): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4402): def_index: 0
,D/MsgPreferenceUtils( 4402): globalIndex = 1
,D/PMS     (  905): releaseWL(43edee78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1213): sku_id=99
D/MsgPreferenceUtils( 4402): phone state: true
D/MsgPreferenceUtils( 4402): sd state: false
D/MsgPreferenceUtils( 4402): vIndex = 0
,D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1213):  phoneType = -1
,D/MmsSmsV2Provider( 1213): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4402): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1213): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1213): sku_id=99
,I/GAV2    ( 4255): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  905): killProcessQuiet, pid=3421
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3421:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3421
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4379, uid=10111, userID:0
,D/Process (  905): killProcessQuiet, pid=4238
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4238:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4238
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=4139
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4139:com.android.chrome/u0a96 (adj 15): empty #17
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  905): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  905): Recipient 4139
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4213): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4213): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4213): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42848d30 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=29, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/Launcher( 1247): Deferring update until onResume
,D/Launcher( 1247): waitUntilResume // bindAppsUpdated
,I/PeopleContactsSync( 1199): CP2 sync disabled
,D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,W/SystemReader( 1223): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/[PluginManager]RegisterService( 4213): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 4213): handle notify Blinkfeed plugin client changed
D/PMS     (  905): acquireWL(42817a20): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4515 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,E/ExternalAccountType( 1311): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
D/PMS     (  905): releaseWL(42817a20): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
,D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4515, uid=10073, userID:0
,D/Finsky  ( 4515): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4515/10073)
,D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4515/10073)
,D/Finsky  ( 4515): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4515): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4515): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4515, uid=10073, userID:0
,D/Finsky  ( 4515): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4515): [1] 2.run: Finished loading 1 libraries.
,D/Process (  905): killProcessQuiet, pid=4255
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4255:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/IcingCorporaProvider( 2666): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,D/Finsky  ( 4515): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PMS     (  905): acquireWL(4301f5f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3661 10160 null
,D/PMS     (  905): releaseWL(4301f5f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Finsky  ( 4515): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  905): Recipient 4255
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3661): Grow heap (frag case) to 13.506MB for 1821008-byte allocation
,I/IcingCorporaProvider( 2666): UpdateCorporaTask done [took 229 ms] updated apps [took 229 ms] 
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41b22fb0 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
,D/PMS     (  905): acquireWL(425b1318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10073}
,V/AlarmManager(  905): sending alarm PendingIntent{42795868: PendingIntentRecord{41f728d8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449748662432, Int=0
,W/PackageManager(  905): Unable to load service info ResolveInfo{4338aea8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/asset   ( 1247): Copying FileAsset 0x62a282b8 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41b22fb0 -
,D/PhoneApp( 1213): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1213): -- N1 =0
,D/PhoneApp( 1213): -- N2 =0
,D/PhoneApp( 1213): -- N3 =0
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
,D/PMS     (  905): releaseWL(425b1318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4515): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4515): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4515): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4515): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4515): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/PMS     (  905): acquireWL(428016d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(428016d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4240e630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41d723f8: PendingIntentRecord{42418538 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=137322, Int=0
,D/PMS     (  905): acquireWL(428949c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): releaseWL(4240e630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(434f8810): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(428949c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  905): releaseWL(434f8810): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4213): service - mHandler: update timezone
,D/AutoSetting( 4189): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4189): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4189): service - onCreate(),
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4189): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4189): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 4189): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4189): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4189): service - mHandler: update timezone
,D/AutoSetting( 4189): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4189): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4189): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4189): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1108): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41db9d10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.htc.htclocationservice 4 5 2 11
,D/AutoSetting( 4213): service - handleMessage() stop self
,D/AutoSetting( 4213): service - handleMessage() quit looper
,D/AutoSetting( 4213): service - onDestroy() END
,D/PMS     (  905): acquireWL(432e7a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(432e7a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1213): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  905): acquireWL(42592740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10028},
,V/AlarmManager(  905): sending alarm PendingIntent{42093e10: PendingIntentRecord{4254dc80 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140134, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42454d20: PendingIntentRecord{42454cc0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141178, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42b64638: PendingIntentRecord{4336f5a0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449748678368, Int=0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/PMS     (  905): acquireWL(427939a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
,D/PMS     (  905): releaseWL(427939a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(425429f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42592740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9a98 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Finsky  ( 4515): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  905): acquireWL(42d7eae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42d7eae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): releaseWL(425429f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42729ae0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 4189): service - handleMessage() stop self
,D/AutoSetting( 4189): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=4305
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 4189): service - handleMessage() quit looper
I/ActivityManager(  905): Killing 4305:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4305
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1213): switchBindHtcMsgCursor: null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/Process (  905): killProcessQuiet, pid=4349
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4349:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4349
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42cd6a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PowerUI ( 1108): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42cd6a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42530150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42530150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42683f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42683f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(43e20538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e20538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(42877d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42877d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42c9f5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42c9f5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42885438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=325939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42885438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(42749240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42749240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3879): Toggling radios to false
I/jxcore-log( 3879): 
D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@422b2f00 mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1246
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	,at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 3(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  905): Sending off request.
,D/WifiManager( 3879): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
D/BluetoothAdapterState( 3926): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3926): Setting state to 13
I/BluetoothAdapterState( 3926): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3926): Broadcasting updateAdapterState() to 1 receivers.
,D/WifiStateMachine(  905): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=12 new=13
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 12 -> 13
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1243
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/WifiService(  905): setWifiEnabled: false pid=3879, uid=10348
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
D/BluetoothAdapterProperties( 3926): onBluetoothDisable()
I/BluetoothAdapterState( 3926): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3926): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3926): BTM_SetDiscoverability
I/bt-btm  ( 3926): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3926): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3926): br_edr_supported=0x0
I/bt-btm  ( 3926): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3926): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterProperties( 3926): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 3926): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3926): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_SetConnectability
I/bt-btm  ( 3926): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3926): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
V/BluetoothPbapReceiver( 3926): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3926): ***********state = 13
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 9(ms)
D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3926): SapReceiver onReceive 
V/BluetoothSapReceiver( 3926): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3926):  Bluetooth Adapter state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 3990): Received state change = 13
V/BluetoothSapReceiver( 3926): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abad60
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): onDeInitialized
D/BluetoothAdapterProperties( 3926): Scan Mode:20
E/BTIF_CORE( 3926): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 3926): HAL bt_hal_cbacks->wake_state_changed_cb
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): getNotificationManager
,D/BluetoothAdapterState( 3926): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3926): BTA_JvDeleteRecord
I/bt-btif ( 3926): BTA_JvRfcommStopServer
D/bt-btm  ( 3926): BTM_FreeSCN 
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 3926): BTA_JvDeleteRecord
E/bt-btif ( 3926): BTA_JvRfcommStopServer
I/bt-btif ( 3926): BTA_JvRfcommStopServer
D/bt-btm  ( 3926): BTM_FreeSCN 
I/bt-btm  ( 3926): BTA_JvDeleteRecord
I/bt-btif ( 3926): BTA_JvDeleteRecord
I/bt-btif ( 3926): SDP_DeleteRecord ok, n
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:14
D/bt-btm  ( 3926): bta_jv_rfcom
E/bt-btif ( 3926): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3926): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 3926): bta_jv_rfcomm_stop_server
I/bt-btif ( 3926): BTA_JvDeleteRecord
I/bt-btm  ( 3926): BTA_JvRfcommStopServer
I/bt-btif ( 3926): BTA_JvRfcommStopServer
D/bt-sdp  ( 3926): BTM_FreeSCN 
D/bt-btm  ( 3926): BTM_FreeSCN 
E/bt-btif ( 3926): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3926): BTM_SEC_CLR[16]: id 55
I/bt-btif ( 3926): BTA_JvDeleteRecord
I/bt-btif ( 3926): BTA_JvRfcommStopServer
D/bt-btm  ( 3926): BTM_FreeSCN 
I/bt-btif ( 3926): BTA_JvDeleteRecord
I/bt-btif ( 3926): BTA_JvRfcommStopServer
D/bt-btm  ( 3926): BTM_FreeSCN 
V/BluetoothSapService( 3926): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3926): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 3926): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3926): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 3926): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3926): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): Write Extended Inquiry Response to controller
I/bt-btm  ( 3926): BTM_SetDiscoverability
I/bt-btm  ( 3926): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3926): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3926): br_edr_supported=0x0
I/bt-btm  ( 3926): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3926): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3926): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3926): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3926): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_SetConnectability
I/bt-btm  ( 3926): btm_ble_set_connectability mode=0x0 combined_mode=0x0
,I/bt-btm  ( 3926): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3926): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3926): BTM_IsInquiryActive
I/bt-btm  ( 3926): BTM_CancelRemoteDeviceName()
W/bt-btif ( 3926): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3926): BTM_FreeSCN 
I/bt-btm  ( 3926): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3926): BTM_FreeSCN 
I/bt-btm  ( 3926): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3926): AVRC_Close handle:0
D/PMS     (  905): acquireWL(42c4fc88): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 3926 1002 null
D/PMS     (  905): acquireWL(42619358): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 3926): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3926): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3926): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 3926): GATT_Deregister gatt_if=3
,I/bt-att  ( 3926): GATT_Deregister gatt_if=4
V/BluetoothPbapService( 3926): Pbap Service closeService in
,D/BluetoothRemoteDevices( 3926): Wake lock Aquired
D/PMS     (  905): releaseWL(42619358): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  905): acquireWL(4344b5a0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
,D/WirelessDisplayService(  905): getMirrorDisplayStatus:falsecurState:1
,D/DockEventReceiver( 3316): finishStartingService: stopping service
D/WifiPerfLock(  905): release()
,D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4577 uid=10037 gids={50037, 3002, 3001}
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
I/jxcore-log( 3879): Radios toggled
I/jxcore-log( 3879): 
,D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): Power_Mode_Type mode = 0
I/wpa_supplicant( 4014): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
,D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothPbap( 3316): Proxy object disconnected
,D/PbapServerProfile( 3316): Bluetooth service disconnected
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): onScreenOff.
D/WifiNative-wlan0(  905):    returned true
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3990): init: null, null
,D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3990):  + initPendingRequestAlarm: false, mContext = null, null
D/BluetoothPbap( 3840): Proxy object disconnected
D/PMS     (  905): acquireWL(428669d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
D/PMS     (  905): releaseWL(4344b5a0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiP2pService(  905): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PbapServerProfile( 3840): Bluetooth service disconnected
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3990): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3990):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3990): deinit: 0
I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1108): removeIcon slot=bluetooth index=12 viewIndex=0
D/BluetoothManagerService(  905): Message: MESSAGE_UNREGISTER_ADAPTER
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/BluetoothManagerService(  905): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422e9d38:true
V/BluetoothPbapService( 3926): successfully stopped pbap service
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
V/BluetoothPbapService( 3926): Pbap Service closeService out
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3990): disableBatteryAlarm: null
I/BtOppRfcommListener( 3926): stopping Accept Thread
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3990): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3990): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3990): init: null
I/BtOppRfcommListener( 3926): BluetoothSocket listen thread finished
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3990): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3990): Exit IdleState
V/BluetoothSapService( 3926): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3926): state: 13
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3926): 1101716304: getState(). Returning 13
V/BluetoothSapService( 3926): Stopping SAP server process
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/BluetoothSapService( 3926): Sap Service closeSapService in
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
V/BluetoothSapService( 3926): Close listen Socket : 
V/BluetoothSapService( 3926): Close rfcomm Socket : 
V/BluetoothSapService( 3926): Close sapd  Socket : 
V/BluetoothSapReceiver( 3926): BluetoothSapReceiver deinit
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19724 mDataStallAlarmIntent=null
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  905):    returned null
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
,D/UsbnetStateTracker(  905): isAvailable+-
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Call handleNetworkDisconnect() in SupplicantStoppingState
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  905): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiP2pService(  905): P2pDisablingState
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  905): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): p2p socket connection lost
D/WifiP2pService(  905): P2pDisabledState
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  905): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
D/HtcBtWidget_BTWidgetProvider( 4577): onBTStateChanged() for widget: 
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4014): Power_Mode_Type mode = 0
I/wpa_supplicant( 4014): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 61
D/SapServerProfile( 3840): Bluetooth service disconnected
D/SapServerProfile( 3316): Bluetooth service disconnected
V/BluetoothSapService( 3926): successfully stopped Sap service
,V/BluetoothSapService( 3926): Sap Service closeSapService out
,D/HtcBtWidget_BTWidgetProvider( 4577): updateWidget(context) for widget: 
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 4014): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4014): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/BluetoothPbapService( 3926): Pbap Service onDestroy
V/BluetoothPbapService( 3926): Pbap Service closeService in
V/BluetoothPbapService( 3926): Pbap Service closeService out
V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
,D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  905): convertEffect before=902
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/HtcEffectManager(  905): convertEffect after=902
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  905):    returned true
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  905): updateConnection
I/WifiDisplayController(  905): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  905): updateConnection enter step 4
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/WifiP2pService(  905): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  905): Failed to set WFD info with reason 2.
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  905): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapService( 3926): onUnbind: android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3926): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ae5e98
V/BluetoothSapService( 3926): Sap Service closeSapService in
V/BluetoothSapService( 3926): Close listen Socket : 
V/BluetoothSapService( 3926): Close rfcomm Socket : 
,V/BluetoothSapService( 3926): Close sapd  Socket : 
D/Process (  905): killProcessQuiet, pid=4364
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-p2p0(  905): doBoolean: TERMINATE
W/WifiHW  (  905): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 4014): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-p2p0(  905):    returned true
D/wpa_supplicant( 4014): TDLS: Tear down peers
I/wpa_supplicant( 4014): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
V/BluetoothSapService( 3926): Sap Service closeSapService out
,V/BluetoothSapService( 3926): ***onDestroyed***
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
I/ActivityManager(  905): Killing 4364:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  365): [NET] entry_id:5   entry:0xb8477100  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb847bda8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb847bf70  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb84778d8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8477458  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  905): acquireWL(424bc4a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1341 10028 null
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  905): Recipient 4364
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(43a8a520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10028 null
W/ActivityManager(  905): Failed to clear dns cache for: com.qualcomm.timeservice
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  905): releaseWL(43a8a520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/PMS     (  905): acquireWL(428606a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (1341/10028)
,D/PMS     (  905): releaseWL(424bc4a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
E/BluetoothFtpService:RfcommSocketAcceptThread( 3926): Shutdown
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 4014): Clean 'force_connect' when disconnect
I/wpa_supplicant( 4014): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 4014): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4014): TDLS: Remove peers on disassociation
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4014): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8998bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4014):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4014): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 4014): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4014): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4014): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 4014): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4014): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4014): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized ,for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:0
I/ActivityManager(  905): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4595 uid=10048 gids={50048}
D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 13
,I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/PMS     (  905): releaseWL(428606a8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3990): Received state change = 13
,W/bt-btif ( 3926): ag scb idx 1 not allocated
W/bt-btif ( 3926): ag scb idx 2 not allocated
E/bt-btif ( 3926): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3926): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3926): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3926): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3926): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3926): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3926): L2CAP - PSM: 0x0017 not found for deregistration
,D/Process (  905): killProcessQuiet, pid=4379
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 4379:com.google.android.talk/u0a111 (adj 15): empty #17
,D/HtcWiFiWidget_WiFiWidgetProvider( 4595): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4595): updateWidget(context) for widget: 
,D/Process (  905): killProcessQuiet, pid=4427
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  905): Killing 4427:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
E/bt_userial_mct( 3926): userial_close userial_thread_created userial_running is 1 
,I/ActivityManager(  905): Recipient 4427
,D/WifiService(  905): Client connection lost with reason: 4
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4379
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 4014): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 4014): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 4014): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 4014): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4014): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 4014): nl80211: Unsubscribe mgmt frames handle 0xb8999718 (mode change)
I/wpa_supplicant( 4014): htc_wext_command_deinit +
I/wpa_supplicant( 4014): htc_wext_command_deinit -
E/wpa_supplicant( 4014): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 4014): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4014): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 4014): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4014): TDLS: Tear down peers
I/wpa_supplicant( 4014): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4014): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4014): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4014): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4014): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4014): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4014): send_and_recv error 0 - cmd 18
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,I/bt-btif ( 3926): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3926): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3926): Received stop request...Stopping profile...
,D/BluetoothHeadset(  905): Proxy object disconnected
D/BluetoothHeadset( 1213): Proxy object disconnected
,D/BluetoothPhoneService( 1213): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1213): Proxy object disconnected
,D/BluetoothHeadset( 1108): Proxy object disconnected
I/QuickSettingMiniLite( 1108): btListener.disconnect:HEADSET
D/BluetoothAdapterState( 3926): Stopping profile services that were post enabled
D/A2dpService( 3926): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3926): doQuit
,D/A2dpStateMachine( 3926): Exit Disconnected: -1
D/BluetoothHeadset( 3840): Proxy object disconnected
D/HeadsetProfile( 3840): Bluetooth service disconnected
,D/BluetoothA2dp(  905): Proxy object disconnected
D/BluetoothHeadset( 3316): Proxy object disconnected
D/HeadsetProfile( 3316): Bluetooth service disconnected
D/BluetoothA2dp( 3316): Proxy object disconnected
D/A2dpProfile( 3316): Bluetooth service disconnected
D/BluetoothA2dp( 3840): Proxy object disconnected
,D/A2dpProfile( 3840): Bluetooth service disconnected
,D/HidService( 3926): Received stop request...Stopping profile...
D/BluetoothInputDevice( 3840): Proxy object disconnected
,D/HidProfile( 3840): Bluetooth service disconnected
D/BluetoothInputDevice( 3316): Proxy object disconnected
,D/HidProfile( 3316): Bluetooth service disconnected
,D/HealthService( 3926): Received stop request...Stopping profile...
D/PanService( 3926): Received stop request...Stopping profile...
D/PanService( 3926): stop
,D/PanService( 3926): stop: mTetherAc send disconnect
,D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECT
,D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  905): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  905): BluetoothPAN Proxy object disconnected
,D/BluetoothAdapterService( 3926): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothPan( 3840): BluetoothPAN Proxy object disconnected
D/PanProfile( 3840): Bluetooth service disconnected
D/BluetoothPan( 3316): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3316): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 3926): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3926): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3926): Profile still running: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 3926): handleDebugAction() action=null
D/BtGatt.GattService( 3926): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3926): stop()
,D/A2dpStateMachine( 3926): cleanup
,D/Avrcp   ( 3926): Unregistering previous receiver
,D/BluetoothAdapterService( 3926): Profile still running: com.android.bluetooth.hdp.HealthService
,W/BluetoothHidServiceJni( 3926): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3926): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3926): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3926): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 3926): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3926): Cleaning up Bluetooth Health object
,D/PanService( 3926): CMD_CHANNEL_DISCONNECTED
D/PanService( 3926): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 3926): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 3926): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3926): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3926): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3926): Setting state to 10
I/BluetoothAdapterState( 3926): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3926): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  905): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(false) to 20 receivers.
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 3926): Entering OffState
D/BluetoothHeadset( 1108): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3316): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3316): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=false
E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x62b57c00
I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x67aed6f8
W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  905): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  905):    returned false
D/BluetoothHeadset(  905): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  905): onBluetoothStateChange: up=false
D/WifiStateMachine(  905): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  905): WIFI Trun OFF
,D/WirelessDisplayService(  905): getDiscoveryDongleList
D/BluetoothHeadset( 3316): onBluetoothStateChange: up=false
D/WIFI_ICON( 1108): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1108): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/BluetoothMap( 3316): onBluetoothStateChange: up=false
D/WifiStateMachine(  905): Exit handleNetworkDisconnect
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 6 { when=-122ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1108): receive(android.net.wifi.STATE_CHANGE,1,false)
E/BluetoothMap( 3316): 
E/BluetoothMap( 3316): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41c44660
E/BluetoothMap( 3316): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3316): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3316): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3316): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3316): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3316): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3316): 	at dalvik.system.NativeStart.run(Native Method)
,D/HtcWiFiWidget_WiFiWidgetProvider( 4595): onWiFiStateChanged() for widget: 
D/BluetoothInputDevice( 3840): onBluetoothStateChange: up=false
,D/HtcWiFiWidget_WiFiWidgetProvider( 4595): updateWidget(context) for widget: 
W/BluetoothHeadset( 1108): Proxy not attached to service
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  905): acquireWL(439dc618): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WIFI_ICON( 1108): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1108): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingMiniLite( 1108): updateLiteState:no connect device!
,D/WISPrService( 3316): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3316): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
D/BluetoothSap( 3316): onBluetoothStateChange on: false
D/BluetoothHeadset( 3840): onBluetoothStateChange: up=false
D/BluetoothPbap( 3316): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3840): onBluetoothStateChange: up=false
D/BluetoothMap( 3840): onBluetoothStateChange: up=false
,E/BluetoothMap( 3840): 
E/BluetoothMap( 3840): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41ac9a90
E/BluetoothMap( 3840): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3840): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3840): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3840): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3840): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3840): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3840): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothSap( 3840): onBluetoothStateChange on: false
,D/BluetoothPbap( 3840): onBluetoothStateChange: up=false
,I/QuickSettingWifi( 1108): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,D/BluetoothManagerService(  905): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceDown() to 11 receivers.
D/BluetoothAdapter( 1108): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41eb47c0
,D/BluetoothAdapter( 1108): onBluetoothServiceDown: done
D/BluetoothAdapter( 1213): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bf17c8
,D/BluetoothAdapter( 1213): onBluetoothServiceDown: done
D/BluetoothAdapter( 1751): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@420a5b28
D/BluetoothAdapter( 1751): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3926): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41aabfc0
D/BluetoothDevice( 3926): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 3926): onBluetoothServiceDown: done
D/BluetoothAdapter( 1395): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d0fab0
,D/BluetoothAdapter( 1395): onBluetoothServiceDown: done
D/BluetoothAdapter( 3879): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425ec918
D/BluetoothAdapter( 3879): onBluetoothServiceDown: done
,D/BluetoothAdapter(  905): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@422b2f00
D/BluetoothAdapter(  905): onBluetoothServiceDown: done
D/BluetoothAdapter( 1223): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bcc2a8
D/BluetoothAdapter( 1223): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3840): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ab1e98
D/BluetoothDevice( 3840): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 3840): onBluetoothServiceDown: done
,I/QuickSettingWifi( 1108): receive.wifiConnect:false wifiAPname:null elapse:2
D/BluetoothAdapter( 3316): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c2e790
D/BluetoothAdapter( 3316): onBluetoothServiceDown: done
D/BluetoothAdapter( 3990): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41abb630
,D/BluetoothAdapter( 3990): onBluetoothServiceDown: done
,D/BluetoothManagerService(  905): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@422b2f00 mBinding = false
,D/BluetoothManagerService(  905): Sending unbind request.
,D/BluetoothAdapterService( 3926): Cleaning up adapter native....
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 13 -> 10
,I/bt-btif ( 3926): HAL bt_hal_cbacks->thread_evt_cb
,D/NfcHandover( 1223): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/PMS     (  905): releaseWL(42c4fc88): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/LocalBluetoothProfileManager( 3316): setBluetoothStateOff
I/IntentController( 1108): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/HtcTagManager( 3316): stopProxy
,D/BluetoothAdapterService( 3926): Done cleaning up adapter native....
D/BluetoothAdapterService(1101698128)( 3926): ****onDestroy()********
D/BtGatt.GattService( 3926): cleanup()
D/LocalBluetoothProfileManager( 3840): setBluetoothStateOff
D/HtcTagManager( 3840): stopProxy
W/bt-btif ( 3926): GATTC Module not enabled/already disabled
W/bt-btif ( 3926): GATTS Module not enabled/already disabled
D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 10
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3990): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41abad60
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3990): deinitLeServices: null
V/BluetoothMasService( 3926): onDestroy: mIsEmailEnabled: true
,D/TetherPref( 3316): persistRestoreBluetoothState false
D/PMS     (  905): acquireWL(43204640): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3316 1000 null
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/TetherPref( 3840): persistRestoreBluetoothState false
,D/HtcBtWidget_BTWidgetProvider( 4577): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 4577): updateWidget(context) for widget: 
,D/DockEventReceiver( 3316): finishStartingService: stopping service
D/PMS     (  905): releaseWL(43204640): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  905): acquireWL(43f431b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3316 1000 null
D/PMS     (  905): releaseWL(43f431b0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 1108): 1104405464: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1108): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothMasReceiver( 3926): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3990): Received state change = 10
,D/BluetoothAdapter( 3840): 1101730864: getState() :  mService = null. Returning STATE_OFF,
,D/Process (  905): killProcessQuiet, pid=3826
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3826:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3826
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4617 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1247): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1247/10075)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1769/1000)
D/CaptivePortalTracker(  905): NoActiveNetworkState
,D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  905): acquireWL(426f8718): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1395/10028)
D/PMS     (  905): releaseWL(426f8718): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
,D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,I/MusicStore( 4617): Database version: 95
,W/ContextImpl( 4617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/Netd    (  365): No subsystem found in netlink event
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,V/Tethering(  905): remove iface:wlan0
D/Tethering(  905): interfaceRemoved wlan0
,E/Tethering(  905): attempting to remove unknown iface (wlan0), ignoring
,D/Tethering(  905): interfaceLinkStateChanged p2p0, false
,D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
,W/Netd    (  365): No subsystem found in netlink event
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,V/Tethering(  905): remove iface:p2p0
D/Tethering(  905): interfaceRemoved p2p0
,E/Tethering(  905): attempting to remove unknown iface (p2p0), ignoring
,W/ContextImpl( 4617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4617, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 4617): Registered
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,I/MediaRouter( 4617): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (4617/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2211/10021)
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4637 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4617): getSelectedRoute
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (4617/10154)
,I/NetworkMonitor( 4617): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4617, uid=10154, userID:0
,D/Process (  905): killProcessQuiet, pid=4320
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4320:com.htc.task/u0a70 (adj 15): empty #17
,D/ACRA    ( 4637): ACRA is enabled for com.facebook.katana, intializing...
I/ActivityManager(  905): Recipient 4320
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4637): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4637): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4637): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4637): Preparing secondary program dexes.
V/DexLibLoader( 4637): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4637): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4637): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4637): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4637): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4637): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4637): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4637): Dex already copied
D/OdexVerifier( 4637): Odex verification is skipped.
,V/DexLibLoader( 4637): Creating class loader
V/DexLibLoader( 4637): Finished creating class loader
V/DexLibLoader( 4637): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4637): Dex already copied
D/OdexVerifier( 4637): Odex verification is skipped.
,V/DexLibLoader( 4637): Creating class loader
V/DexLibLoader( 4637): Finished creating class loader
V/DexLibLoader( 4637): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4637): Dex already copied
D/OdexVerifier( 4637): Odex verification is skipped.
,V/DexLibLoader( 4637): Creating class loader
,V/DexLibLoader( 4637): Finished creating class loader
V/DexLibLoader( 4637): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4637): Dex already copied
D/OdexVerifier( 4637): Odex verification is skipped.
,V/DexLibLoader( 4637): Creating class loader,
V/DexLibLoader( 4637): Finished creating class loader
,V/DexLibLoader( 4637): Verifying classes from secondary dexes.
,D/DexLibLoader( 4637): DexLibLoader.ensureDexLoaded took 29 ms
,D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-1s591ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  905): releaseWL(439dc618): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/PMS     (  905): acquireWL(43e67918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=385939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e67918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/dalvikvm( 4637): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4637): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4637): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4637): Verify
,D/WifiService(  905): New client listening to asynchronous messages
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4637): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4637): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/PMS     (  905): acquireWL(43e4ab80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1199 10028 null
,D/PMS     (  905): acquireWL(43e11fa0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(43e4ab80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/GCM     ( 1341): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1341/10028)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): releaseWL(43e11fa0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/Process (  905): killProcessQuiet, pid=4456
,I/ActivityManager(  905): Killing 4456:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 4456
,D/AutoSetting( 4213): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4660 uid=10078 gids={50078, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4637): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/AutoSetting( 4213): Util - no network available!
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4637): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutoSetting( 4213): service - onCreate()
,D/AutoSetting( 4213): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4213/10053)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (4213/10053)
W/fb4a(:<default>):UserScope( 4637): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/AutoSetting( 4213): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  905): request 42402748 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4213): service - mHandler: cancel location update
D/AutoSetting( 4213): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4660): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4660): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4660): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4660): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4675 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4660/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4660/10078)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (4660/10078)
,E/dalvikvm( 4637): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4637): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4637): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4637): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4637): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4637): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4637): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4637): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4637): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4637): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4637): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4637): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4637): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4637): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4637): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4637): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4637): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4637): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,D/Process (  905): killProcessQuiet, pid=4471
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4689 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 4471:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4471
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 9.998MB for 79892-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4689): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 10.060MB for 84664-byte allocation
,W/ContextImpl( 4689): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 10.087MB for 28144-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,V/WebViewChromiumFactoryProvider( 4689): Binding Chromium to main looper Looper (main, tid 1) {41a90d18}
,I/LibraryLoader( 4689): Expected native library version number "",actual native library version number ""
I/chromium( 4689): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4689): Initializing chromium process, renderers=0
,D/PMS     (  905): acquireWL(424dae00): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4689): BLUETOOTH permission is missing!
D/PMS     (  905): acquireWL(41eab908): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(41eab908): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4689): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4689): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4689): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4689): Local Branch: 
I/Adreno-EGL( 4689): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4689): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4689):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4637): Grow heap (frag case) to 10.274MB for 75760-byte allocation
,I/NSApplication( 4689): Starting up...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42401280 u0 ReceiverList{4249a970 4637 com.facebook.katana/10026/u0 remote:426d98e0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42401280 u0 ReceiverList{4249a970 4637 com.facebook.katana/10026/u0 remote:426d98e0}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42502468 u0 ReceiverList{4255d3a8 4637 com.facebook.katana/10026/u0 remote:42d72aa8}}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (4689/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,I/dalvikvm-heap( 3661): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
,D/Process (  905): killProcessQuiet, pid=4402
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3661/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3661/10160)
,I/ActivityManager(  905): Killing 4402:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1751/10178)
,I/dalvikvm-heap( 3661): Grow heap (frag case) to 16.946MB for 1821008-byte allocation
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  905): Recipient 4402
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  905): acquireWL(424c4628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,D/PMS     (  905): releaseWL(424c4628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1395): Unknown pending intent to remove.
D/PMS     (  905): acquireWL(4273c248): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
D/PMS     (  905): releaseWL(4273c248): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4637): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4637): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4637): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/WifiP2pService(  905): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  905): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,D/PMS     (  905): acquireWL(42525370): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4617 10154 null
,D/PMS     (  905): releaseWL(424dae00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/ContextImpl( 4617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4617, uid=10154, userID:0
,I/MusicLeanback( 4617): Conditions not met for autocaching.
,I/MusicLeanback( 4617): Stop autocaching.
D/PMS     (  905): releaseWL(42525370): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,W/fb4a(:<default>):UserScope( 4637): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4637): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4637): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (4637/10026)
,I/GAV2    ( 4689): Thread[GAThread,5,main]: No campaign data found.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(42ce1650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,D/PMS     (  905): acquireWL(42116cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1395 10028 null
,D/PMS     (  905): releaseWL(42ce1650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  905): releaseWL(42116cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42ac9fc0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WirelessDisplayService(  905): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  905): HANDLE_STOP_DIS
,D/WirelessDisplayService(  905): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  905): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/AutoSetting( 4213): service - handleMessage() stop self
,D/AutoSetting( 4213): service - handleMessage() quit looper
,D/AutoSetting( 4213): service - onDestroy() END
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42cb7e40): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(42cb7e40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(4319e658): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(4319e658): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(433da1c8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(433da1c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  905): acquireWL(427bf440): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  905): releaseWL(427bf440): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 4515): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4515): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4515): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4515): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4515): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41e1e448 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 15 3 12
,D/libc    ( 4515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4515): [NET] getaddrinfo-,err=8
D/libc    ( 4515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4515): [NET] getaddrinfo-, 1
,D/libc    ( 4515): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =df15 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/libc    (  365): [NET]Querying server xid =df15 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  365): [NET]res_nsend:ECONNREFUSED
D/libc    (  365): [NET] -----res_nsend exit-1: xid=df15, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  365): [NET]res_queryN: exit 2
D/libc    (  365): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 4515): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4515): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  905): acquireWL(43033670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43033670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): releaseWL(428669d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  905): NetTransition Wakelock for ConnectedState released by timeout
,D/PMS     (  905): acquireWL(42cb9588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=445939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42cb9588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(424ecaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(424ecaf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  905): acquireWL(425101c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(425101c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42574c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=505940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42574c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(43376340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43376340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(43426e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=565939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43426e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42879318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42879318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1213): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1213): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1213): sku_id=99
D/ContactMessageStore( 1213): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1213): start background delete task...
D/ContactMessageStore( 1213): size: 0 , 0
,D/ContactMessageStore( 1213): Background delete complete
,D/PMS     (  905): acquireWL(42cedea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=625940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42cedea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(429432f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429432f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4399c790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=685939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4399c790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1341): GoogleAccountDataService.getToken()
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1341): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1341): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1341): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1341): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1341): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1341): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1341): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1341): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 4515): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4515): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4515): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4515): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4515): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4515): 	at dalvik.system.NativeStart.run(Native Method)
D/libc    ( 4515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4515): [NET] getaddrinfo-,err=8
D/libc    ( 4515): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4515): [NET] getaddrinfo-, 1
D/libc    ( 4515): [NET] getaddrinfo_proxy+
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41ee4f30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =163f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/libc    (  365): [NET]Querying server xid =163f (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  365): [NET]res_nsend:ECONNREFUSED
D/libc    (  365): [NET] -----res_nsend exit-1: xid=163f, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  365): [NET]res_queryN: exit 2
D/libc    (  365): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 4515): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 4515): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/RemoteViews.Performance( 1108): com.google.android.gms 1 12 5 12
,D/PMS     (  905): acquireWL(435bdc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(435bdc30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(434cb650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=745939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434cb650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(4343ec10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4343ec10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4343ea80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=805939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4343ea80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  905): acquireWL(434099c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(434099c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(433da3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=865939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(433da3e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(433c9d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(433c9d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(433a99e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=925939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(433a99e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(433a9118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(433a9118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PMS     (  905): runPSCheck
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4755 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,W/ContextImpl( 4755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3316): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3316): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3316): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3316): Cust_ConnectToPC   : spcsc>false
D/        ( 3316): Cust_ConnectToPC   : IPT>true
D/        ( 3316): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3316): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3316): Index of the first 1 = 3
W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3316): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3316): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3316): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3316): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,W/ContextImpl( 3316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3316): [ACC]android_networking:tethering_guard_support=false
,D/Process (  905): killProcessQuiet, pid=4332
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 4332:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4332
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42c846f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42c846f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
,D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42853e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=985940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42853e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(4262e7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41d9d4c8: PendingIntentRecord{423c3ce0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781493, Int=0
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4770 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4251e3b0: PendingIntentRecord{420394f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449748753233, Int=10800000
,V/AlarmManager(  905): sending alarm PendingIntent{4235fd70: PendingIntentRecord{42516368 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449748800196, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{41ec23b0: PendingIntentRecord{4241ee70 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449749473729, Int=900000
,V/AlarmManager(  905): sending alarm PendingIntent{4249f720: PendingIntentRecord{43180960 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449749546186, Int=0
,D/PMS     (  905): acquireWL(41f45db8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1199 10028 null
,D/PMS     (  905): acquireWL(41be2f00): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1199 10028 null
,I/EventLogService( 1199): Aggregate from 1449748644548 (log), 1449747000160 (data)
D/PMS     (  905): releaseWL(41f45db8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,W/ContextImpl( 4755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4755): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4755): MY_DEBUG = false
,D/SmartSyncUtils( 4755): isEpsOn(), nState = 0
D/PMS     (  905): acquireWL(422c3b90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4755 1000 null
,D/PMS     (  905): releaseWL(4262e7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4770/10047)
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): releaseWL(41be2f00): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  905): releaseWL(422c3b90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(42433f58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4755 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4755): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4755): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 21, nStart = 18, nEnd = 21, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4755): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4755): SettingOnTime = 1449777600000, randomSettingOnTime = 1449774912000
,D/SmartSyncScreenOnOffTimeReceiver( 4755): SettingOffTime = 1449766800000, randomSettingOffTime = 1449768922000
,D/SmartSyncScreenOnOffTimeReceiver( 4755): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4755): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4755): bNightModeTurnOffOnce = false
,D/PMS     (  905): releaseWL(42433f58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=4515
,I/ActivityManager(  905): Killing 4515:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4515
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42fc4300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42fc4300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1108): closing low battery warning: level=100
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43f6b0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43f6b0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(41e07bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1045940, Int=0
,D/PMS     (  905): releaseWL(41e07bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e1f8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e1f8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4341f360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4341f360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427598a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1105940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427598a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(439c6fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(439c6fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427fbc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427fbc88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1108): closing low battery warning: level=100
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
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
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(431bcda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1165939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(431bcda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42869c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42869c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42603b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42603b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(434331d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1225940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(434331d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(42591018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42591018): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(426535d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(426535d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4278ccd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1285939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4278ccd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42578b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42578b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/PowerUI ( 1108): closing low battery warning: level=100
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e89ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e89ae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e61060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1345939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(43e61060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(424b54e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,I/BatteryService(  905): n_update end
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(424b54e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(427ddae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427ddae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(433878c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1405939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(433878c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(43e33320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/PMS     (  905): releaseWL(43e33320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42604588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42604588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4261af88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1465939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4261af88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(42fd4818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): releaseWL(42fd4818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(423aa7c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  905): releaseWL(423aa7c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(425d6178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1525940, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(425d6178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427bf248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(427bf248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(43e3db18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(43e3db18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(436975f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1585939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(436975f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(428937e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(428937e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(44511010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): releaseWL(44511010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(439e0b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1645939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(439e0b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(439dddc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(439dddc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(433a5738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1705939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(433a5738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(433a4c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(433a4c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42d9f4e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): releaseWL(42d9f4e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42c9d388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1765939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42c9d388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(42c90700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42c90700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(42893130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42893130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(422f9ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1825939, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  905): Prepared write state in 50ms
,I/ProcessStatsService(  905): Prepared write state in 25ms
,D/PMS     (  905): releaseWL(422f9ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  905): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-26.bin
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  905): acquireWL(41dd9908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41d9d4c8: PendingIntentRecord{423c3ce0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1732148, Int=0
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{422138c0: PendingIntentRecord{42484df8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820754, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{42731208: PendingIntentRecord{4280bc20 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1852514, Int=0
,D/PMS     (  905): acquireWL(422e8448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
,V/AlarmManager(  905): sending alarm PendingIntent{41ec23b0: PendingIntentRecord{4241ee70 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449750373729, Int=900000
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,D/PMS     (  905): releaseWL(422e8448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(41dd9908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/PMS     (  905): acquireWL(4255b948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4255b948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42523a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  905): releaseWL(42523a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
D/HtcPowerSaver(  905): updateBatteryInfo
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,W/AppWidgetServiceImpl(  905): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4264c728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41af92e0: PendingIntentRecord{42320470 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1885940, Int=0
,D/PMS     (  905): releaseWL(4264c728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4820): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4820): ====startRecUseTime====
D/htc.customization.log.level( 4820):  is 
W/CustomizationLogLevel( 4820): Level value is invalid, use default level 2
D/CustomizationManager( 4820):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4820): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4820): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4820): Parsing tag category name = system
I/CustomizationCIDLoader( 4820): Parsing tag category name = application
I/CustomizationCIDLoader( 4820): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4820): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4820): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4820): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4820): Parsing tag category name = Settings
D/CustomizationManager( 4820):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4820):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 4820): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4820): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4820): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4820): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4820, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  905): killProcessQuiet, pid=3879
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 3879:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  905):   Force finishing activity ActivityRecord{41aa0710 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  905): Copying FileAsset 0x69efd7e0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  905): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1183): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3879 uid 10348
W/PackageSettings(  905): Skipping PackageSetting{421f5f48 com.example.hello/10355} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
W/InputDispatcher(  905): channel '423412f8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  905): channel '423412f8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '423412f8 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
I/WindowState(  905): WIN DEATH: Window{423412f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1769): Unregistering com.test.thalitest
E/acms    ( 1769): Could not unregister removed application com.test.thalitest
I/WindowManager(  905): WINDOW DIED Window{423412f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1395): Ignoring removeGeofence because network location is disabled.
D/PMS     (  905): acquireWL(428817e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1395 10028 null
D/PMS     (  905): releaseWL(428817e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Scheme: "smsto"
D/VoicemailCleanupService( 1263): Cleaning up data for package: com.test.thalitest
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/ExternalAccountType( 1311): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/ActivityManager(  905): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4837 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/SystemReader( 1223): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1213 :
D/PhoneApp( 1213): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4837): install
I/MultiDex( 4837): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4837): loading existing secondary dex files
I/MultiDex( 4837): load found 1 secondary dex files
I/MultiDex( 4837): install done
I/ActivityManager(  905): Delaying start of: ServiceRecord{439e5ea8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 1199): CP2 sync disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/Icing   ( 1199): doRemovePackageData com.test.thalitest
D/PMS     (  905): acquireWL(424bc4e8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  905): releaseWL(424bc4e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4837): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4855 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  905): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4855): install
I/MultiDex( 4855): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4855): loading existing secondary dex files
I/MultiDex( 4855): load found 1 secondary dex files
I/MultiDex( 4855): install done
I/ProviderInstaller( 4855): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  905): Resuming delayed broadcast
I/[PluginManager]RegisterService( 4213): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4213): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4872 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=4595
I/ActivityManager(  905): Killing 4595:com.htc.widget.process2/u0a48 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Recipient 4595
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4872, uid=10073, userID:0
D/Finsky  ( 4872): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4872/10073)
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (4872/10073)
E/SQLiteLog( 4837): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4837): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9d3138
D/Finsky  ( 4872): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
E/DriveAsyncService( 4837): disk I/O error (code 3850)
E/DriveAsyncService( 4837): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4837): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4837): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4837): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4837): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4837): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4837): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4837): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4837): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Settings( 4872): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/PackageManager(  905): Unable to load service info ResolveInfo{41fe5170 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/Settings( 4872): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4872): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4872): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4872): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4872): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4872): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4872): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4872): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4872): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4872): threadid=25: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  905): App crashed! Process: com.android.vending
E/AndroidRuntime( 4872): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4872): Process: com.android.vending, PID: 4872
E/AndroidRuntime( 4872): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4872): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4872): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4872): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4872): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4872): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4872): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4872): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4872): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4872): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4872, uid=10073, userID:0
D/Process (  905): killProcessQuiet, pid=4577
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4872): killProcess, pid=4872
D/Process ( 4872): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  905): Killing 4577:com.htc.widget.hmsproc3/u0a37 (adj 15): empty #17
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
I/IcingCorporaProvider( 2666): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4910 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 4837): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4837): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9d3138
E/DocListDatabase( 4837): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4837): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4837): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4837): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4837): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4837): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4837): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4837): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4837): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4837): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4837): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4837): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4837): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4837): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4837): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4837): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4837): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4837): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4837): threadid=1: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4837): FATAL EXCEPTION: main
E/AndroidRuntime( 4837): Process: com.google.android.gms.drive, PID: 4837
E/AndroidRuntime( 4837): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4837): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4837): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4837): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4837): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4837): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4837): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4837): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4837): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4837): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4837): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4837): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4837): 	... 10 more
D/Process ( 4837): killProcess, pid=4837
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4837): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteLog( 2666): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2666): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5ca31ab0
W/dalvikvm( 2666): threadid=14: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2666): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2666): Process: com.google.android.googlequicksearchbox:search, PID: 2666
E/AndroidRuntime( 2666): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2666): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2666): 	at cid.d(PG:186)
E/AndroidRuntime( 2666): 	at clo.g(PG:594)
E/AndroidRuntime( 2666): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2666): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2666): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2666): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2666): 	at clr.tL(PG:827)
E/AndroidRuntime( 2666): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2666): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2666): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2666): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2666): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2666): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2666): killProcess, pid=2666
D/Process ( 2666): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2666
D/MediaRouterService(  905): Client com.google.android.googlequicksearchbox (pid 2666): Died!
I/ActivityManager(  905): Process com.google.android.googlequicksearchbox:search (pid 2666) has died.
D/WifiService(  905): Client connection lost with reason: 4
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  905): Recipient 4577
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 4872
I/ActivityManager(  905): Process com.android.vending (pid 4872) has died.
I/ActivityManager(  905): Recipient 4837
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.gms.drive (pid 4837) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 10885ms
E/SQLiteDatabase( 4910): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4910): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4910): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4910): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4910): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4910): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4910): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4910): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4910): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4910): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4910): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4910): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4910): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4910): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4910): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4910): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4910): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4910): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4910): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4910): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4910): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4910): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4910): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4910): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4910): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4910): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4910): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4910): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4910): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4910): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4910): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4910): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4910): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4910): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4910): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4910): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4910): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4910): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4910): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4910): threadid=11: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4910): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4910): Process: com.google.android.apps.docs, PID: 4910
E/AndroidRuntime( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4910): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4910): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4910): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4910): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4910): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4910): killProcess, pid=4910
D/Process ( 4910): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4927 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4910
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4910) has died.
W/ContextImpl( 4927): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4940 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4927): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4927): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4927): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4927): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4927): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4927): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4927): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4927): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4927): threadid=10: thread exiting with uncaught exception (group=0x41660e30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4927): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4927): Process: com.android.keychain, PID: 4927
E/AndroidRuntime( 4927): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4927): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4927): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4927): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4927): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4927): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4927): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449750446779.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4927): killProcess, pid=4927
D/Process ( 4927): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Recipient 4927
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4927) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20629ms
D/AppTag  ( 4940): getInstance(Context context)
D/AppTag  ( 4940): getInstance(Context context)
D/AppTag  ( 4940): onCreate()
D/PMS     (  905): acquireWL(42c94918): PARTIAL_WAKE_LOCK  AsyncService 0x1 3661 10160 null
D/PMS     (  905): releaseWL(42c94918): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  905): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4958 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4958): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4958 dbg=false s=true
I/DeviceManagement( 4958): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4958): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4958): WorkflowService: Starting workflow service
I/DeviceManagement( 4958): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41abdd60] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4958): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4958): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4958): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4958): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  905): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4972 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4958): BackgroundController: *** Processing package remove for appID=com.test.thalitest

```
