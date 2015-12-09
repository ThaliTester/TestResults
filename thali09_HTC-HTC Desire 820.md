#### Test 506502789252e15_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  914): setLight #0: color=#26
,V/LightsService(  914): setLight #0: color=#22
V/LightsService(  914): setLight #0: color=#1c
V/LightsService(  914): setLight #0: color=#15
V/LightsService(  914): setLight #0: color=#14
--------- beginning of /dev/log/main
I/SensorManager(  914): mEventCount = 900
E/cutils-trace( 3853): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3853): ====startRecUseTime====
D/htc.customization.log.level( 3853):  is 
W/CustomizationLogLevel( 3853): Level value is invalid, use default level 2
D/CustomizationManager( 3853):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3853): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3853): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3853): Parsing tag category name = system
I/CustomizationCIDLoader( 3853): Parsing tag category name = application
I/CustomizationCIDLoader( 3853): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3853): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3853): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3853): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3853): Parsing tag category name = Settings
D/CustomizationManager( 3853):  Read CID file spent 0.098 (s)
D/CustomizationManager( 3853):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 3853): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3853): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3853): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3853): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  914): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  914): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  914): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  914): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  914): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  914): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  914): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3853
D/PMS     (  914): acquireHCC(437d6738): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 914 1000 null
D/PMS     (  914): acquireHCC(425a30c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 914 1000 null
W/asset   (  914): Copying FileAsset 0x7072cff8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  914): @test_code: getHtcIntentFlag: 0 obj: 1112892824
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c0f840
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  914): acquireWL(4259d620): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 914 1000 null
I/ActivityManager(  914): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3864 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 3864): Copying FileAsset 0x5c8a9428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1251): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3864): Binding Chromium to main looper Looper (main, tid 1) {41b4d228}
I/LibraryLoader( 3864): Expected native library version number "",actual native library version number ""
I/chromium( 3864): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3864): Initializing chromium process, renderers=0
W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441fbaa8:true
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3864): 1102475112: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  914): acquireWL(440dd200): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  914): acquireWL(440f6fe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  914): releaseWL(440dd200): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3864): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3864): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3864): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3864): Local Branch: 
I/Adreno-EGL( 3864): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3864): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3864):                  aa63bbd948f41d15fc72f585e
,W/chromium( 3864): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 3864): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 3864): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3864): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3864): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
,W/dalvikvm( 3864): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 3864): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 3864): CordovaWebView is running on device made by: HTC
,W/AwContents( 3864): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  914): Disable input method client, pid=1251
,I/InputMethodManagerService(  914): Enable input method client, pid=3864
W/ResourceType( 3864): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3864): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b98530, mServedView=org.apache.cordova.engine.SystemWebView{41b5e280 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  914): Displayed com.test.thalitest/.MainActivity: +400ms
,W/AwContents( 3864): nativeOnDraw failed; clearing to background color.
D/PMS     (  914): releaseWL(4259d620): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 3864): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3864): JniHelper::setJavaVM(0x41629048), pthread_self() = 1662885696
D/JX-Cordova( 3864): jxcore cordova android initializing
W/dalvikvm( 3864): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.513MB for 63974-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.570MB for 95956-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.652MB for 143930-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.771MB for 215890-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 11.944MB for 323830-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 12.612MB for 728606-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 13.207MB for 1092904-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 14.102MB for 1639352-byte allocation
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 15.476MB for 2459024-byte allocation
,W/CpuWake (  914): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  914): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  914): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  914): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  914): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  914): <<release mCpuPerf_Freq wakelock
D/PMS     (  914): releaseHCC(437d6738): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  914): releaseHCC(425a30c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 3864): Grow heap (frag case) to 17.543MB for 3688532-byte allocation
,W/jxcore-log( 3864): Initializing JXcore engine
,W/jxcore-log( 3864): JXcore engine is ready
,W/jxcore-log( 3864): Starting JXcore engine
,W/jxcore-log( 3864): Platform android
W/jxcore-log( 3864): 
,W/jxcore-log( 3864): Process ARCH arm
W/jxcore-log( 3864): 
,D/PMS     (  914): releaseWL(440f6fe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 3864): JXcore Cordova bridge is ready!
I/jxcore-log( 3864): 
,W/jxcore-log( 3864): JXcore engine is started
,I/chromium( 3864): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3864): Toggling radios to true
I/jxcore-log( 3864): 
,D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  914): checking for enable restriction...
,D/BluetoothManagerService(  914): checkBTEasState, ret=true
,I/BluetoothManagerService(  914): isBluetoothRestricted(): false
D/BluetoothManagerService(  914): enable(): region ID = 6
,D/BluetoothManagerService(  914): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  914): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  914): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  914): Settings:Agentvalue: 1
,W/Settings:Agent(  914): >> traceCallingStack()
W/Settings:Agent(  914): Process.myPid(): 914
,W/Settings:Agent(  914): Process.myTid(): 1980
W/Settings:Agent(  914): Process.myUid(): 1000
,W/Settings:Agent(  914): 
W/Settings:Agent(  914): 
,W/System.err(  914): java.lang.Throwable: stack dump
,W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  914): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  914): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  914): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  914): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  914): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  914): 
,W/Settings:Agent(  914): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  914): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  914): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3864): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  914): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  914): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  914): Settings:Agentvalue: 2
W/Settings:Agent(  914): >> traceCallingStack()
W/Settings:Agent(  914): Process.myPid(): 914
W/Settings:Agent(  914): Process.myTid(): 1337
W/Settings:Agent(  914): Process.myUid(): 1000
W/Settings:Agent(  914): 
W/Settings:Agent(  914): 
W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  914): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  914): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  914): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  914): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
D/WifiService(  914): New client listening to asynchronous messages
D/WifiService(  914): setWifiEnabled: true pid=3864, uid=10389
E/WifiService(  914): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  914): isSprintWifiRestricted(): false
I/WifiService(  914): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  914): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  914): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  914): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  914): 
W/Settings:Agent(  914): << traceCallingStack(): 1(ms)
,I/ActivityManager(  914): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3913 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3864): disconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiManager( 3864): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/jxcore-log( 3864): Radios toggled
I/jxcore-log( 3864): 
D/PMS     (  914): acquireWL(42c2ed28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 914 1000 null
,D/AdapterServiceConfig( 3913): Adding HeadsetService
D/AdapterServiceConfig( 3913): Adding A2dpService
D/AdapterServiceConfig( 3913): Adding HidService
D/AdapterServiceConfig( 3913): Adding HealthService
D/AdapterServiceConfig( 3913): Adding PanService
,D/AdapterServiceConfig( 3913): Adding GattService
,W/linker  ( 3913): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3913): REFCOUNT: CREATED. INSTANCE_COUNT1
,W/System.err(  914): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42589240:true
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3913): make
,I/BluetoothAdapterState( 3913): Entering OffState
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3913): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  914): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  914): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  914): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapter( 1110): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f2a918
,D/BluetoothAdapter( 1110): onBluetoothServiceUp done
,D/BluetoothAdapter( 1223): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41bc3918
D/BluetoothAdapter( 1223): onBluetoothServiceUp done
,D/BluetoothAdapter(  914): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42585a88
D/BluetoothAdapter(  914): onBluetoothServiceUp done
D/BluetoothAdapter( 3913): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b69e48
,D/BluetoothAdapter( 3913): onBluetoothServiceUp done
,D/BluetoothAdapter( 1236): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c840e8
,D/BluetoothAdapter( 1236): onBluetoothServiceUp done
,D/BluetoothAdapter( 1201): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41ec6320
,D/BluetoothAdapter( 1201): onBluetoothServiceUp done
,D/BluetoothAdapter( 3864): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@42693028
D/BluetoothAdapter( 3864): onBluetoothServiceUp done
,D/BluetoothManagerService(  914): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3913): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3913): Setting state to 11
I/BluetoothAdapterState( 3913): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3913): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  914): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  914): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3913): make
,I/BluetoothBondStateMachine( 3913): StableState(): Entering Off State
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/HeadsetService( 3913): Received start request. Starting profile...
D/HeadsetStateMachine( 3913): Version 1.6
,D/HeadsetStateMachine( 3913): make
D/PMS     (  914): acquireWL(42658340): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
D/PMS     (  914): releaseWL(42658340): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  914): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3939 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 3913): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3913): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3913): Received start request. Starting profile...
V/Avrcp   ( 3913): make
,D/Avrcp   ( 3913): fillIntentFilter()
,D/A2dpStateMachine( 3913): make
,D/HtcBtWidget_BTWidgetProvider( 3939): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3939): updateWidget(context) for widget: 
,D/A2dpStateMachine( 3913): Enter Disconnected: -2
,I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/HidService( 3913): Received start request. Starting profile...
D/Process (  914): killProcessQuiet, pid=3320
,D/HealthService( 3913): Received start request. Starting profile...
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PanService( 3913): Received start request. Starting profile...
D/BluetoothTethering(  914): supplyMessenger
,D/BluetoothTethering(  914): supplyMessenger mAsyncChannel is null
D/BluetoothTethering(  914): got MESSAGE_CONNECT_PANSERVICE, call connect
D/PanService( 3913): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  914): got CMD_CHANNEL_HALF_CONNECTED
,I/ActivityManager(  914): Killing 3320:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/BtGatt.DebugUtils( 3913): handleDebugAction() action=null
D/BtGatt.GattService( 3913): Received start request. Starting profile...
D/BtGatt.GattService( 3913): start()
V/BluetoothPbapService( 3913): Pbap Service onCreate
V/BluetoothPbapService( 3913): Starting PBAP service
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 11
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 11
E/BluetoothMasService( 3913): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3913): Add permission for SmsProvider.
V/BluetoothMasService( 3913): Starting MAS instances
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 11
I/MailMessageReceiver( 3913): reg:com.android.bluetooth.btservice.AdapterApp@41b5d3b0 with com.htc.util.mail.MailMessageReceiver@41b9d6f8
I/MailManager( 3913): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41b9d6f8
V/EmailUtils( 3913): Manager Instance is not NULL
,I/ActivityManager(  914): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3957 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/Tethering(  914): interfaceAdded wlan0
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/Tethering(  914): wlan0 is not a tetherable iface, ignoring
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/Tethering(  914): interfaceAdded p2p0
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/Tethering(  914): p2p0 is not a tetherable iface, ignoring
D/Tethering(  914): interfaceLinkStateChanged p2p0, false
D/Tethering(  914): interfaceStatusChanged p2p0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/libc    (  914): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/PMS     (  914): releaseWL(42c2ed28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/EmailUtils( 3913): ============NULL aList========
,V/EmailUtils( 3913): <-getEmailAccountIdList
V/BluetoothMasService( 3913): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 11
V/BluetoothMasService( 3913): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3913): Manager Instance is not NULL
D/EmailUtils( 3913): ============NULL aList========
,V/EmailUtils( 3913): <-getEmailAccountIdList
V/BluetoothSapService( 3913): Sap Service onCreate
,V/BluetoothSapService( 3913): initBinder
V/BluetoothSapService( 3913): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41ba2ae8
,V/BluetoothSapReceiver( 3913): BluetoothSapReceiver init
D/BluetoothSapService( 3913): setSapService()
V/BluetoothSapService( 3913): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3913): state: 12
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 11
D/BluetoothAdapterService( 3913): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3913): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3913): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3913): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3913): Profile still not running:com.android.bluetooth.pan.PanService
D/PanService( 3913): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothTethering(  914): got CMD_CHANNEL_FULLY_CONNECTED
,D/BluetoothAdapterService( 3913): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3913): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/Process (  914): killProcessQuiet, pid=3583
I/ActivityManager(  914): Recipient 3320
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Killing 3583:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 11
I/qcom-bluetooth( 3975): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  914): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=3979 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,I/qcom-bluetooth( 3993): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 3994): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 3996): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3997): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3979): Received state change = 11
,I/qcom-bluetooth( 3998): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3999): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/WifiService(  914): New client listening to asynchronous messages
,D/Process (  914): killProcessQuiet, pid=3686
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  914): Killing 3686:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1357): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  914): Recipient 3686
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 4004): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 4004): Add randomness: count=1 entropy=0
D/wpa_supplicant( 4004): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4004): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4004): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4004): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4004): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4004): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4004): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4004): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 4004): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4004): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4004): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4004): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4004): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4004): update_config=1
D/wpa_supplicant( 4004): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4004): device_name='Android_1950'
D/wpa_supplicant( 4004): manufacturer='HTC'
D/wpa_supplicant( 4004): model_name='HTC_PHONE'
D/wpa_supplicant( 4004): model_number='1234'
D/wpa_supplicant( 4004): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4004): p2p_oper_reg_class=126
D/wpa_supplicant( 4004): p2p_oper_channel=36
D/wpa_supplicant( 4004): p2p_ssid_postfix='-Android_1950'
,D/wpa_supplicant( 4004): persistent_reconnect=1
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 3
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 4004): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4004): nl80211: RFKILL status not available
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4004): nl80211: Using driver-based roaming
D/wpa_supplicant( 4004): nl80211: TDLS supported
D/wpa_supplicant( 4004): nl80211: TDLS external setup
,D/wpa_supplicant( 4004): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4004): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4004): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4004): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4004): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4004): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4004): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84a9758
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84a9758
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 4004): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4004): htc_wext_command_init +
E/wpa_supplicant( 4004): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 4004): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4004): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4004): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4004): nl80211: 2457-2482 @ 40 MHz
,D/wpa_supplicant( 4004): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4004): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4004): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  914): interfaceLinkStateChanged p2p0, false
D/Tethering(  914): interfaceStatusChanged p2p0, false
D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/Tethering(  914): interfaceLinkStateChanged p2p0, false
D/Tethering(  914): interfaceStatusChanged p2p0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Recipient 3583
,D/WifiMonitor(  914): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  914): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  914): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4005 uid=10050 gids={50050}
,D/HtcWiFiWidget_WiFiWidgetProvider( 4005): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4005): updateWidget(context) for widget: 
,D/Process (  914): killProcessQuiet, pid=1301
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  914): Killing 1301:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4018): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/wpa_supplicant( 4004): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 4004):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 4004):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4004):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): nl80211: Flush PMKIDs
E/wpa_supplicant( 4004): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 4004): State: DISCONNECTED -> INACTIVE
I/ActivityManager(  914): Recipient 1301
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/bt-btu  ( 3913): btu_task pending for preload complete event
,D/wpa_supplicant( 4004): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4004): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4004): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4004): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4004): Using existing control interface directory.
D/wpa_supplicant( 4004): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 4004): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 4004): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
D/wpa_supplicant( 4004): P2P: Own listen channel: 6
D/wpa_supplicant( 4004): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 4004): P2P: Add operating class 81
I/wpa_supplicant( 4004): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4004): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 4004): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4004): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4004): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4004): disable_scan_offload=1
D/wpa_supplicant( 4004): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 4004): update_config=1
D/wpa_supplicant( 4004): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 4004): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4004): manufacturer='HTC'
D/wpa_supplicant( 4004): model_name='HTC Desire 820'
D/wpa_supplicant( 4004): model_number='HTC Desire 820'
D/wpa_supplicant( 4004): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 4004): persistent_reconnect=1
D/wpa_supplicant( 4004): p2p_disabled=1
D/wpa_supplicant( 4004): hs20=1
D/wpa_supplicant( 4004): interworking=1
D/wpa_supplicant( 4004): Line: 18 - start of a new network block
D/wpa_supplicant( 4004): key_mgmt: 0x2
D/wpa_supplicant( 4004): priority=1 (0x1)
,D/wpa_supplicant( 4004): signinfail=0 (0x0)
,D/wpa_supplicant( 4004): Priority group 1
D/wpa_supplicant( 4004):    id=0 ssid='NG700'
I/wpa_supplicant( 4004): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4004): nl80211: RFKILL status not available
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 4004): nl80211: Using driver-based roaming
D/wpa_supplicant( 4004): nl80211: TDLS supported
D/wpa_supplicant( 4004): nl80211: TDLS external setup
D/wpa_supplicant( 4004): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 4004): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4004): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4004): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4004): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4004): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4004): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84b9718
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 4004): htc_wext_command_init +
I/wpa_supplicant( 4004): htc_wext_command_init -
I/wpa_supplicant( 4004): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 4004): Don't set 00 to countryID.conf
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 4004): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 4004): nl80211: Use separate P2P group interface
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4004): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4004): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 4004): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4004): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4004): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 4004): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 4004):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 4004):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 4004):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): nl80211: Flush PMKIDs
,E/wpa_supplicant( 4004): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 4004): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4004): TDLS: Driver uses external link setup
,D/wpa_supplicant( 4004): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4004): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 4004): Using existing control interface directory.
I/wpa_supplicant( 4004): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4004): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 4004): Auto country group 1: ch36
I/wpa_supplicant( 4004): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4004): random: Got 17/20 bytes from /dev/random
I/wpa_supplicant( 4004): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_914-2
D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4004): nl80211: Event message available
D/wpa_supplicant( 4004): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 4004): nl80211: Regulatory domain change
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4004): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4004): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4004): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 4004): P2P: Add operating class 81
D/wpa_supplicant( 4004): P2P: Add operating class 115
D/wpa_supplicant( 4004): P2P: Add operating class 116
D/wpa_supplicant( 4004): P2P: Add operating class 117
D/wpa_supplicant( 4004): P2P: Update channel list
D/wpa_supplicant( 4004): p2p0: Updating hw mode
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 95
D/WifiNative-wlan0(  914): doBoolean: SET_WIFI_ON 1
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 4004): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 4004): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 4004): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 4004): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 4004): nl80211: Added 802.11b mode based on 802.11g information
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
V/RegulatoryObserver(  914): uevent:
V/RegulatoryObserver(  914): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4421, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  914): Regulatory Country Code:DE
D/wpa_supplicant( 4004): random: Got 3/3 bytes from /dev/random
D/wpa_supplicant( 4004): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4004): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/wpa_supplicant( 4004): wpa_supplicant_scan enter
I/wpa_supplicant( 4004): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 4004): ap_scan=1 , scan_req =1
,I/wpa_supplicant( 4004): wpa_supplicant_trigger_scan +
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 4004): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): set wifi ON
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/wpa_supplicant( 4004): nl80211: Event message available
,D/wpa_supplicant( 4004): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doString: DRIVER MACADDR
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
V/RegulatoryObserver(  914): Start wifi-crda service to run crda.
V/RegulatoryObserver(  914): Country Code is DE
V/RegulatoryObserver(  914): Send broadcast country code message.
I/RegulatoryObserver(  914): Broadcast intent for crda country code: DE
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
D/WifiConfigStore(  914): Loading config and enabling all networks
D/WifiNative-wlan0(  914): doString: LIST_NETWORKS
I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): list_network_info: ret=0x1, pos=0xb84bd2ef buf=0xb84bd2c0
D/WirelessDisplayService(  914): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,I/wpa_supplicant( 4004): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4004): 0	NG700	any	
D/WifiNative-wlan0(  914):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  914): 0	NG700	any	
,D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 ssid
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/HtcWiFiWidget_WiFiWidgetProvider( 4005): onWiFiStateChanged() for widget: 
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 bssid
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/HtcWiFiWidget_WiFiWidgetProvider( 4005): updateWidget(context) for widget: 
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 priority
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_suppli,cant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 psk
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4004): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 proto
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  914): Failed to look-up a string: W
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  914): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 group
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='group'
E/WifiConfigStore(  914): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  914): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  914): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  914): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  914): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  914): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 limited
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 eap
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 phase2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 identity
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 password
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 engine
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'engine_id'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 key_id
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  914): doString: GET_NETWORK 0 private_key
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4004): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  914): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  914): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 4004): device_name='a51ul_htc_europe'
D/wpa_supplicant( 4004): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET manufacturer HTC
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 4004): manufacturer='HTC'
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 4004): model_name='HTC Desire 820'
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 4004): model_number='HTC Desire 820'
D/WifiNative-wlan0(  914):    returned true
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 4004): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET auto_interworking 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 4004): auto_interworking=0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: RECONNECT
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doString: STATUS
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =SCANNING
D/WifiNative-wlan0(  914): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): SET_SCREEN_ON:On
I/wpa_supplicant( 4004): htc_wext_set_keepalive +
I/wpa_supplicant( 4004): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4004): getPrivFuncNum +	
I/wpa_supplicant( 4004): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SET ps 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4004): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  914):    returned true
W/Settings(  914): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  914): doBoolean: CTRL-DAT-AIR_MODE-0:1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE: field=AIR_MODE id=0
D/libc    (  914): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  914): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): SETBAND: 0
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 4004): P2P: Add operating class 81
D/wpa_supplicant( 4004): P2P: Add operating class 115
D/wpa_supplicant( 4004): P2P: Add operating class 116
D/wpa_supplicant( 4004): P2P: Add operating class 117
D/wpa_supplicant( 4004): P2P: Update channel list
I/wpa_supplicant( 4004): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
D/WifiMonitor(  914): startMonitoring(p2p0) with mConnected = true
I/wpa_supplicant( 4004): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 4004): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 4004): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 4004): p2p_oper_reg_class=126
D/wpa_supplicant( 4004): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4004): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 4004): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4004): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 4004): p2p_oper_channel=36
E/wpa_supplicant( 4004): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 4004): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4004): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4004): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 4004): P2P_OP_CH: save_config, class=126, ch=36
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: BSS_FLUSH 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: SCAN
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  914):    returned false
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  914): doBoolean: SET pno 0
D/WifiNative-p2p0(  914): doBoolean: SET persistent_reconnect 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 4004): wpa_supplicant_scan enter
D/WifiNative-wlan0(  914):    returned true
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4004): persistent_reconnect=1
I/wpa_supplicant( 4004): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doBoolean: SET device_name Android_1950
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 4004): device_name='Android_1950'
I/wpa_supplicant( 4004): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 4004): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 4004): P2P: New SSID postfix: -Android_1950
,I/wpa_supplicant( 4004): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  914):    returned true
D/WifiP2pService(  914): P2pEnablingState
D/WifiP2pService(  914): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2p socket connection successful
D/WifiP2pService(  914): P2pEnabledState
D/WifiP2pService(  914): sending p2p connection changed broadcast
D/WifiDisplayController(  914): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  914): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: true
D/WifiDisplayController(  914): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[, type_ext: WIFI_P2P], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiDisplayController(  914): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiStateMachine(  914): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiNative-p2p0(  914): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 4004): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  914):    returned true
I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
D/WifiNative-p2p0(  914): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4004): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 4004): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  914): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 4004): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 4004): Single channel concurrency preference: sta
I/wpa_supplicant( 4004): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doString: STATUS
W/WifiHW  (  914): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  914): doBoolean: P2P_FLUSH
W/WifiHW  (  914): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 4004): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 4004): P2P: Stopping find
D/wpa_supplicant( 4004): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 4004): P2P: State IDLE -> IDLE
I/wpa_supplicant( 4004): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  914): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 4004): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 4004): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doString: LIST_NETWORKS
W/WifiHW  (  914): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 4004): list_network_info: ret=0x22, pos=0xb84bd2e2 buf=0xb84bd2c0
I/wpa_supplicant( 4004): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 4004): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  914):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  914): doBoolean: AP_SCAN 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  914):    returned false
D/WifiNative-p2p0(  914): doBoolean: SET wifi_display 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 4004): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 4004): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 4004): WFD: Update WFD IE
I/wpa_supplicant( 4004): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4004): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  914):    returned true
D/WifiNative-p2p0(  914): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  914): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 4004): WFD: Set subelement 0
D/wpa_supplicant( 4004): WFD: Update WFD IE
I/wpa_supplicant( 4004): WFD: Update WFD IE - DONE
I/wpa_supplicant( 4004): Recv Cmd 2: WFD_SUBELEM_SET 0
D/WifiNative-p2p0(  914):    returned true
D/WifiP2pService(  914): Send p2p flush in initializeP2pSettings
D/WifiDisplayController(  914): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  914):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  914):  primary type: 10-0050F204-5
D/WifiDisplayController(  914):  secondary type: null
D/WifiDisplayController(  914):  wps: 0
D/WifiDisplayController(  914):  grpcapab: 0
D/WifiDisplayController(  914):  devcapab: 0
D/WifiDisplayController(  914):  status: 3
D/WifiDisplayController(  914):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  914):  WFD CtrlPort: 0
D/WifiDisplayController(  914):  WFD MaxThroughput: 0
D/WifiP2pService(  914): sending p2p persistent groups changed broadcast
D/WifiP2pService(  914): InactiveState
D/WifiP2pService(  914): InactiveState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  914):  WFD CtrlPort: 7236
D/WifiP2pService(  914):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  914):  WFD CtrlPort: 7236
D/WifiP2pService(  914):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  914): Successfully set WFD info.
I/WifiDisplayController(  914): updateScanState(): mScanRequested = false, mWfdEnabled = true, mDiscoverPeersInProgress = false
V/AudioService(  914): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  914):     Client/Owner: Client
V/AudioService(  914):     GroupId: 
V/AudioService(  914):     Passphrase: 
V/AudioService(  914):     SessionId: 0
V/AudioService(  914):     IP Address: }
D/HtcEffectManagerBase(  914): onEventChanged id=5 status=false
D/HtcEffectManager(  914): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  914): convertEffect before=902
D/HtcEffectManager(  914): convertEffect after=902
D/WifiDisplayController(  914): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_1950
D/WifiDisplayController(  914):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiDisplayController(  914):  primary type: 10-0050F204-5
D/WifiDisplayController(  914):  secondary type: null
D/WifiDisplayController(  914):  wps: 0
D/WifiDisplayController(  914):  grpcapab: 0
D/WifiDisplayController(  914):  devcapab: 0
D/WifiDisplayController(  914):  status: 3
D/WifiDisplayController(  914):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiDisplayController(  914):  WFD CtrlPort: 7236
D/WifiDisplayController(  914):  WFD MaxThroughput: 50
D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/Tethering(  914): interfaceLinkStateChanged p2p0, false
,D/Tethering(  914): interfaceStatusChanged p2p0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 4004): nl80211: Event message available
D/wpa_supplicant( 4004): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 4004): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4004): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 4004): nl80211: Survey data missing
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 4004): Sorted scan results
I/wpa_supplicant( 4004): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 4004): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 4004): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 4004): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 4004): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 4004): Add randomness: count=2 entropy=0
D/wpa_supplicant( 4004): Add randomness: count=3 entropy=1
D/wpa_supplicant( 4004): Add randomness: count=4 entropy=2
D/wpa_supplicant( 4004): Add randomness: count=5 entropy=3
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4004): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4004): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 4004): wpa_supplicant_pick_network+
I/wpa_supplicant( 4004): Selecting BSS from priority group 1
I/wpa_supplicant( 4004): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 4004): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 4004): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 4004): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 4004): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 4004):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 4004):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 4004): Start print parameters
I/wpa_supplicant( 4004): wpa_s->wpa_state is 3
I/wpa_supplicant( 4004): wpa_s->br_have_IP is 0
I/wpa_supplicant( 4004): isConcurrentMode() is 0
I/wpa_supplicant( 4004): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 4004): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 4004): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 4004): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 4004): wpa_s->reassociate is 0
I/wpa_supplicant( 4004): wpa_s->is_screen_on 1
I/wpa_supplicant( 4004): wpa_s->ifname wlan0
I/wpa_supplicant( 4004): End print parameters
I/wpa_supplicant( 4004): selected network = 2
D/wpa_supplicant( 4004): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84ba4e8  current_ssid=0x0
D/wpa_supplicant( 4004): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4004): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 4004): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 4004): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4004): check if in concurrent case
,I/wpa_supplicant( 4004): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4004): wpa_supplicant_associate, 1777
D/wpa_supplicant( 4004): wpa_supplicant_associate, 1780
D/wpa_supplicant( 4004): wpa_supplicant_associate, 1795
D/wpa_supplicant( 4004): RSN: PMKSA cache search - network_ctx=0xb84ba4e8 try_opportunistic=0
D/wpa_supplicant( 4004): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4004): RSN: No PMKSA cache entry found
I/wpa_supplicant( 4004): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4004): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4004): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4004): nl80211: Unsubscribe mgmt frames handle 0xb84b9718 (mode change)
D/wpa_supplicant( 4004): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84b9718
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718,
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Register frame type=0xd0 nl_handle=0xb84b9718
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 4004): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 4004):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4004):   * freq=2412
D/wpa_supplicant( 4004):   * Auth Type 0
D/wpa_supplicant( 4004):   * WPA Versions 0x2
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
D/WifiNative-wlan0(  914): doString: LIST_DONGLES
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 4004): nl80211: Connect request send successfully
D/wpa_supplicant( 4004): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  914): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 4004): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 4004): reply (489) for get BSS: id=0
I/wpa_supplicant( 4004): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 4004): freq=5220
I/wpa_supplicant( 4004): level=-50
I/wpa_supplicant( 4004): tsf=0000000105170908
I/wpa_supplicant( 4004): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4004): ssid=NG7005g
I/wpa_supplicant( 4004): ====
I/wpa_supplicant( 4004): id=1
I/wpa_supplicant( 4004): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 4004): freq=2412
I/wpa_supplicant( 4004): level=-53
I/wpa_supplicant( 4004): tsf=0000000105170919
I/wpa_supplicant( 4004): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 4004): ssid=01ABC
I/wpa_supplicant( 4004): ====
I/wpa_supplicant( 4004): id=2,
I/wpa_supplicant( 4004): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4004): freq=2412
I/wpa_supplicant( 4004): level=-54
I/wpa_supplicant( 4004): tsf=0000000105170922
I/wpa_supplicant( 4004): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 4004): ssid=NG700
I/wpa_supplicant( 4004): ====
I/wpa_supplicant( 4004): id=3
I/wpa_supplicant( 4004): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 4004): freq=2427
I/wpa_supplicant( 4004): level=-80
I/wpa_supplicant( 4004): tsf=0000000105170926
I/wpa_supplicant( 4004): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 4004): ssid=Gonzos
I/wpa_supplicant( 4004): ####
,D/WirelessDisplayService(  914): getDiscoveryDongleList
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/WifiStateMachine(  914): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 105170908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 105170919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 105170922, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2427, timestamp: 105170926, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  914): add 4 to mScanResults
D/WifiStateMachine(  914): == begin of scan result ==
,D/WifiStateMachine(  914): == (4) end of scan result ==
,D/WifiManager( 1201): getScanResults enter 
D/WirelessDisplayService(  914): getDiscoveryDongleList
D/WifiStateMachine(  914): == begin of scan result ==
,D/WifiStateMachine(  914): == (4) end of scan result ==
D/WifiNotificationController(  914): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4004): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4004): nl80211: Event message available
D/wpa_supplicant( 4004): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4004): nl80211: Connect event
D/wpa_supplicant( 4004): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4004): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 4004): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 4004): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4004): Add randomness: count=6 entropy=4
I/wpa_supplicant( 4004): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 4004): TDLS: Remove peers on association
D/wpa_supplicant( 4004): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 4004): htc_wext_set_keepalive +
I/wpa_supplicant( 4004): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 4004): getPrivFuncNum +	
I/wpa_supplicant( 4004): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4004): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4004): Get randomness: len=32 entropy=5
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  914): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  914): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/HTCRequest(  914): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  914): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  914): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/Tethering(  914): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  914): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  914): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  914): interfaceStatusChanged wlan0, true
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  914): Enter handleAssociatedWithEvent
D/WifiStateMachine(  914): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  914): Associated
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  914): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  914): Exit handleAssociatedWithEvent
,D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  914): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
,I/wpa_supplicant( 4004): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84b99f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4004):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=1
I/wpa_supplicant( 4004): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ecfb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4004):    broadcast key
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 4004): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 4004): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 4004): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4004): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 4004): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 4004): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 4004): set send_ind_to_ndc = 0
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4004): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4004): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4004): EAPOL authentication completed successfully
I/wpa_supplicant( 4004): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 4004): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4004): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4004): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  914): interfaceLinkStateChanged wlan0, true
,D/Tethering(  914): interfaceStatusChanged wlan0, true
D/Tethering(  914): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  914): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  914): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  914): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  914): This record is existed, only update it...
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
,D/WifiStateMachine(  914): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  914): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  914): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  914): This record is existed, only update it...
D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  914): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  914): Provision feature enable=false
D/ConnectivityService(  914): mActiveDefaultNetwork: -1
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  914): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  914): updateConnectedAP...
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3286): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3286): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  914): [StoppedState] Start DHCP
D/WifiService(  914): New client listening to asynchronous messages
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
D/WifiStateMachine(  914): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=100 [2][2][0]
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  914): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 4004): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): Power_Mode_Type mode = 1
I/wpa_supplicant( 4004): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  914):    returned null
E/WifiStateMachine(  914): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING STOP
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  914): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  914): acquireWL(43aecd18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 914 1000 null
D/WifiStateMachine(  914): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  914):    returned null
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiP2pService(  914): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4411fbe8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4411fbe8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:1
,I/bt-btu  ( 3913): btu_task received preload complete event
,D/bt-btm  ( 3913): btm_acl_device_down
D/bt-btm  ( 3913): btm_acl_reset_paging
,D/bt-btm  ( 3913): btm_acl_set_discing
,I/bt-btm  ( 3913): btm_reset_complete
,I/bt-btm  ( 3913): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3913): Start reading local supported commands
,D/bt-btm  ( 3913): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3913): BTM reads next extended features page (1)
,D/bt-btm  ( 3913): BTM reads next extended features page (2)
D/bt-btm  ( 3913): BTM reached last extended features page (2)
,D/bt-btm  ( 3913): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3913): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3913): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 3913): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3913): btm_read_ble_wl_size 
D/bt-btm  ( 3913): btm_read_white_list_size_complete 
,D/bt-btm  ( 3913): btm_get_ble_buffer_size 
D/bt-btm  ( 3913): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3913): btm_read_ble_local_supported_features 
D/bt-btm  ( 3913): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3913): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3913): btm_decode_ext_features_page page: 0
,D/bt-btm  ( 3913): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 3913): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3913): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3913): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,I/bt-btm  ( 3913):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3913): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3913): BTM_SetInquiryMode
,I/bt-btm  ( 3913): BTM_SetPageScanType
I/bt-btm  ( 3913): BTM_SetInquiryScanType
D/bt-btm  ( 3913): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3913): btm_decode_ext_features_page page: 2
,D/bt-btm  ( 3913): BTM_BleLoadLocalKeys
D/bt-btm  ( 3913): BTM_BleLoadLocalKeys
I/bt-btm  ( 3913): BTM_Sec: application registered
E/bt-btm  ( 3913): BTM_SecRegister:p_cb_info->p_le_callback == 0x62011941 
,I/bt-btm  ( 3913): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3913): SMP_Register state=0
E/bt-btm  ( 3913): BTM_SecRegister: btm_cb.api.p_le_callback = 0x62011941 
I/bt-btm  ( 3913): BTM_Sec: application registered
,D/bt-btm  ( 3913): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3913): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3913): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3913): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3913): Set DefaultLinkPolicy:0x0007
,D/bt-btm  ( 3913): BTM_RegBusyLevelNotif
I/bt-att  ( 3913): GATT_Register
D/bt-att  ( 3913): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 3913): allocated gatt_if=3
,I/bt-att  ( 3913): GATT_StartIf gatt_if=3
D/bt-att  ( 3913): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3913): gatt_find_the_connected_bda found=0 found_idx=7
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Calling BTA_HhEnable
E/bt-btif ( 3913): Calling BTA_HhEnable
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3913): BTM_AllocateSCN
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3913): BTM_AllocateSCN
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3913):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3913):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
E/bt-btif ( 3913): btif_storage_get_adapter_property service_mask:0x140040
I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3913): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3913): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3913): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
D/bt-avp  ( 3913): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3913): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[10]: id 34, is,_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3913):                : sec: 0x80, service name [] (up to 21 chars saved)
I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:2 len:6
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: b0:c5:59:3f:75:69
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: f4:f1:e1:5c:3b:e2
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3913): BTM_GetHCIConnHandle
I/bt-btm  ( 3913): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3913): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3913): GATT_Register
D/bt-att  ( 3913): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3913): allocated gatt_if=4
I/bt-att  ( 3913): GATT_StartIf gatt_if=4
D/bt-att  ( 3913): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 3913): gatt_find_the_connected_bda found=0 found_idx=7
D/BluetoothAdapterProperties( 3913): Address is:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:1 len:14
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3913): Scan Mode:20
I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3913): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:8 len:60
,D/BluetoothAdapter( 3913): getBluetoothService(): entry
D/BluetoothAdapter( 3913): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3913): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41bad9d8
,D/BluetoothDevice( 3913): getService : Register callback
,D/BluetoothAdapterProperties( 3913): Adding bonded device:B0:C5:59:3F:75:69
,D/BluetoothAdapterProperties( 3913): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3913): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 3913): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 3913): Adding bonded device:14:B4:84:21:3B:49
,D/BluetoothAdapterProperties( 3913): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3913): Adding bonded device:7C:F9:0E:34:8A:A0
,D/BluetoothAdapterProperties( 3913): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 3913): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3913): Adding bonded device:38:94:96:B5:06:DC
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
D/wpa_supplicant( 4004): EAPOL: disable timer tick
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
,I/bt-btif ( 3913): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3913): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 3913): Remote class is:5898764
I/bt-btif ( 3913): BTA_JvEnable
I/bt-btm  ( 3913): BTM_ReadConnectability
I/bt-btm  ( 3913): BTM_ReadDiscoverability
I/bt-btm  ( 3913): BTM_SetDiscoverability
I/bt-btm  ( 3913): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3913): br_edr_supported=0x2
I/bt-btm  ( 3913): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x0
I/bt-btm  ( 3913): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3913): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3913): BTM_SetConnectability
I/bt-btm  ( 3913): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3913): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3913): BTM_SetDiscoverability
I/bt-btm  ( 3913): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3913): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3913): br_edr_supported=0x0
I/bt-btm  ( 3913): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3913): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3913): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3913): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3913): BTM_SetConnectability
I/bt-btm  ( 3913): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3913): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3913): bta_pan_co_init
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:8
,I/bt-btm  ( 3913): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3913):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3913):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3913): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3913):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3913): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3913):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3913): Write Extended Inquiry Response to controller,
,E/bt_mct  ( 3913): hci lib postload completed
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:10
,I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3913): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3913): ScanMode =  20
D/BluetoothAdapterProperties( 3913): State =  11
I/bt-btm  ( 3913): BTM_SetDiscoverability
D/BluetoothAdapterProperties( 3913): Setting state to 12
I/bt-btm  ( 3913): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3913): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3913): br_edr_supported=0x0
I/bt-btm  ( 3913): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3913): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3913): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3913): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3913): BTM_SetConnectability
I/bt-btm  ( 3913): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3913): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3913): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3913): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:7 len:4
I/BluetoothAdapterState( 3913): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3913): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  914): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  914): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3913): Entering On State
D/BluetoothAdapterProperties( 3913): Scan Mode:21
I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3913): Discoverable Timeout:120
D/BluetoothAdapterService(1102475992)( 3913): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3913): getBondedDevices: length=10
,D/BluetoothHeadset( 1223): Proxy object connected
,D/BluetoothHeadset( 1110): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1110): Proxy object connected
,I/QuickSettingMiniLite( 1110): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e66620
,D/BluetoothHeadset(  914): onBluetoothStateChange: up=true
,D/BluetoothPan(  914): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset(  914): Proxy object connected
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
,D/BluetoothAdapter(  914): 1111790440: getState(). Returning 12
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothHeadset( 1223): Proxy object connected
D/BluetoothPhoneService( 1223): BluetoothHeadset onServiceConnected
D/BluetoothA2dp(  914): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1223): 1103653960: getState(). Returning 12
D/BluetoothAdapterService(1102475992)( 3913): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3913): getBondedDevices: length=10
,D/BluetoothManagerService(  914): Bluetooth State Change Intent: 11 -> 12
D/BluetoothPan(  914): BluetoothPAN Proxy object connected
,D/BluetoothA2dp(  914): Proxy object connected
,D/BluetoothAdapter(  914): 1111790440: getState(). Returning 12
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/PMS     (  914): acquireWL(423cccc0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
V/BluetoothPbapReceiver( 3913): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3913): ***********state = 12
D/BluetoothManagerService(  914): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 12
V/BluetoothSapReceiver( 3913): SapReceiver onReceive 
V/BluetoothSapReceiver( 3913): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3913):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 3913): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,D/HtcBtWidget_BTWidgetProvider( 3939): onBTStateChanged() for widget: 
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 12
,D/HtcBtWidget_BTWidgetProvider( 3939): updateWidget(context) for widget: 
D/PMS     (  914): releaseWL(423cccc0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  914): acquireWL(432bf6f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3286 1000 null
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  914): releaseWL(432bf6f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  914): acquireWL(4381fdc0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3286 1000 null
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 12
V/BluetoothMasService( 3913): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3913): Manager Instance is not NULL
W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4382de58:true
I/LocationAgent( 3286): new LocationAgent instance!!
D/EmailUtils( 3913): ============NULL aList========
V/EmailUtils( 3913): <-getEmailAccountIdList
V/BluetoothSapService( 3913): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3913): state: 12
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 12
D/HtcTagManager( 3286): HtcTagManager construction complete
W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3913): Starting SAP server process
V/BluetoothPbapService( 3913): Handler(): got msg=1
,V/BluetoothPbapService( 3913): Pbap Service startRfcommSocketListener
,D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
,V/BluetoothPbapService( 3913): Pbap Service initSocket
,D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3913): getBluetoothService(): entry
,W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 3286): BluetoothInputDevice()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
E/BluetoothServiceJni( 3913): SOCK FLAG = 1 ***********************
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 7
I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:11
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
,D/BluetoothInputDevice( 3286): BluetoothInputDevice(): Binding service...
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3913):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3913): Succeed to create listening socket 
,V/BluetoothPbapService( 3913): Accepting socket connection...
,D/BluetoothPan( 3286): BluetoothPan()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 8
,V/BluetoothMasService( 3913): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 3913): BluetoothMns: isEmailEnabled: true
,D/BluetoothMasService( 3913): Map_prev 1
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
,D/BluetoothPan( 3286): BluetoothPan(): Binding service...
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothAdapter( 1110): 1105207064: getState(). Returning 12
,D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 1110): 1105207064: getState(). Returning 12
I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/BluetoothMap( 3286): Create BluetoothMap proxy object
D/BluetoothManagerService(  914): registerStateChangeCallback+
,D/PhoneStatusBar( 1110): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 9
,E/BluetoothMap( 3286): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothAdapter( 3913): getBluetoothService(): entry
,W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  914): registerStateChangeCallback+
,D/BluetoothSap( 3286): BluetoothSap() call bindService
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothServiceJni( 3913): SOCK FLAG = 3 ***********************
D/BluetoothManagerService(  914): Registered receivers: 10
,I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
,I/bt-btm  ( 3913):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3913): getBluetoothService(): entry
W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPbap( 3286): BluetoothPbap()
E/BluetoothServiceJni( 3913): SOCK FLAG = 3 ***********************
I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 11
I/bt-btm  ( 3913):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
,D/BluetoothPbap( 3286): BluetoothPbap(): Binding service...
D/BluetoothSapService( 3913): Sap_prev 1
,D/BluetoothA2dp( 3286): BluetoothA2dp()
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
V/BluetoothSapService( 3913): SAP Service startRfcommListenerThread
D/BluetoothManagerService(  914): registerStateChangeCallback+
V/BluetoothSapService( 3913): Sap Service initRfcommSocket
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 12
D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
D/BluetoothA2dp( 3286): BluetoothA2dp(): Binding service...
D/BluetoothAdapter( 3913): getBluetoothService(): entry
W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3913): SOCK FLAG = 3 ***********************
I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3913):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3913): Succeed to create listening socket 
,V/BluetoothSapService( 3913): Accepting socket connection...,
D/BluetoothHeadset( 3286): BluetoothHeadset()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
,D/BluetoothHeadset( 3286): BluetoothHeadset(): Binding service...
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 13
,D/HtcTagManager( 3286): startProxy
,D/BluetoothAdapter( 1110): 1105207064: getState(). Returning 12
,W/ContextImpl( 3286): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,I/QuickSettingMiniLite( 1110): updateLiteState:no connect device!
,D/LocalBluetoothProfileManager( 3286): LocalBluetoothProfileManager construction complete
,W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
V/TAG     ( 3913): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3913): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ba4228
V/BluetoothPbapService( 3913): Pbap Service onBind
D/DockEventReceiver( 3286): finishStartingService: stopping service
D/BluetoothPan( 3286): BluetoothPAN Proxy object connected
D/PanProfile( 3286): Bluetooth service connected
D/BluetoothA2dp( 3286): Proxy object connected
D/A2dpProfile( 3286): Bluetooth service connected
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothHeadset( 3286): Proxy object connected
I/BluetoothFtpService( 3913): Ftp Service onCreate
D/HeadsetProfile( 3286): Bluetooth service connected
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 12
D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 12
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): onCreate: going to find gatt base service first.
D/BluetoothFtpService( 3913): Ftp_prev 1
D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3913): getBluetoothService(): entry
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 3913): getBluetoothService(): entry
W/BluetoothAdapter( 3913): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothInputDevice( 3286): Proxy object connected
E/BluetoothServiceJni( 3913): SOCK FLAG = 0 ***********************
I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/HidProfile( 3286): Bluetooth service connected
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3913):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 3913): Accept thread started.
E/BluetoothServiceJni( 3913): SOCK FLAG = 1 ***********************
I/bt-btif ( 3913): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3913): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btif ( 3913): BTA_JvRfcommStartServer
I/bt-btm  ( 3913): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3913):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapter( 3286): 1104082880: getState(). Returning 12
W/System.err(  914): java.lang.Throwable: stack dump
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b776e8:true
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
D/SapServerProfile( 3286): Bluetooth service connected
D/BluetoothPbap( 3286): Proxy object connected
D/PbapServerProfile( 3286): Bluetooth service connected
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 12
V/BluetoothMasService( 3913): parseIntent 1: mIsEmail,Enabled: true
,V/EmailUtils( 3913): Manager Instance is not NULL
,D/PMS     (  914): releaseWL(4381fdc0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
V/BluetoothFtpService:RfcommSocketAcceptThread( 3913): Run Accept thread
D/[HTC_BLE][Constants]( 3979):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3979):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3979):  + discoverServicesOnBonded = false
D/EmailUtils( 3913): ============NULL aList========
V/EmailUtils( 3913): <-getEmailAccountIdList
D/BluetoothMasService( 3913): Map_prev 1
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6d2d0
D/[HTC_BLE][Constants]( 3979): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 3979): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 3979): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 3979): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 3979): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 3979): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 3979): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3286): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3979): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6d2d0
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3979): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6d2d0
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3979): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6d2d0, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b78c88
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3979): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b6d2d0
D/HtcTagProfile( 3286): setup proxy
D/HtcPxpProfile( 3286): setup proxy
,D/HtcFmpProfile( 3286): setup proxy
,W/System.err(  914): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41b64408:true
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3806): new LocationAgent instance!!
,D/HtcTagManager( 3806): HtcTagManager construction complete
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothInputDevice( 3806): BluetoothInputDevice()
D/BluetoothManagerService(  914): registerStateChangeCallback+
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 14
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothInputDevice( 3806): BluetoothInputDevice(): Binding service...
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3806): BluetoothPan()
D/RingtoneManager( 3979): getExternalStorageState=mounted
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 15
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
D/BluetoothPan( 3806): BluetoothPan(): Binding service...
,D/BluetoothMap( 3806): Create BluetoothMap proxy object
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 16
,E/BluetoothMap( 3806): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3806): BluetoothSap() call bindService
,D/BluetoothManagerService(  914): Registered receivers: 17
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
,W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3806): BluetoothPbap()
D/wpa_supplicant( 4004): EAPOL: startWhen --> 0
D/wpa_supplicant( 4004): EAPOL: disable timer tick
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  914): Registered receivers: 18
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothPbap( 3806): BluetoothPbap(): Binding service...
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[0]: Crocus
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[3]: Foxglove
,D/BluetoothA2dp( 3806): BluetoothA2dp()
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[7]: Licorice
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[9]: Rose
,D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[12]: Tulip
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[13]: Wintergreen
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 3979):  + mAlertUri: content://settings/system/alarm_alert
,D/BluetoothManagerService(  914): Registered receivers: 19
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothA2dp( 3806): BluetoothA2dp(): Binding service...
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothHeadset( 3806): BluetoothHeadset()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 20
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothHeadset( 3806): BluetoothHeadset(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3979): BleProfilesStateMachine is initialized...
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3979): Enter IdleState
,D/HtcTagManager( 3806): startProxy
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): initScanModeInterface: true
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
W/ContextImpl( 3806): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/System.err(  914): java.lang.Throwable: stack dump
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4405b738:true
D/LocalBluetoothProfileManager( 3806): LocalBluetoothProfileManager construction complete
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979): loadDeviceConfiguration() init =true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979):  + mTag.getPrimaryDeviceList() = []
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
D/LocalBluetoothProfileManager( 3806): setBluetoothStateOn
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
D/[HTC_BLE][Constants]( 3979):  + defaultServices = 0
D/[HTC_BLE][Constants]( 3979):  + enableOnBonded = false
D/[HTC_BLE][Constants]( 3979):  + discoverServicesOnBonded = false
D/HtcTagManager( 3806): startProxy
D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
D/BluetoothAdapterService(1102475992)( 3913): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3913): getBondedDevices: length=10
D/BluetoothAdapter( 3806): getBluetoothService(): entry
D/BluetoothAdapter( 3806): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3806): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41ba7878
D/BluetoothDevice( 3806): getService : Register callback
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,E/BluetoothDevice( 3806): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): addHtcTagProfiles
,D/BluetoothInputDevice( 3806): Proxy object connected
,D/HidProfile( 3806): Bluetooth service connected
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/AuthorizationBluetoothService( 1357): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1357): Proximity feature is not enabled.
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b78c88
,D/BluetoothPan( 3806): BluetoothPAN Proxy object connected
D/PanProfile( 3806): Bluetooth service connected
D/SapServerProfile( 3806): Bluetooth service connected
D/BluetoothPbap( 3806): Proxy object connected
D/PbapServerProfile( 3806): Bluetooth service connected
,D/BluetoothA2dp( 3806): Proxy object connected
,D/A2dpProfile( 3806): Bluetooth service connected
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/BluetoothHeadset( 3806): Proxy object connected
,D/HeadsetProfile( 3806): Bluetooth service connected
,D/BluetoothAdapter( 3806): 1102504320: getState(). Returning 12
,D/HtcTagManager( 3806): onServiceConnected
D/HtcTagProfile( 3806): setup proxy
D/HtcPxpProfile( 3806): setup proxy
,D/HtcFmpProfile( 3806): setup proxy
,I/PMS     (  914): Going to sleep due to screen timeout...
,I/ActivityManager(  914): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  914): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421eb980
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  914): disable: get sensor name = CM36282 Light sensor
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 2
W/SensorService(  914): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421eb980, eanble = 0, strlen(mName) = 59
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  914): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f98ad0
W/SensorService(  914): Listener[1] = com.htc.smartdim.sensor_eye@41c5bea8
,W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  914): Couldn't get kernel wake lock stats
V/LightsService(  914): setLight #2: color=#0
D/qdlights(  914): set_light_buttons_func: on=0 brightness=0
V/LightsService(  914): setLight #0: color=#0
,D/WirelessDisplayService(  914): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  914): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  914): mWirelessDisplayManager is null
,D/SurfaceControl(  914): Excessive delay in blankDisplay() while turning screen off: 316ms
D/PMS     (  914): nativeSetInteractive:false
,V/KeyguardServiceDelegate(  914): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@441f3f38)
,V/KeyguardServiceDelegate(  914): **** SHOWN CALLED ****
D/PMS     (  914): nativeSetInteractive:false done
D/PMS     (  914): nativeSetAutoSuspend:true
D/PMS     (  914): nativeSetAutoSuspend:true done
D/HABCtrl (  914): TPE algorithm. remove timeout.
D/PMS     (  914): OOBE c monitor 11
I/InputManager(  914): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  914): screenObserver, isScreenOn=false
I/InputMethodManagerService(  914): Disable input method client, pid=3864
D/PMN     (  914): wakingUp
I/WindowManager(  914): No lock screen! windowToken=null
D/NfcService( 1236): applyRouting - 0
,D/NfcService( 1236): ScreenObserver: OFF
,I/IntentController( 1110): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  914): onScreenOn
D/PMS     (  914): acquireWL(425541c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/NfcService( 1236): applyRouting -2
D/WirelessDisplayService(  914): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  914): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  914): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/BatteryService(  914): n_update end
D/PMS     (  914): acquireWL(42cc4ba0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1236 1027 null
D/PMS     (  914): releaseWL(425541c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): releaseWL(42cc4ba0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  914): ACTION_SCREEN_ON
I/AlarmManager(  914): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  914): [AlarmQueuing] done recovering
I/AlarmManager(  914): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  914): [AlarmQueuing] done EPS screen off alarm recovering
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ActivityManager(  914): Disable JIT of com.htc.bgp
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
I/ActivityManager(  914): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4066 uid=10014 gids={50014, 3003, 5012, 1028, 1015, 5001, 5011, 3002, 3001, 5003, 2001}
,D/MtpService( 2151): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2151): [MTP][onReceive]-
,D/NfcService( 1236): applyRouting - 0
,D/WifiDataStallTracker(  914): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,D/NfcService( 1236): applyRouting -2
,I/ClockThread( 1110): stop update clock
D/WirelessDisplayService(  914): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  914): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  914): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
D/WifiNative-wlan0(  914): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): acquireWL(4201d2d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1236 1027 null
D/PMS     (  914): releaseWL(4201d2d8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): SET_SCREEN_ON:On
I/wpa_supplicant( 4004): htc_wext_set_keepalive +
I/wpa_supplicant( 4004): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 4004): getPrivFuncNum +	
I/wpa_supplicant( 4004): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  914):    returned true
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  914):    returned true
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NotificationService(  914): batLight: Full, plugged
V/LightsService(  914): setLight #8: color=#c8c800
D/qdlights(  914): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  914): setLight #8: color=#c800
D/qdlights(  914): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  914): [LedInfo] has indicator attribute
D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  914): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  369): ParamSet string: screen_state=on
D/WirelessDisplayService(  914): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  914): updateScreenOn: false
,I/CalendarProvider2( 4066): Created com.android.providers.calendar.CalendarAlarmManager@41b90bd8(com.android.providers.calendar.HtcCalendarProvider@41b78f60)
D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,D/CalendarProvider2( 4066): wait start:true
,D/CalendarProvider2( 4066): wait end:false
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  914): acquireWL(4267c488): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(4267c488): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4098 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  914): acquireWL(439a9a08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(439a9a08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): Power_Mode_Type mode = 0
,I/wpa_supplicant( 4004): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  914):    returned true
,D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  914): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  914): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  914):    returned true
,D/WifiStateMachine(  914): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(43aecd18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  914): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  914): doBoolean: SignalStrength 97
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4004): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): gateway: /192.168.1.1
D/WifiNative-wlan0(  914): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  914):    returned true
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  914): VerifyingLinkState enter
D/WifiStateMachine(  914): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  914): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  914): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1110): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): onScreenOn: 1449683628196
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3979): onScreenOn: 1449683628196
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  914): startDataStallAlarm: tag=20790 delay=15s
,V/NetworkPolicy(  914): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  914): WAN detection
,I/SensorManager(  914): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f98ad0
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  914): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  914): Provision feature enable=false
D/ConnectivityService(  914): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  914): pid=914, uid=1000,
W/SensorService(  914): Active sensors: size = 2
W/SensorService(  914): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
,W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f98ad0, eanble = 0, strlen(mName) = 91
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 1
,W/SensorService(  914): Listener[0] = com.htc.smartdim.sensor_eye@41c5bea8
,W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WISPrService( 3286): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
V/ConnectivityService(  914): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  914): default: teardown()
D/MDST    (  914): default: setTeardownRequested(true)
D/PMN     (  914): goingToSleep
D/MDST    (  914): default: setEnableApn apnType =default , enable=false
D/PMS     (  914): acquireWL(43136f98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 914 1000 null
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  914): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  914): syncGetConfiguredNetworks
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/MDST    (  914): default: setTeardownRequested(true)
D/ConnectivityService(  914): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  914): Unexpected mtu value: android.net.wifi.WifiStateTracker@424d4818
D/ConnectivityService(  914): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/SmartSyncUtils( 4098): isEpsOn(), nState = 0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  914): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/PMS     (  914): acquireWL(434ab4c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4098 1000 null
D/ConnectivityService(  914): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,I/QuickSettingWifi( 1110): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  914): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/ConnectivityService(  914): handleConnectivityChange: resetting
D/Nat464Xlat(  914): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  914): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/WifiDataStallTracker(  914): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  914): stopDataStallAlarm: current tag=20790 mDataStallAlarmIntent=PendingIntent{430d3e48: PendingIntentRecord{434ec848 android broadcastIntent}}
D/ConnectivityService(  914): sendGeneralBroadcast, restrictEnable=false
D/AlarmManager(  914): ACTION_SCREEN_OFF
I/AlarmManager(  914): [AlarmQueuing] screen off now: 
I/AlarmManager(  914): [AlarmQueuing] data connection: true
I/AlarmManager(  914): [AlarmQueuing] wifi connection: true
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  914): releaseWL(434ab4c8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  914): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  914): acquireWL(42601ae0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 914 1000 null
D/ConnectivityService(  914): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): releaseWL(42601ae0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WirelessDisplayService(  914): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  914):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  914): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  914): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): SET_SCREEN_ON:Off
I/wpa_supplicant( 4004): htc_wext_set_keepalive +
I/wpa_supplicant( 4004): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 4004): getPrivFuncNum +	
I/wpa_supplicant( 4004): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 4004): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 4004): get_ip_address source addr = c0a80175
I/wpa_supplicant( 4004): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 4004): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  914):    returned true
D/SmartSyncUtils( 4098): getMobilePolicyEnabled, result = true
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,D/PMS     (  914): acquireWL(42a018e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 914 1000 null
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,D/WifiNative-wlan0(  914):    returned true
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
D/PMS     (  914): releaseWL(42a018e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  914): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4134 uid=10055 gids={50055, 1023, 3003, 5012}
,V/SRS_Proc(  369): ParamSet string: screen_state=off
,D/ContactMessageStore( 1223): start background delete task...
,I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/ContactMessageStore( 1223): size: 0 , 0
,D/ContactMessageStore( 1223): Background delete complete
,D/ConnectivityService(  914): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  914): updateScreenOn: false
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] getTotalRam: 1873 Mb
D/PMS     (  914): acquireWL(44043358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(4378e798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(44043358): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(4378e798): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 3979): onScreenOff
,D/PluginProvider( 4134): PluginProvider onCreate
,D/PluginProvider( 4134): current plugin count: 18
,D/HtcAppUPService( 4134): HtcUPDataProvider onCreate()
,D/AutoSetting( 4134): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3286): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3286): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3286): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3286): Cust_ConnectToPC   : spcsc>false
D/        ( 3286): Cust_ConnectToPC   : IPT>true
D/        ( 3286): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3286): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3286): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3286): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/AutoSetting( 4134): service - onCreate()
,D/SmartNS_NSReceiver( 3286): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3286): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 4134): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3286): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3286): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3286):  defaultType:0
I/ActivityManager(  914): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  914): Resuming delayed broadcast
,D/AutoSetting( 4134): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  914): request 42276e80 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  914): provider request: passive ProviderRequest[ON interval=0]
,W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4098): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4098): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4098): isEpsOn(), nState = 0
D/WifiService(  914): New client listening to asynchronous messages
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  914): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c5bea8
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 1
W/SensorService(  914): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  914): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c5bea8, eanble = 0, strlen(mName) = 36
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  914): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  914): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  914): pid=914, uid=1000
W/SensorService(  914): Active sensors: size = 0
W/SensorService(  914): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c5bea8, eanble = 0, strlen(mName) = 36
W/SensorService(  914): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  914): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  914): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c5bea8
E/ActivityThread(  914): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425b1968 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  914): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425b1968 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  914): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  914): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  914): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  914): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  914): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  914): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  914): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  914): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  914): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  914): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  914): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  914): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  914): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  914): Activity pause timeout for ActivityRecord{4379d5d0 u0 com.test.thalitest/.MainActivity t2}
,I/CalendarProvider2( 4066): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 4066): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ProviderChangeReceiver( 3792): ---------------------------------------------------
,D/ProviderChangeReceiver( 3792): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3792): start to updateAlertNotification!
,W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3792): No fired or scheduled alerts
,D/HtcAlertUtils( 3792): -- cancelReminderNotification --
,D/HtcAlertUtils( 3792): broadcastExistReminder!
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  914): killProcessQuiet, pid=3719
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3719:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3719
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  914): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  914): [AlarmQueuing] connectivity wifi: true
,I/ActivityManager(  914): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4164 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
,D/GpsLocationProvider(  914): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  914): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,V/Tethering(  914): bSetPropertyMultiRAB:false
,D/Tethering(  914): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  914): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/PMS     (  914): acquireWL(427540d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
I/Tethering(  914): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  914): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  914): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  914): Found interface wlan0
,D/Tethering(  914): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1251): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  914): NoActiveNetworkState
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.htc.launcher (1251/10076)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.musicenhancer (3360/10053)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  914): DelayedCaptiveCheckState
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
,D/libc    (  914): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - new mNetworkConnected = true,
D/libc    (  362): [NET] +++++ res_nsend xid =cfee +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/GpsLocationProvider(  914): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  914): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(43b77080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=50 [2][1][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,I/MusicStore( 4164): Database version: 95,
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 139
D/libc    (  362): [NET]res_nsend:resplen=104
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo_proxy-, success
,D/PMS     (  914): acquireWL(43cea748): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 914 1000 WorkSource{10029}
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): acquireWL(4345ac38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 914 1000 WorkSource{10029}
D/PMS     (  914): acquireWL(437b8da0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 914 1000 WorkSource{10029}
,D/PMS     (  914): acquireWL(432c7f90): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 914 1000 WorkSource{10029}
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/PMS     (  914): acquireWL(427013e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 914 1000 WorkSource{10096}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4164): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  914): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4190 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  914): [handleMessage] INJECT_NTP_TIME
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
,D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =fae +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo_proxy-, success
D/PMS     (  914): releaseWL(43b77080): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(427339d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(427339d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,W/dalvikvm( 1965): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  914): acquireWL(4403b8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(4403b8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(43798640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4164): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4164): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/PMS     (  914): releaseWL(43798640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(427229b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4164, uid=10154, userID:0
,D/PMS     (  914): releaseWL(427229b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  914): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1965): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(4343f098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(432c7f90): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,D/MediaRouterService(  914): Client com.google.android.music (pid 4164): Registered
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
I/MediaRouter( 4164): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor( 4164): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.music (4164/10154)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (2151/10021)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
I/ActivityManager(  914): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4212 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/SyncManager(  914): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 26052, reason: UserStart, SyncResult: databaseError: true stats []
,E/Auth.Api.Credentials( 1965): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager(  914): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 108577, reason: UserStart
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(4343f098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
D/MediaRouter( 4164): getSelectedRoute
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,I/NetworkMonitor( 4164): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(42726538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(4345ac38): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.google.android.music (4164/10154)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  914): acquireWL(42645860): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 914 1000 WorkSource{10029}
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4190): Delaying sync.
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4164, uid=10154, userID:0
D/PMS     (  914): releaseWL(42726538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(42b116c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(42b116c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(4345bb90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(4345bb90): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(434b1da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(43cea748): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): acquireWL(43abe790): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 914 1000 WorkSource{10029}
D/PMS     (  914): releaseWL(434b1da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/PMS     (  914): acquireWL(431d8c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/PhoneStatusBar( 1110): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/PMS     (  914): releaseWL(431d8c88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(439521d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(439521d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(427293e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/Process (  914): killProcessQuiet, pid=3739
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/PMS     (  914): releaseWL(427013e8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  914): Killing 3739:com.htc.backup/1000 (adj 15): empty #17
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/ACRA    ( 4212): ACRA is enabled for com.facebook.katana, intializing...
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  914): Recipient 3739
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(427293e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(441280f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/ACRA    ( 4212): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4212): Looking for error files in /data/data/com.facebook.katana/app_minidumps
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): releaseWL(441280f8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,W/SystemClassLoaderAdder( 4212): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4212): Preparing secondary program dexes.
V/DexLibLoader( 4212): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4212): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4212): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4212): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4212): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4212): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4212): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4212): Dex already copied
D/OdexVerifier( 4212): Odex verification is skipped.
,V/DexLibLoader( 4212): Creating class loader
,V/DexLibLoader( 4212): Finished creating class loader
V/DexLibLoader( 4212): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4212): Dex already copied
D/OdexVerifier( 4212): Odex verification is skipped.
,V/DexLibLoader( 4212): Creating class loader
,V/DexLibLoader( 4212): Finished creating class loader
V/DexLibLoader( 4212): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4212): Dex already copied
D/OdexVerifier( 4212): Odex verification is skipped.
,V/DexLibLoader( 4212): Creating class loader
,V/DexLibLoader( 4212): Finished creating class loader
V/DexLibLoader( 4212): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4212): Dex already copied
D/OdexVerifier( 4212): Odex verification is skipped.
,V/DexLibLoader( 4212): Creating class loader
,V/DexLibLoader( 4212): Finished creating class loader
,V/DexLibLoader( 4212): Verifying classes from secondary dexes.
,W/DriveInitializer( 1965): Awaiting to be initialized
,W/DriveInitializer( 1965): Background init thread started
,D/DexLibLoader( 4212): DexLibLoader.ensureDexLoaded took 128 ms
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1965): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,W/DriveInitializer( 1965): Background init thread ended
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(4272ce80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(42645860): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  914): acquireWL(434fd5c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 914 1000 WorkSource{10096}
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(4272ce80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(426728d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(437b8da0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4190): Delaying sync.
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(426728d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(42c66be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(42c66be0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(42668e30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(43abe790): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): acquireWL(43854c18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 914 1000 WorkSource{10029}
D/PMS     (  914): releaseWL(42668e30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
D/PMS     (  914): acquireWL(43726d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(434fd5c8): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
D/PMS     (  914): releaseWL(43726d70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(440df848): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): releaseWL(440df848): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(42677b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(43854c18): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
,D/Process (  914): killProcessQuiet, pid=3757
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/IntentController( 1110): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
I/ActivityManager(  914): Killing 3757:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/PMS     (  914): releaseWL(42677b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Recipient 3757
,D/PhoneStatusBar( 1110): removeIcon slot=sync_active index=7 viewIndex=0
,I/Scheduler( 1201): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 1201): Found 10029
,E/BTIF_CORE( 3913): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3913): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3913): Wake lock released
,W/dalvikvm( 4212): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4212): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4212): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4212): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =bce7 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  914): Find DNS Address www.htc.com/23.59.123.86
,W/fb4a(:<default>):StaticBindingVerifier( 4212): Verify
,D/WifiService(  914): New client listening to asynchronous messages
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4212): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4212): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  914): killProcessQuiet, pid=3706
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  914): Killing 3706:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3706
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4134): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  914): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4259 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 4134): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (4134/10055)
,D/AutoSetting( 4134): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 4134): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4134): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (4134/10055)
,W/fb4a(:<default>):UserScope( 4212): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4212): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4259): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4259): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4259): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4259): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4212): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4259/10079)
,I/ActivityManager(  914): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4273 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  914): killProcessQuiet, pid=3515
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  914): Killing 3515:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4259/10079)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4259/10079)
I/ActivityManager(  914): Recipient 3515
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  914): acquireWL(42551d98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(4346a120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1965): Checkin interval check for package: unspecified last checkin: 1449681172522 min interval config: 0 actual interval: 2459212
D/PMS     (  914): releaseWL(42551d98): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1965): Checking schedule, now: 1449683631743 next: 1449681202492
,I/CheckinService( 1965): active receiver: enabled
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1965, uid=10029, userID:0
,I/CheckinService( 1965): Preparing to send checkin request
,I/EventLogService( 1965): Accumulating logs since 1449682776069
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,W/GAV2    ( 4273): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4273): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4273): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/dalvikvm( 4212): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4212): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4273): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4273): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4212): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4212): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4212): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4212): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4212): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4212): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 9.971MB for 28144-byte allocation
,W/dalvikvm( 4212): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4212): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4212): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4212): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4212): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4212): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4212): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4212): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4212): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4212): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4273/10151)
,V/WebViewChromiumFactoryProvider( 4273): Binding Chromium to main looper Looper (main, tid 1) {41b4ed50}
,I/LibraryLoader( 4273): Expected native library version number "",actual native library version number ""
,I/chromium( 4273): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4273): Initializing chromium process, renderers=0
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 10.015MB for 39954-byte allocation
D/PMS     (  914): acquireWL(43108190): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/PMS     (  914): acquireWL(434ae388): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
,E/AudioManagerAndroid( 4273): BLUETOOTH permission is missing!
D/PMS     (  914): releaseWL(43108190): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/WifiService(  914): New client listening to asynchronous messages
I/ActivityManager(  914): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/Adreno-EGL( 4273): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4273): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4273): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4273): Local Branch: 
I/Adreno-EGL( 4273): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4273): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4273):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 10.091MB for 79892-byte allocation
,I/NSApplication( 4273): Starting up...
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4273/10151)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4273/10151)
,I/ActivityManager(  914): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4312 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/ConnectivityService(  914): getNetworkInfo networkType=9 called by com.google.android.gms (1965/10029)
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/dalvikvm-heap( 4212): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,W/BroadcastQueue(  914): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42695ab8 u0 ReceiverList{425e0a58 4212 com.facebook.katana/10027/u0 remote:43c162e8}}
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BroadcastQueue(  914): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43482288 u0 ReceiverList{43482228 4212 com.facebook.katana/10027/u0 remote:434c6578}}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/PMS     (  914): acquireWL(44200d08): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4312 10160 null
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
,D/PMS     (  914): acquireWL(44132828): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4312 10160 null
,D/PMS     (  914): releaseWL(44200d08): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(434add88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(434add88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1965, uid=10029, userID:0
,I/ActivityManager(  914): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4343 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/iu.SyncManager( 1965): SYNC; picasa accounts
,D/NetworkLogImpl( 1965): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/dalvikvm( 4343): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4343): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4343): install
,I/iu.Environment( 1965): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/MultiDex( 4343): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/iu.UploadsManager( 1965): num queued entries: 0
,I/iu.UploadsManager( 1965): num updated entries: 0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/iu.SyncManager( 1965): NEXT; no task
,I/MultiDex( 4343): loading existing secondary dex files
,I/MultiDex( 4343): load found 3 secondary dex files
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4343): install done
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4343): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4343): VFY: unable to resolve instance field 36
W/dalvikvm( 4343): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,V/JNIHelp ( 4343): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 4212): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/PMS     (  914): releaseWL(44132828): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,I/ActivityManager(  914): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4359 uid=10041 gids={50041}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/Process (  914): killProcessQuiet, pid=3479
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3479:com.google.android.gm/u0a107 (adj 15): empty #17
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1357): [NET] getaddrinfo-,err=8
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/PMS     (  914): acquireWL(43833fb8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1357): [NET] getaddrinfo-, 1
D/libc    ( 1357): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =f754 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
I/ActivityManager(  914): Recipient 3479
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  914): killProcessQuiet, pid=3542
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  914): Killing 3542:com.android.vending/u0a74 (adj 15): empty #17
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 15
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
I/dalvikvm-heap( 4312): Grow heap (frag case) to 15.207MB for 1821008-byte allocation
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1357): [NET] getaddrinfo_proxy-, success
,I/ProviderInstaller( 4343): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  914): acquireWL(4370f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4343): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4343): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
W/dalvikvm( 4343): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4343): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4343): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4343): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
W/dalvikvm( 4343): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1357): [NET] getaddrinfo-,err=8
,I/ActivityManager(  914): Recipient 3542
,D/WearableService( 1201): callingUid 10029, callindPid: 1201
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/MDM     ( 1201): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/PMS     (  914): releaseWL(4370f808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1357): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,I/GCM     ( 1357): GCM config loaded
D/AuthorizationBluetoothService( 1357): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1357): Proximity feature is not enabled.
,D/LocationInitializer( 1965): Restart initialization of location
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1201): location=null
,D/NativeLibraryUtils( 4343): Install completed successfully. count=14 extracted=0
D/PMS     (  914): acquireWL(426b6fe8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(426b6fe8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): acquireWL(43338df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/WVCdm   (  369): PrepareKeyRequest: nonce=3280834549
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/PMS     (  914): releaseWL(43833fb8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  914): handleInetConditionChange: starting a change hold
,D/PMS     (  914): releaseWL(43338df0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(431491f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  914): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  914): reportInetCondition for net 1, percentage: 100 by  (1357/10029)
,D/ConnectivityService(  914): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  914): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(431491f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/WifiStateMachine(  914): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  914): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=3671751948
,I/WVCdm   (  369): CdmEngine::CloseSession
,W/Settings( 4343): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  914): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  914): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=50 [8][4][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,W/ActivityManager(  914): Sleep timeout!  Sleeping now.
,D/PMS     (  914): releaseWL(43136f98): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/Adreno-EGL( 4343): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4343): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4343): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4343): Local Branch: 
I/Adreno-EGL( 4343): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4343): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4343):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (4343/10029)
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
,I/jxcore-log( 3864): Test app app.js loaded
I/jxcore-log( 3864): 
,I/Choreographer( 3864): Skipped 540 frames!  The application may be doing too much work on its main thread.
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,W/ResourceType( 3864): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3864): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b5e280 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 3864): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/libc    ( 1965): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1965): [NET] getaddrinfo-,err=8
,D/libc    ( 1965): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 1965): [NET] getaddrinfo-, 1
,D/libc    ( 1965): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =aede +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 296
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1965): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1965): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1965): [NET] getaddrinfo-,err=8
,D/libc    ( 1965): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1965): [NET] getaddrinfo-,err=8
D/libc    ( 1965): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1965): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1965): Sending checkin request (12236 bytes)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,W/fb4a(:<default>):UserScope( 4212): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4212): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [17][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/PMS     (  914): acquireWL(425ff4a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4164 10154 null
,I/CheckinRequestBuilder( 1965): Checkin reason type: 8 attempt count: 1
,W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  914): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1965): Failed to find provider info for com.google.android.wearable.settings
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4164, uid=10154, userID:0
,I/MusicLeanback( 4164): Conditions not met for autocaching.
,I/MusicLeanback( 4164): Stop autocaching.
,D/PMS     (  914): releaseWL(425ff4a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4164): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/fb4a(:<default>):LocalFbBroadcastManager( 4212): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  914): getNetworkInfo networkType=9 called by com.google.android.gms (1965/10029)
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [4][0][0]
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/CheckinRequestBuilder( 1965): Classify the device as Phone.
,I/CheckinTask( 1965): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1965): Checking schedule, now: 1449683634726 next: 1450206571720
,I/CheckinService( 1965): active receiver: disabled
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1965, uid=10029, userID:0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/CheckinService( 1965): Recording last checkin time for package unspecified as 1449683634745
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/PMS     (  914): releaseWL(4346a120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/GCM     ( 1357): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/PMS     (  914): releaseWL(434ae388): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  914): Killing 3360:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  914): killProcessQuiet, pid=3360
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  914): Recipient 3360
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4273): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  914): killProcessQuiet, pid=4005
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  914): killProcessQuiet, pid=3835
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4005:com.htc.widget.process2/u0a50 (adj 15): empty #17
I/ActivityManager(  914): Killing 3835:com.htc.mms.backupagent/u0a78 (adj 15): empty #18
,I/ActivityManager(  914): Recipient 4005
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Recipient 3835
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4134): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4134): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4134): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  914): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  914): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  914): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  914): acquireWL(429f3ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(429f3ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  914): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4411 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1251): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1236): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1251): Deferring update until onResume
D/Launcher( 1251): waitUntilResume // bindAppsUpdated
I/PackageManager(  914):   Scheme: "smsto"
,W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
,D/PhoneApp( 1223): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4411): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4411): MmsConfig.loadMmsSettings
,W/dalvikvm( 4411): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4411): VFY: unable to resolve instance field 36
,W/dalvikvm( 4411): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4411): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4411, uid=10111, userID:0
,W/Settings( 4411): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  914): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4434 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4411, uid=10111, userID:0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4411, uid=10111, userID:0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4411, uid=10111, userID:0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4411, uid=10111, userID:0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4411, uid=10111, userID:0
,D/PMS     (  914): acquireWL(4291c5a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4411 10111 null
,I/[PluginManager]RegisterService( 4134): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4134): handle notify Blinkfeed plugin client changed
,D/MessageFrequencyProvider( 4434): onCreate,
I/ActivityManager(  914): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  914): Resuming delayed broadcast
,V/GetPrviateResource( 4434): GetPrviateResource
,V/GetPrviateResource( 4434): GetPrviateResource
,D/MmsCustomizationProvider( 4434): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  914): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  914): acquireWL(43128d90): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43128d90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(4291c5a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/MmsCustomizationProvider( 4434): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ProviderInstaller( 4411): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  914): Resuming delayed broadcast
I/Babel   ( 4411): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4411): MmsConfig.loadFromDatabase
D/PMS     (  914): acquireWL(43873b78): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  914): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,E/Babel   ( 4411): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4411): MmsConfig.loadFromResources
,E/Babel   ( 4411): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4411): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,W/PackageManager(  914): Unable to load service info ResolveInfo{43c22e48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  914): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  914): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  914): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  914): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  914): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  914): 	at dalvik.system.NativeStart.main(Native Method)
,D/MessageCustFlag( 4434): sense_version=6.0
D/BTAccessoryUtil( 4434): createReceiver
D/BTAccessoryUtil( 4434): registerReceiver return intent = null
D/MessageCustFlag( 4434): sku_id=99
W/SystemReader( 4434): Cannot find message_ambs_application_id, use default value instead
D/Messaging( 4434): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4434): networkCode: 
D/MessageCustFlag( 4434): sku_id=99
D/MmsConfig( 4434): SIE smsPri: null
D/MmsConfig( 4434): networkCode: 
D/HtcTelephonyCapability( 4434): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4434): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4434): getRATByHtcTelephonyCapability:1
W/SystemReader( 4434): Cannot find qct_8960_interface, use default value instead
D/PMS     (  914): releaseWL(43873b78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Resuming delayed broadcast
,D/PMS     (  914): acquireWL(43c76058): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  914): acquireWL(440e9738): PARTIAL_WAKE_LOCK  AsyncService 0x1 4312 10160 null
,D/PMS     (  914): releaseWL(440e9738): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  914): releaseWL(43c76058): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Resuming delayed broadcast
,I/ActivityManager(  914): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  914): acquireWL(43763aa0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43763aa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Resuming delayed broadcast
,I/ActivityManager(  914): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4461 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/PMS     (  914): acquireWL(43782830): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43782830): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(434b1eb0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(434b1eb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(435ba4a0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 4461): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/PMS     (  914): releaseWL(435ba4a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4461, uid=10074, userID:0
,D/PMS     (  914): acquireWL(426967e0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4461): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4461/10074)
D/PMS     (  914): releaseWL(426967e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43757f00): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43757f00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/RemoteDisplayProvider(  914): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  914): start
,I/GCoreNlp( 1201): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 342 ms] updated apps [took 342 ms] 
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/LocationProviderProxy(  914): applying state to connected service
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4461/10074)
,D/LocationProviderProxy(  914): applying state to connected service
,D/Finsky  ( 4461): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/PMS     (  914): acquireWL(43c5f908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43c5f908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Settings( 4461): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4461): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  914): acquireWL(43137368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43137368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(43b929e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43b929e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4461, uid=10074, userID:0
,D/Ads     ( 4461): Skipping gmscore version check
,D/Finsky  ( 4461): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4461): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4461): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4461): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4461): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1965): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1965): Null package name or gms related package.  Ignoreing.
,D/Process (  914): killProcessQuiet, pid=3939
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3939:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
,D/PMS     (  914): acquireWL(441220a8): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms},
I/ActivityManager(  914): Recipient 3939
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 1965): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1251): loadItems() com.htc.launcher.pageview.WidgetManager@41be3eb0 +
,I/Prism.WidgetManager( 1251): onLoadItems() +
,I/ActivityManager(  914): Waited long enough for: ServiceRecord{42ac4c48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Prism.WidgetManager( 1251): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1251): onLoadItems() -
,I/Prism.ItemManager( 1251): loadItems() com.htc.launcher.pageview.WidgetManager@41be3eb0 -
,I/Icing   ( 1965): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/PhoneApp( 1223): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1223): -- N1 =0
,D/PhoneApp( 1223): -- N2 =0
,D/PhoneApp( 1223): -- N3 =0
,I/Icing   ( 1965): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  914): releaseWL(441220a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4434): mNeedToUpdateDate2 start
,D/MmsConfig( 4434): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4434): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4434): 
D/MmsAsyncWorkHandler( 4434): HM tk = 20001
,D/ReportIndicatorCache( 4434): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4434): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b61208
,I/Messaging( 4434): mccmnc> 
D/DraftCache( 4434): [DraftCache/1] DraftCache.constructor
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/DraftCache( 4434): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsConfig( 4434): networkCode: 
D/Messaging( 4434): ViewCache CreatePreloadOnlyConversationList
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29,
D/AccFlag ( 1223): sku_id=99
,D/MessageCustFlag( 4434): sense_version=6.0
D/Jerry   ( 4434): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4434): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4434): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4434): createReceiver
,D/TelephUtils( 1223): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 61
V/MmsProvider( 1223): Update uri=content://mms, match=0
,D/DraftCache( 4434): [DraftCache/439] rebuildCache
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/MmsProvider( 1223): selection=st=129 AND m_type!=134
,D/Messaging( 4434): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4434): TransactionService is going to be woken up.
,D/Messaging( 4434): mNeedToUpdateDate2: false
,V/TransactionService( 4434): 1-Creating TransactionService
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/TransactionService( 4434): onStartCommand: 1
D/MmsSystemEventReceiver( 4434): unRegisterForConnectionStateChanges
V/TransactionService( 4434): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4434): Loading previous transactions.
,D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 61
,D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1223): device_type: 1
D/TransactionService( 4434): Force set service start id to 1
V/TransactionService( 4434): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4434): unRegisterForConnectionStateChanges
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/TransactionService( 4434): stopSelfResult: true, mLastHandledServiceId: 1
,D/Jerry   ( 1223): URI_DRAFT
,V/TransactionService( 4434): Destroying TransactionService
,V/TransactionService( 4434): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4434): ViewCache CreatePreload
,D/Messaging( 4434): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4434): hasDraft() = false mNeedNotifyChange = true
,D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/DraftCache( 4434): [DraftCache/439] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4434): 
D/MmsAsyncWorkHandler( 4434): HM tk = 20002
,D/MmsSmsV2Provider( 1223):  phoneType = -1
,D/MmsSmsV2Provider( 1223): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Cust_MMSMS( 4434): _has_set_default_values_2=true
,D/Messaging( 4434): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1223): sku_id=99
,D/MsgPreferenceUtils( 4434): def_index: 0
D/MsgPreferenceUtils( 4434): globalIndex = 1
D/TelephUtils( 1223): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1223): sku_id=99
D/MsgPreferenceUtils( 4434): phone state: true
D/MsgPreferenceUtils( 4434): sd state: false
,D/MsgPreferenceUtils( 4434): vIndex = 0
,I/GAV4    ( 4411): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  914): killProcessQuiet, pid=3957
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3957:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3957
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/GpsLocationProvider(  914): requestTime failed
,D/GpsLocationProvider(  914): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  914): releaseWL(427540d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  914): acquireWL(42564258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42564258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
,D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(420d8cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{426ac120: PendingIntentRecord{42761c20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137431, Int=0
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/PMS     (  914): releaseWL(420d8cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(42002998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{41dac998: PendingIntentRecord{42539928 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=138449, Int=0
,D/PMS     (  914): acquireWL(41c32da8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 914 1000 null
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): releaseWL(42002998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(425a4dd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(41c32da8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  914): releaseWL(425a4dd0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 4134): service - mHandler: update timezone
,D/AutoSetting( 4066): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4134): service - handleMessage() stop self
,W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 4066): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 4066): service - onCreate()
W/ActivityManager(  914): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 4134): service - handleMessage() quit looper
,D/AutoSetting( 4134): service - onDestroy() END
,D/AutoSetting( 4066): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4066): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 4066): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 4066): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 4066): service - mHandler: update timezone
,D/AutoSetting( 4066): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 4066): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 4066): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 4066): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1524): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1110): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{41e0e298 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  914): acquireWL(41c566a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{43952658: PendingIntentRecord{42758900 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=141417, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{41ee6d10: PendingIntentRecord{423d35e0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142259, Int=0
,D/PMS     (  914): acquireWL(43144000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=40 [15][6][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): acquireWL(425e04e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(425e04e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43144000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(432c7c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(432c7c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(426a3b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): acquireWL(426b7a10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  914): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  914): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  914): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  914): acquireWL(4379e010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/PMS     (  914): releaseWL(41c566a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  914): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
,D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =58c6 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/PMS     (  914): acquireWL(4272a050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1201): Vacuum at: now=1449683663531 tag=VacuumService
,D/PMS     (  914): releaseWL(426a3b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=243
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  914): [NET] getaddrinfo_proxy-, success
,I/global  (  914): call createSocket() return a new socket.
D/libc    (  914): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  914): releaseWL(426b7a10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(4272a050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(42693a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(42693a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43873bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  914): [handleDownloadXtraData] calling native_inject_xtra_data
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(43873bb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(434d4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=29 [27][8][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(434d4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  914): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  914): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  914):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  914): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  914): releaseWL(4379e010): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  914): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  914): killProcessQuiet, pid=4098
,I/ActivityManager(  914): Killing 4098:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  914): Recipient 4098
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  914): Client connection lost with reason: 4
,D/PMS     (  914): acquireWL(43123838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): releaseWL(43123838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1223): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1223): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  914): Waited long enough for: ServiceRecord{43380fd8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  914): acquireWL(434c84e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{41dac998: PendingIntentRecord{42539928 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=168471, Int=0
,D/PMS     (  914): acquireWL(43ce9f70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 914 1000 null
D/PMS     (  914): releaseWL(434c84e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(431047c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  914): acquireWL(434d4ce8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 914 1000 WorkSource{10029}
,D/PMS     (  914): releaseWL(43ce9f70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/PMS     (  914): releaseWL(431047c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(426be030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null,
,D/PMS     (  914): releaseWL(426be030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  914): Cannot resolve ContentProvider=com.android.contacts.metadata
,E/ActivityThread( 1965): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(4411cab8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/SyncManager(  914): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 26022, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  914): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 168678, reason: UserStart
D/PMS     (  914): releaseWL(434d4ce8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  914): releaseWL(4411cab8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/PMS     (  914): acquireWL(43abe938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
D/PMS     (  914): releaseWL(43abe938): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
,W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,D/AutoSetting( 4066): service - handleMessage() stop self
,D/AutoSetting( 4066): service - onDestroy() END
,D/AutoSetting( 4066): service - handleMessage() quit looper
,D/Process (  914): killProcessQuiet, pid=3792
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3792:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3792
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1223): switchBindHtcMsgCursor: null
,D/PMS     (  914): acquireWL(42cbc570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42cbc570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(434c5ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(434c5ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(43746e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,D/PMS     (  914): acquireWL(440df918): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 914 1000 null
,V/AlarmManager(  914): sending alarm PendingIntent{41dac998: PendingIntentRecord{42539928 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=198512, Int=0
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(43fe1d88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(43746e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): releaseWL(440df918): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  914): releaseWL(43fe1d88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  914): acquireWL(42724cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  914): sending alarm PendingIntent{440de600: PendingIntentRecord{42758900 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185079, Int=0
,D/PMS     (  914): acquireWL(43b77110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
V/AlarmManager(  914): sending alarm PendingIntent{42416f80: PendingIntentRecord{423b5768 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=188412, Int=0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=6 [15][1][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-,err=8
D/libc    (  914): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  914): [NET] getaddrinfo-, 1
D/libc    (  914): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024,
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =4caf +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  914): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  914): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4543 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  914): sending alarm PendingIntent{41c5f650: PendingIntentRecord{425ceba8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449683733669, Int=10800000
D/PMS     (  914): releaseWL(42724cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.aurora (4543/10049)
,D/PMS     (  914): acquireWL(43c115b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/Process (  914): killProcessQuiet, pid=3806
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 3806:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 3806
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  914): Client connection lost with reason: 4
,D/PMS     (  914): releaseWL(43c115b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(43b77110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(44200c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(44200c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(436491b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 4004): Change stage from stage0 to stage3
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): acquireWL(42686f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): releaseWL(436491b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1201): Scheduling Phenotype for one-off execution 11516 seconds from now (1449683734390)
,D/GetConfigurationSnapshotOperation( 1201): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1201): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1201): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1201): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1201): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1201): [NET] getaddrinfo-,err=8
D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1201): [NET] getaddrinfo-, 1
,D/libc    ( 1201): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =b0da +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 274
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1201): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1201): [NET] getaddrinfo-,err=8
D/libc    ( 1201): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1201): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  914): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
,D/PMS     (  914): releaseWL(42686f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43424010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
,W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(43424010): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  914): acquireWL(43090d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 4004): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  914): doString: SIGNAL_POLL
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: survey data missing!
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 4004): environment dirty rate=0 [0][0][0]
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,D/PMS     (  914): releaseWL(43090d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  914): acquireWL(434a7018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(434a7018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(43599438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43599438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  914): acquireWL(440c11b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=299018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(440c11b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(4411f820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4411f820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(434ceda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(434ceda8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4385bda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4385bda8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 3864): Toggling radios to false
I/jxcore-log( 3864): 
,D/BluetoothManagerService(  914): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  914): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42585a88 mBinding = false
,W/HtcDLNAServiceManager(  914): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  914): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  914): Settings:Agentvalue: 0
,W/Settings:Agent(  914): >> traceCallingStack()
W/Settings:Agent(  914): Process.myPid(): 914
,W/Settings:Agent(  914): Process.myTid(): 925
W/Settings:Agent(  914): Process.myUid(): 1000
,W/Settings:Agent(  914): 
W/Settings:Agent(  914): 
,W/System.err(  914): java.lang.Throwable: stack dump
,W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  914): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  914): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  914): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  914): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  914): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  914): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  914): 
,W/Settings:Agent(  914): << traceCallingStack(): 12(ms)
,D/BluetoothManagerService(  914): Message: MESSAGE_DISABLE
D/BluetoothManagerService(  914): Sending off request.
,D/WifiManager( 3864): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,D/WifiStateMachine(  914): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  914): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  914): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  914): Settings:Agentvalue: 0
W/Settings:Agent(  914): >> traceCallingStack()
W/Settings:Agent(  914): Process.myPid(): 914
W/Settings:Agent(  914): Process.myTid(): 1980
W/Settings:Agent(  914): Process.myUid(): 1000
W/Settings:Agent(  914): 
W/Settings:Agent(  914): 
W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  914): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  914): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  914): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  914): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  914): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  914): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  914): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  914): 
,W/Settings:Agent(  914): << traceCallingStack(): 2(ms)
D/BluetoothAdapterState( 3913): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3913): Setting state to 13
I/BluetoothAdapterState( 3913): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3913): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  914): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 3913): onBluetoothDisable()
I/bt-btm  ( 3913): BTM_SetDiscoverability
I/BluetoothAdapterState( 3913): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_properties_cb
,I/bt-btm  ( 3913): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3913): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3913): br_edr_supported=0x0
I/bt-btm  ( 3913): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3913): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterProperties( 3913): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 3913): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3913): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
,I/bt-btm  ( 3913): BTM_SetConnectability
I/bt-btm  ( 3913): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3913): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 3913): Scan Mode:20
E/BTIF_CORE( 3913): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 3913): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothAdapterState( 3913): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer
,D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer
D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer,
D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer
D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer
D/bt-btm  ( 3913): SDP_DeleteRe
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
,D/WifiService(  914): setWifiEnabled: false pid=3864, uid=10389
E/WifiService(  914): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  914): isSprintWifiRestricted(): false
I/WifiService(  914): isMdmWifiRestricted(): false
D/WifiSettingsStore(  914): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
E/BtOppRfcommListener( 3913): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btif ( 3913): BTA_JvDeleteRecord
I/bt-btif ( 3913): BTA_JvRfcommStopServer
D/bt-btm  ( 3913): BTM_FreeSCN 
V/BluetoothSapService( 3913): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/bt-btm  ( 3913): BTM_SEC_CLR[13]: id 52,
D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3913): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
,I/bt-btm  ( 3913): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
D/BluetoothManagerService(  914): Bluetooth State Change Intent: 12 -> 13
I/bt-btm  ( 3913): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3913): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:10
,E/bt-btif ( 3913): bta_jv_rfcomm_stop_server
I/bt-btm  ( 3913): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): Write Extended Inquiry Response to controller
I/bt-btm  ( 3913): BTM_SetDiscoverability
,I/bt-btm  ( 3913): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3913): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3913): br_edr_supported=0x0
I/bt-btm  ( 3913): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3913): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3913): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3913): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3913): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3913): BTM_SetConnectability
I/bt-btm  ( 3913): btm_ble_set_connectability mode=0x0 combined_mode=0x0
,I/bt-btm  ( 3913): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3913): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3913): BTM_IsInquiryActive
I/bt-btm  ( 3913): BTM_CancelRemoteDeviceName()
W/bt-btif ( 3913): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btm  ( 3913): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3913): BTM_FreeSCN 
I/bt-btm  ( 3913): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3913): AVRC_Close handle:0
,D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 3913): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3913): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3913): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 3913): GATT_Deregister gatt_if=3
I/bt-att  ( 3913): GATT_Deregister gatt_if=4
I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 3913): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothRemoteDevices( 3913): Wake lock Aquired
,V/BluetoothPbapReceiver( 3913): ***********state = 13
D/PMS     (  914): acquireWL(426890d8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 3913 1002 null
,D/WirelessDisplayService(  914): getMirrorDisplayStatus:falsecurState:1
,I/jxcore-log( 3864): Radios toggled
I/jxcore-log( 3864): 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 3979): Received state change = 13
D/WifiPerfLock(  914): release()
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b78c88
,D/WifiStateMachine(  914): PerfLock released for exiting ConnectedState
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): onDeInitialized
D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 3913): SapReceiver onReceive 
V/BluetoothSapReceiver( 3913): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3913):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 3913): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  914): acquireWL(4323e7b8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
D/PMS     (  914): acquireWL(434c0eb0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3286 1000 null
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  914): releaseWL(4323e7b8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/ConnectivityService(  914): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,V/BluetoothPbapService( 3913): Pbap Service closeService in
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): cancelAllNotification
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): getNotificationManager
,D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): Power_Mode_Type mode = 0
I/wpa_supplicant( 4004): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  914):    returned true
D/PMS     (  914): releaseWL(434c0eb0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  914): acquireWL(434235d0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3286 1000 null
D/PMS     (  914): acquireWL(440ed960): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 914 1000 null
D/WifiP2pService(  914): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  914): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  914): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  914): [RunningState] Stop DHCP
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  914): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  914): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
,I/ActivityManager(  914): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4580 uid=10040 gids={50040, 3002, 3001}
D/DockEventReceiver( 3286): finishStartingService: stopping service
D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING GET
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  914): stopDataStallAlarm: current tag=20791 mDataStallAlarmIntent=null
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  914):    returned null
E/WifiStateMachine(  914): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  914): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  914):    returned null
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  914): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  914): Provision feature enable=false
D/ConnectivityService(  914): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/PMS     (  914): releaseWL(434235d0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  914): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  914): isAvailable+-
D/UsbnetStateTracker(  914): reconnect
D/UsbnetStateTracker(  914): isAvailable+-
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3979): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 3979):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3979): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 3979):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 3979): deinit: 0
,D/WifiStateMachine(  914): Call handleNetworkDisconnect() in SupplicantStoppingState
D/BluetoothManagerService(  914): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  914): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424bb4c8:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 3979): disableBatteryAlarm: null
V/BluetoothPbapService( 3913): successfully stopped pbap service
V/BluetoothPbapService( 3913): Pbap Service closeService out
D/WISPrService( 3286): >>>>>WISPrService start isConnected = false<<<<<
V/BluetoothSapService( 3913): action: android.bluetooth.adapter.action.STATE_CHANGED
D/WifiNative-wlan0(  914): doBoolean: DRIVER POWERMODE 0
D/BluetoothPbap( 3286): Proxy object disconnected
D/PbapServerProfile( 3286): Bluetooth service disconnected
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
V/BluetoothSapService( 3913): state: 13
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 4004): Power_Mode_Type mode = 0
I/wpa_supplicant( 4004): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 61
D/WISPrService( 3286): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  914):    returned true
D/WifiNative-wlan0(  914): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothAdapter( 3913): 1102494168: getState(). Returning 13
V/BluetoothSapService( 3913): Stopping SAP server process
W/WifiHW  (  914): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 3979): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3979): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3979): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 3979): Exit IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 3979): setPendingRequestAlarm: false, mContext = null, null
I/wpa_supplicant( 4004): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 4004): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  914):    returned true
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  914): P2pDisablingState
D/MDST    (  914): default: reconnect()
D/MDST    (  914): default: setTeardownRequested(false)
D/MDST    (  914): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  914): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): p2p socket connection lost
D/WifiP2pService(  914): P2pDisabledState
D/WifiDisplayController(  914): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  914): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  914): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  914): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  914): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  914): P2pDisabledState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  914):  WFD CtrlPort: 0
D/WifiP2pService(  914):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  914): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  914): updateConnection
D/WifiP2pService(  914): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  914):  WFD CtrlPort: 0
D/WifiP2pService(  914):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  914): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  914): updateConnection enter step 4
D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
D/WifiP2pService(  914): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  914): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothSapService( 3913): Sap Service closeSapService in
V/BluetoothSapService( 3913): Close listen Socket : 
V/BluetoothSapService( 3913): Close rfcomm Socket : 
V/BluetoothSapService( 3913): Close sapd  Socket : 
V/BluetoothSapReceiver( 3913): BluetoothSapReceiver deinit
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
V/AudioService(  914): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  914):     Client/Owner: Client
V/AudioService(  914):     GroupId: 
V/AudioService(  914):     Passphrase: 
V/AudioService(  914):     SessionId: 0
V/AudioService(  914):     IP Address: }
D/HtcEffectManagerBase(  914): onEventChanged id=5 status=false
D/HtcEffectManager(  914): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  914): convertEffect before=902
D/HtcEffectManager(  914): convertEffect after=902
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1110): removeIcon slot=bluetooth index=12 viewIndex=0
D/WifiDisplayController(  914): Failed to set WFD info with reason 2.
D/ConnectivityService(  914): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  914): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  914): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  914): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  914): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  914): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-p2p0(  914): doBoolean: TERMINATE
W/WifiHW  (  914): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 4004): Supplicant Terminat @ wpa_supplicant_deinit function
V/NativeCrypto( 1357): Read error: ssl=0x647ffa20: I/O error during system call, Connection timed out
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-p2p0(  914):    returned true
D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 4004): TDLS: Tear down peers
I/wpa_supplicant( 4004): wpa_driver_nl80211_disconnect(reason_code=3)
I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NativeCrypto( 1357): SSL shutdown failed: ssl=0x647ffa20: I/O error during system call, Broken pipe
W/ConnectivityService(  914): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  914): handleConnectivityChange: resetting
D/ConnectivityService(  914): resetConnections(wlan0, 3)
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  914): acquireWL(44070d58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1357 10029 WorkSource{10029 com.google.android.gms}
D/SapServerProfile( 3286): Bluetooth service disconnected
V/BluetoothSapService( 3913): successfully stopped Sap service
V/BluetoothSapService( 3913): Sap Service closeSapService out
I/BtOppRfcommListener( 3913): stopping Accept Thread
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  914): [MLHD] Error! unhandled message 1 { when=-28ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
I/BtOppRfcommListener( 3913): BluetoothSocket listen thread finished
D/libc    (  362): [NET] entry_id:3   entry:0xb87830f8  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb8783968  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb8783428  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb87832d8  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb87834f0  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb8782eb0  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
D/ConnectivityService(  914): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  914): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  914): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  914): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WISPrService( 3286): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
D/HtcBtWidget_BTWidgetProvider( 4580): onBTStateChanged() for widget: 
E/WifiStateMachine(  914): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3286): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HtcBtWidget_BTWidgetProvider( 4580): updateWidget(context) for widget: 
I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:1
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/BluetoothPbapService( 3913): Pbap Service onDestroy
V/BluetoothPbapService( 3913): Pbap Service closeService in
V/BluetoothPbapService( 3913): Pbap Service closeService out
V/BluetoothSapService( 3913): onUnbind: android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3913): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41ba4228
V/BluetoothSapService( 3913): Sap Service closeSapService in
V/BluetoothSapService( 3913): Close listen Socket : 
V/BluetoothSapService( 3913): Close rfcomm Socket : 
V/BluetoothSapService( 3913): Close sapd  Socket : 
I/ActivityManager(  914): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=4594 uid=10050 gids={50050}
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  914): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  914): reportInetCondition for net -1, percentage: 0 by  (1357/10029)
V/BluetoothSapService( 3913): Sap Service closeSapService out
V/BluetoothSapService( 3913): ***onDestroyed***
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 4004): Clean 'force_connect' when disconnect
I/wpa_supplicant( 4004): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 4004): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  914): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4004): TDLS: Remove peers on disassociation
D/HTCRequest(  914): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  914): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  914): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  914): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 4004): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb84b8bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4004):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 4004): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 4004): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  914): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4004): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4004): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 4004): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 4004): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 4004): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/PMS     (  914): acquireWL(43217080): PARTIAL_WAKE_LOCK  NetworkStats 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  914): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
D/PMS     (  914): releaseWL(44070d58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/WirelessDisplayService(  914): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  914): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  914): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  914): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  914): interfaceStatusChanged wlan0, false
D/HTCRequest(  914): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  914): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  914): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  914): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/Process (  914): killProcessQuiet, pid=4259
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
D/Tethering(  914): [isWifi] getHotspotEnabled: false
,I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:2
I/ActivityManager(  914): Killing 4259:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4259/10079)
I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  914): startScan Pid: 914 Uid 1000
D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
I/ActivityManager(  914): Recipient 4259
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/BluetoothFtpService:RfcommSocketAcceptThread( 3913): Shutdown
I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 13
D/PMS     (  914): releaseWL(43217080): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3979): Received state change = 13
D/HtcWiFiWidget_WiFiWidgetProvider( 4594): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 4594): updateWidget(context) for widget: 
D/ConnectivityService(  914): mActiveDefaultNetwork: -1
D/ConnectivityService(  914): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  914): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4610 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  914): killProcessQuiet, pid=4190
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  914): Killing 4190:com.android.chrome/u0a96 (adj 15): empty #17
,D/Process (  914): killProcessQuiet, pid=4273
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  914): Killing 4273:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 4190
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/bt-btif ( 3913): ag scb idx 1 not allocated
,W/bt-btif ( 3913): ag scb idx 2 not allocated
E/bt-btif ( 3913): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3913): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3913): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3913): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3913): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3913): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3913): L2CAP - PSM: 0x0017 not found for deregistration
,V/Settings:HtcSettingsApplication( 4610): [4610/4610] onCreate()
,D/WifiService(  914): New client listening to asynchronous messages
,E/bt_userial_mct( 3913): userial_close userial_thread_created userial_running is 1 
,E/wpa_supplicant( 4004): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 4004): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 4004): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  914): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  914): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,I/ActivityManager(  914): Recipient 4273
,D/Process (  914): killProcessQuiet, pid=4359
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1357): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  914): Killing 4359:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  914): Recipient 4359
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 4004): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 4004): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 4004): nl80211: Unsubscribe mgmt frames handle 0xb84b9718 (mode change)
I/wpa_supplicant( 4004): htc_wext_command_deinit +
I/wpa_supplicant( 4004): htc_wext_command_deinit -
E/wpa_supplicant( 4004): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 4004): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4004): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 4004): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 4004): TDLS: Tear down peers
I/wpa_supplicant( 4004): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4004): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4004): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4004): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 4004): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4004): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4004): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 4004): send_and_recv error 0 - cmd 18
,E/WifiStateMachine(  914): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  914): interfaceLinkStateChanged wlan0, false
D/Tethering(  914): interfaceStatusChanged wlan0, false
,D/Tethering(  914): [isWifi] getHotspotEnabled: false,
,E/WifiStateMachine(  914): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  914): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  914): [wpa_ctrl_close] ctrl=0x62d25068
I/wpa_ctrl(  914): [wpa_ctrl_close] ctrl=0x62d40d18
,W/WifiHW  (  914): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  914): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  914): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  914): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  914):    returned false
,D/WifiStateMachine(  914): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 4411): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/IntentController( 1110): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  914): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  914): WIFI Trun OFF
,D/WirelessDisplayService(  914): getDiscoveryDongleList
D/WIFI_ICON( 1110): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  914): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  914): Exit handleNetworkDisconnect
,E/WifiStateMachine(  914): [MLHD] Error! unhandled message 6 { when=-129ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  914): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  914): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,W/Settings( 1201): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HtcWiFiWidget_WiFiWidgetProvider( 4594): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 4594): updateWidget(context) for widget: 
D/PMS     (  914): acquireWL(432740d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 914 1000 null
D/WifiStateTracker(  914): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1110): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1110): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1110): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3286): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3286): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1110): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,I/QuickSettingWifi( 1110): receive.wifiConnect:false wifiAPname:null elapse:1
,I/bt-btif ( 3913): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 3913): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3913): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3913): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1223): Proxy object disconnected
D/BluetoothHeadset( 1223): Proxy object disconnected
D/BluetoothPhoneService( 1223): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 3286): Proxy object disconnected
D/HeadsetProfile( 3286): Bluetooth service disconnected
D/BluetoothHeadset( 1110): Proxy object disconnected
I/QuickSettingMiniLite( 1110): btListener.disconnect:HEADSET
D/BluetoothHeadset(  914): Proxy object disconnected
D/A2dpService( 3913): Received stop request...Stopping profile...
D/A2dpStateMachine( 3913): doQuit
,D/A2dpStateMachine( 3913): Exit Disconnected: -1
,D/BluetoothA2dp(  914): Proxy object disconnected
D/BluetoothA2dp( 3286): Proxy object disconnected
,D/A2dpProfile( 3286): Bluetooth service disconnected
,D/HidService( 3913): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 3286): Proxy object disconnected
,D/HidProfile( 3286): Bluetooth service disconnected
,D/HealthService( 3913): Received stop request...Stopping profile...
D/PanService( 3913): Received stop request...Stopping profile...
D/PanService( 3913): stop
,D/PanService( 3913): stop: mTetherAc send disconnect
,D/BluetoothTethering(  914): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  914): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  914): attempted to stop reverse tether with nothing tethered
D/BluetoothPan( 3286): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3286): Bluetooth service disconnected
D/BluetoothAdapterService( 3913): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 3913): handleDebugAction() action=null
D/BluetoothPan(  914): BluetoothPAN Proxy object disconnected
D/BtGatt.GattService( 3913): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3913): stop()
W/BluetoothHeadsetServiceJni( 3913): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3913): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3913): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 3913): cleanup
,D/Avrcp   ( 3913): Unregistering previous receiver
,D/BluetoothAdapterService( 3913): Profile still running: com.android.bluetooth.hdp.HealthService
,W/BluetoothHidServiceJni( 3913): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 3913): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3913): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3913): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 3913): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3913): Cleaning up Bluetooth Health object
D/PanService( 3913): CMD_CHANNEL_DISCONNECTED
D/PanService( 3913): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 3913): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 3913): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3913): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 3913): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3913): Setting state to 10
I/BluetoothAdapterState( 3913): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3913): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  914): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  914): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 3913): Entering OffState
,D/BluetoothManagerService(  914): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  914): Broadcasting onBluetoothStateChange(false) to 13 receivers.
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1110): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  914): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  914): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3286): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3286): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3286): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3286): onBluetoothStateChange: up=false
,D/BluetoothMap( 3286): onBluetoothStateChange: up=false
,E/BluetoothMap( 3286): 
E/BluetoothMap( 3286): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41d06138
E/BluetoothMap( 3286): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3286): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3286): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3286): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3286): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3286): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3286): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothSap( 3286): onBluetoothStateChange on: false
,D/BluetoothManagerService(  914): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  914): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothAdapter( 1110): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41f2a918
D/BluetoothAdapter( 1110): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1223): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bc3918
,D/BluetoothAdapter( 1223): onBluetoothServiceDown: done
,D/BluetoothAdapter(  914): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42585a88
D/BluetoothAdapter(  914): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3913): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b69e48
D/BluetoothDevice( 3913): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 3913): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1236): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c840e8
,D/BluetoothAdapter( 1236): onBluetoothServiceDown: done
D/BluetoothAdapter( 1201): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ec6320
D/BluetoothAdapter( 1201): onBluetoothServiceDown: done
D/BluetoothAdapter( 3979): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b79558
,D/BluetoothAdapter( 3979): onBluetoothServiceDown: done
D/BluetoothAdapter( 3864): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42693028
,D/BluetoothAdapter( 3864): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3286): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cf0228
,D/BluetoothAdapter( 3286): onBluetoothServiceDown: done
,D/BluetoothManagerService(  914): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42585a88 mBinding = false
,D/BluetoothManagerService(  914): Sending unbind request.
,D/BluetoothManagerService(  914): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 3913): Cleaning up adapter native....
I/bt-btif ( 3913): HAL bt_hal_cbacks->thread_evt_cb
,I/IntentController( 1110): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/LocalBluetoothProfileManager( 3286): setBluetoothStateOff
D/HtcTagManager( 3286): stopProxy
,D/BluetoothAdapter( 1201): 1105770072: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  914): releaseWL(426890d8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PMS     (  914): acquireWL(435fde10): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1201 10029 null
D/NfcHandover( 1236): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/BluetoothAdapter( 1201): 1105770072: getState() :  mService = null. Returning STATE_OFF
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 3979): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b78c88
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 3979): deinitLeServices: null
D/BluetoothAdapterService( 3913): Done cleaning up adapter native....
D/BluetoothAdapterService(1102475992)( 3913): ****onDestroy()********
D/BtGatt.GattService( 3913): cleanup()
W/bt-btif ( 3913): GATTC Module not enabled/already disabled
,W/bt-btif ( 3913): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 3913): onDestroy: mIsEmailEnabled: true
,D/PMS     (  914): releaseWL(435fde10): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
W/BluetoothHeadset( 1110): Proxy not attached to service
I/QuickSettingMiniLite( 1110): updateLiteState:no connect device!
,D/TetherPref( 3286): persistRestoreBluetoothState false
D/PMS     (  914): acquireWL(43628d28): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3286 1000 null
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 4580): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 4580): updateWidget(context) for widget: 
,D/DockEventReceiver( 3286): finishStartingService: stopping service
D/PMS     (  914): releaseWL(43628d28): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  914): acquireWL(4275ba48): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3286 1000 null
,D/BluetoothMasReceiver( 3913): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 3979): Received state change = 10
D/PMS     (  914): releaseWL(4275ba48): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 1110): 1105207064: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1110): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  914): java.lang.Throwable: stack dump
W/System.err(  914): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  914): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,D/BluetoothManagerService(  914): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425cc4c8:true
W/System.err(  914): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  914): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  914): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4610): new LocationAgent instance!!
,D/HtcTagManager( 4610): HtcTagManager construction complete
,D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4610): BluetoothInputDevice()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4610): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4610): Bluetooth service connected
W/BluetoothInputDevice( 4610): Proxy not attached to service
,D/BluetoothManagerService(  914): Registered receivers: 14
,D/BluetoothPan( 4610): BluetoothPan()
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4610): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 4610): Bluetooth service connected
,D/BluetoothManagerService(  914): Registered receivers: 15
,D/BluetoothMap( 4610): Create BluetoothMap proxy object
D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 16
,E/BluetoothMap( 4610): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothSap( 4610): BluetoothSap() call bindService
,D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 17
,D/BluetoothPbap( 4610): BluetoothPbap()
,D/BluetoothManagerService(  914): registerStateChangeCallback+
D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4610): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4610): Bluetooth service connected
D/LocalBluetoothProfileManager( 4610): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4610): 1102464824: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4610): setBluetoothStateOff
D/HtcTagManager( 4610): stopProxy
W/BluetoothEventManager( 4610): unregister mProfileBroadcastReceiver fail
D/BluetoothManagerService(  914): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  914): Registered receivers: 18
,D/Process (  914): killProcessQuiet, pid=4164
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/ContextImpl( 4610): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,I/ActivityManager(  914): Killing 4164:com.google.android.music:main/u0a154 (adj 15): empty #17
D/AuthorizationBluetoothService( 1357): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  914): Recipient 4164
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  914): Client com.google.android.music (pid 4164): Died!
,D/ConnectivityService(  914): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  914): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  914): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  914): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4628 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by  (914/1000)
D/GpsLocationProvider(  914): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  914): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/Tethering(  914): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  914): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  914): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  914): bSetPropertyMultiRAB:false
D/PMS     (  914): acquireWL(435b8af8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 914 1000 null
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/Tethering(  914): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  914): DelayedCaptiveCheckState
D/CaptivePortalTracker(  914): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/ConnectivityHelper( 1251): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  914): NoActiveNetworkState
I/Tethering(  914): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  914): ipv4Default null
I/Tethering(  914): No IPv4 upstream interface, giving up.
,D/Tethering(  914): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  914): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/PMS     (  914): releaseWL(435b8af8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.backuptransport (1536/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.htc.launcher (1251/10076)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1201/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.facebook.katana (4212/10027)
,W/Netd    (  362): No subsystem found in netlink event
D/NetlinkEvent(  362): Unexpected netlink message. type=0x11
,V/Tethering(  914): remove iface:wlan0
D/Tethering(  914): interfaceRemoved wlan0
,E/Tethering(  914): attempting to remove unknown iface (wlan0), ignoring
,I/MusicStore( 4628): Database version: 95
,W/ContextImpl( 4628): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4628): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4628): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4628): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4628): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4628, uid=10154, userID:0
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,D/MediaRouterService(  914): Client com.google.android.music (pid 4628): Registered
,D/WifiDisplayAdapter(  914): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  914):     Client/Owner: Client
D/WifiDisplayAdapter(  914):     GroupId: 
D/WifiDisplayAdapter(  914):     Passphrase: 
D/WifiDisplayAdapter(  914):     SessionId: 0
D/WifiDisplayAdapter(  914):     IP Address: }
,I/MediaRouter( 4628): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.music (4628/10154)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (2151/10021)
,D/AutoSetting( 4134): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MediaRouter( 4628): getSelectedRoute
,I/ActivityManager(  914): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4651 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (4134/10055)
,D/ConnectivityService(  914): getNetworkInfo networkType=1 called by com.google.android.music (4628/10154)
,D/AutoSetting( 4134): Util - no network available!
,I/NetworkMonitor( 4628): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.htc.sense.hsp (4134/10055)
D/AutoSetting( 4134): service - onCreate()
D/Tethering(  914): interfaceLinkStateChanged p2p0, false
D/Tethering(  914): interfaceStatusChanged p2p0, false
D/Tethering(  914): [isWifi] getHotspotEnabled: false
D/AutoSetting( 4134): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4134): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  914): request 42276e80 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  914): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4134): service - mHandler: cancel location update
,D/AutoSetting( 4134): service -           changes count: 0
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4628, uid=10154, userID:0
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/PMS     (  914): acquireWL(4378dac8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 914 1000 null
,D/PMS     (  914): releaseWL(4378dac8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/MobileConnectivityChangeReceiver( 4651): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4651): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4651): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4651): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  914): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4667 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
,D/Process (  914): killProcessQuiet, pid=4343
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  914): Killing 4343:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.setupwizard (4651/10079)
,W/Netd    (  362): No subsystem found in netlink event
D/NetlinkEvent(  362): Unexpected netlink message. type=0x11
,V/Tethering(  914): remove iface:p2p0
,D/Tethering(  914): interfaceRemoved p2p0
,E/Tethering(  914): attempting to remove unknown iface (p2p0), ignoring
,I/ActivityManager(  914): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4680 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  914): killProcessQuiet, pid=4411
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  914): Killing 4411:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4680): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  914): Recipient 4343
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4680): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4680): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4680): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4680): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  914): Recipient 4411
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4680/10151)
,V/WebViewChromiumFactoryProvider( 4680): Binding Chromium to main looper Looper (main, tid 1) {41b56138}
,I/LibraryLoader( 4680): Expected native library version number "",actual native library version number ""
,I/chromium( 4680): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4680): Initializing chromium process, renderers=0
,D/PMS     (  914): acquireWL(434510e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/PMS     (  914): acquireWL(4308d210): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4680): BLUETOOTH permission is missing!
D/PMS     (  914): releaseWL(434510e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4680): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4680): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4680): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4680): Local Branch: 
I/Adreno-EGL( 4680): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4680): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4680):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4680): Starting up...
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4680/10151)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.magazines (4680/10151)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.apps.plus (4312/10160)
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/iu.Environment( 1965): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/iu.UploadsManager( 1965): num queued entries: 0
,I/iu.UploadsManager( 1965): num updated entries: 0
,I/iu.SyncManager( 1965): NEXT; no task
,D/Process (  914): killProcessQuiet, pid=4461
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
I/ActivityManager(  914): Killing 4461:com.android.vending/u0a74 (adj 15): empty #17
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,D/ConnectivityService(  914): getActiveNetworkInfo called by  (1357/10029)
,I/ActivityManager(  914): Recipient 4461
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  914): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  914): [MLHD] Error! unhandled message 1 { when=-1s937ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  914): releaseWL(432740d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/PMS     (  914): releaseWL(4308d210): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiP2pService(  914): P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  914): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  914): startScan Pid: 914 Uid 1000
,D/PMS     (  914): acquireWL(426a1328): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4628 10154 null
,W/ContextImpl( 4628): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  914):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4628, uid=10154, userID:0
,I/MusicLeanback( 4628): Conditions not met for autocaching.
,I/MusicLeanback( 4628): Stop autocaching.
,D/PMS     (  914): releaseWL(426a1328): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4628): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GAV2    ( 4680): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  914): startScan Pid: 914 Uid 1000
,I/ActivityManager(  914): Waited long enough for: ServiceRecord{440f8d70 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  914): acquireWL(42ae5ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): releaseWL(42ae5ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): runPSCheck
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WirelessDisplayService(  914): HANDLE_WIFI_DIS
,D/WirelessDisplayService(  914): HANDLE_STOP_DIS
,D/WirelessDisplayService(  914): clearDongleCache: Wivulist is already empty
,D/WirelessDisplayService(  914): HANDLE_CHANGE_STATE previousState = 1, state=1 err=-1
D/ConnectivityService(  914): getActiveNetworkInfo called by  (914/1000)
,D/AutoSetting( 4134): service - handleMessage() stop self
,D/AutoSetting( 4134): service - handleMessage() quit looper
,D/AutoSetting( 4134): service - onDestroy() END
,D/Process (  914): killProcessQuiet, pid=4434
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4434:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 4434
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(42452d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=419018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42452d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(44138cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(44138cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): releaseWL(440ed960): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  914): NetTransition Wakelock for ConnectedState released by timeout
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  914): acquireWL(4412a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=479018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4412a850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4346f9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4346f9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  914): acquireWL(42c24728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=539019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42c24728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4266cd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4266cd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(43855a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=599019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43855a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(44215010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(44215010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1223): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1223): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1223): sku_id=99
,D/ContactMessageStore( 1223): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1223): start background delete task...
D/ContactMessageStore( 1223): size: 0 , 0
,D/ContactMessageStore( 1223): Background delete complete
,D/PMS     (  914): acquireWL(4362f4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=659018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4362f4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4322e460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4322e460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(43689ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=719018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43689ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(426973c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(426973c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(42668748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=779018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(42668748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(42ac4770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(42ac4770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(440c4250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=839019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(440c4250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(426baee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(426baee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(43773d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=899019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43773d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4373e310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4373e310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(4268fb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=959018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4268fb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(440f7b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(440f7b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(43511068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,D/ConnectivityService(  914): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  914): sending alarm PendingIntent{41de2758: PendingIntentRecord{424defd0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786314, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{41fa7cf0: PendingIntentRecord{42672ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449684453983, Int=900000
,D/ConnectivityService(  914): Done.
,D/ConnectivityService(  914): Setting timer for 720seconds
,I/ActivityManager(  914): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4727 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  914): sending alarm PendingIntent{423e98f8: PendingIntentRecord{437a1968 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449684528576, Int=0
,W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4727): call getInstance()
,D/PMS     (  914): acquireWL(434512e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4727 1000 null
,D/SmartSyncUtils( 4727): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4727): MY_DEBUG = false
D/PMS     (  914): releaseWL(43511068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/PMS     (  914): releaseWL(434512e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  914): acquireWL(4379d440): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4727 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4727): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4727): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4727): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4727): SettingOnTime = 1449727200000, randomSettingOnTime = 1449724188000
,D/SmartSyncScreenOnOffTimeReceiver( 4727): SettingOffTime = 1449712800000, randomSettingOffTime = 1449716985000
,D/SmartSyncScreenOnOffTimeReceiver( 4727): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4727): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4727): bNightModeTurnOffOnce = false
,D/PMS     (  914): releaseWL(4379d440): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/Process (  914): killProcessQuiet, pid=4543
,D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  914): Killing 4543:com.htc.aurora/u0a49 (adj 15): empty #17
,I/ActivityManager(  914): Recipient 4543
,I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  914): acquireWL(43c73250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1019019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43c73250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4315f6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4315f6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(42c65b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): releaseWL(42c65b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(43681530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1079018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43681530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4275bdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4275bdf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(440d2e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1139018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(440d2e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43735da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43735da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(43795af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1199018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(43795af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4377f020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4377f020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  914): acquireWL(4299ac40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1259018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4299ac40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(440ec640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(440ec640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(427408a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1319019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(427408a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4268a240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4268a240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(440ea790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1379018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(440ea790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(434608c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(434608c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(426a2bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1439018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(426a2bb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(4275e758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(4275e758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(432c85e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1499018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(432c85e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43196110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43196110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(424b3668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): releaseWL(424b3668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(4412f058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1559019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(4412f058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(42719568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  914): releaseWL(42719568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(43c3e950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43c3e950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(439a8858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1619019, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(439a8858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(434a4b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(434a4b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  914): acquireWL(438308d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1679018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(438308d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43615de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43615de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(429a5768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1739018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(429a5768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  914): acquireWL(43c1d8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(43c1d8f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  914): updateBatteryInfo
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,D/TetherSettings( 3286): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3286): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3286): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3286): Cust_ConnectToPC   : spcsc>false
D/        ( 3286): Cust_ConnectToPC   : IPT>true
,D/        ( 3286): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3286): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3286): Index of the first 1 = 3
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3286): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3286): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3286): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3286): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3286): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3286): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(441391a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(441391a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
,I/HtcPowerSaver(  914): >> updateStatus
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  914): acquireWL(440e5d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1799018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(440e5d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/PMS     (  914): acquireWL(440bf040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/PMS     (  914): releaseWL(440bf040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  914): acquireWL(4370d468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): releaseWL(4370d468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  914): runPSCheck
D/PowerUI ( 1110): closing low battery warning: level=100
D/HtcPowerSaver(  914): Checking...
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  914): >> updateStatus
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  914): Prepared write state in 44ms
,I/ProcessStatsService(  914): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-34-38.bin
,D/PMS     (  914): acquireWL(435fad30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{42301f80: PendingIntentRecord{422b9ec8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1859018, Int=0
,I/IntentController( 1110): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  914): releaseWL(435fad30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  914): Sampling interval elapsed, updating statistics ..
,D/PMS     (  914): acquireWL(4355c1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 914 1000 WorkSource{1000}
,V/AlarmManager(  914): sending alarm PendingIntent{41de2758: PendingIntentRecord{424defd0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1727623, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{42085450: PendingIntentRecord{42614798 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821765, Int=1800000
D/PMS     (  914): acquireWL(42765098): PARTIAL_WAKE_LOCK  NetworkStats 0x1 914 1000 null
,V/AlarmManager(  914): sending alarm PendingIntent{435552f0: PendingIntentRecord{433738f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849769, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{426ac208: PendingIntentRecord{4261b0e8 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1864868, Int=0
,V/AlarmManager(  914): sending alarm PendingIntent{4252ab58: PendingIntentRecord{42659648 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449684576128, Int=1800000
,V/AlarmManager(  914): sending alarm PendingIntent{41fa7cf0: PendingIntentRecord{42672ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449685353983, Int=900000
,D/ConnectivityService(  914): Done.
,D/ConnectivityService(  914): Setting timer for 720seconds
,D/PMS     (  914): releaseWL(42765098): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  914): getAllProviders()=[passive, gps, network]
,D/PMS     (  914): acquireWL(426bc918): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,D/ConnectivityService(  914): getActiveNetworkInfo called by com.google.android.gms (1965/10029)
,I/ActivityManager(  914): Resuming delayed broadcast
,D/PMS     (  914): acquireWL(4266b9f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  914): releaseWL(426bc918): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  914): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,I/EventLogService( 1965): Aggregate from 1449683631875 (log), 1449682776069 (data)
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1357): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/dalvikvm( 1357): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1357): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1357): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1357): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025483
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025623
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025704
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025710
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025713
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360025716
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027155
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360027169
W/AlarmManager(  914): Converted elapesd time is over 1 year! when = 315360029967
I/ActivityManager(  914): Resuming delayed broadcast
D/PMS     (  914): releaseWL(4355c1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  914): releaseWL(4266b9f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1357): [NET] getaddrinfo-,err=8
D/libc    ( 1357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1357): [NET] getaddrinfo-, 1
,D/libc    ( 1357): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =2223 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/libc    (  362): [NET]Querying server xid =2223 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  362): [NET]res_nsend:ECONNREFUSED
D/libc    (  362): [NET] -----res_nsend exit-1: xid=2223, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  362): [NET]res_queryN: exit 2
D/libc    (  362): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  362): [NET] getaddrinfo-,err=7
,D/libc    ( 1357): [NET] getaddrinfo_proxy-
,E/Auth    ( 1357): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:-200118834>, App: com.google.android.gms, Service: oauth2: email
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,W/BatSI   (  914): Couldn't get kernel wake lock stats
,D/PMS     (  914): acquireWL(440c41f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  914): n_update end
,I/IntentController( 1110): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  914): BroadcastReceiver::onReceive+
,D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1524): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  914): onReceive BATTERY_CHANGED
D/DotMatrix( 1524): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  914):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  914): BroadcastReceiver::onReceive-
D/PMS     (  914): releaseWL(440c41f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1110): closing low battery warning: level=100
D/PowerUI ( 1110): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  914): updateBatteryInfo
D/PMS     (  914): runPSCheck
D/HtcPowerSaver(  914): Checking...
I/HtcPowerSaver(  914): >> updateStatus
,I/HtcPowerSaver(  914): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  914): << updateStatus
,I/BatteryController( 1110): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4772): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4772): ====startRecUseTime====
D/htc.customization.log.level( 4772):  is 
W/CustomizationLogLevel( 4772): Level value is invalid, use default level 2
D/CustomizationManager( 4772):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4772): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4772): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4772): Parsing tag category name = system
I/CustomizationCIDLoader( 4772): Parsing tag category name = application
I/CustomizationCIDLoader( 4772): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4772): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4772): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4772): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4772): Parsing tag category name = Settings
D/CustomizationManager( 4772):  Read CID file spent 0.131 (s)
D/CustomizationManager( 4772):  All configurations done spent 0.131 (s)
W/HtcNativeFlag( 4772): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4772): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4772): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4772): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  914): deletePackageAsUser: pkg=com.test.thalitest, pid=4772, uid=2000 user=0
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  914): killProcessQuiet, pid=3864
D/Process (  914): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  914): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  914): Killing 3864:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  914):   Force finishing activity ActivityRecord{4379d5d0 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  914): Copying FileAsset 0x7072cc48 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  914): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  914): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  914): Got RemoteException sending setActive(false) notification to pid 3864 uid 10389
E/JavaBinder( 1187): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  914): Skipping PackageSetting{421d4ed0 com.example.hello/10396} due to missing metadata
I/ActivityManager(  914): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1524): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1524): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
D/PMS     (  914): acquireWL(44042ec0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
W/SystemReader( 1236): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  914): WIN DEATH: Window{4253e1d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  914): Client connection lost with reason: 4
D/PMS     (  914): releaseWL(44042ec0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SQLiteConnectionPool( 1965): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1279): Cleaning up data for package: com.test.thalitest
I/Launcher( 1251): Deferring update until onResume
D/Launcher( 1251): waitUntilResume // bindAppsRemoved
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/[PluginManager]RegisterService( 4134): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4134): handle notify Blinkfeed plugin client changed
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mms"
D/Prism.PackageStateRece_( 1251): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/IcingCorporaProvider( 2571): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
E/ExternalAccountType( 1321): Unsupported attribute readOnly
I/ActivityManager(  914): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4788 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/Choreographer(  914): Skipped 32 frames!  The application may be doing too much work on its main thread.
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/InputMethodManagerService(  914): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "sms"
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "smsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mms"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
I/PackageManager(  914):   Action: "android.intent.action.SENDTO"
I/PackageManager(  914):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  914):   Scheme: "mmsto"
I/PackageManager(  914): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1223 :
D/PhoneApp( 1223): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  914): acquireWL(43ce7c28): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): releaseWL(43ce7c28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  914): acquireWL(43ce12f0): PARTIAL_WAKE_LOCK  Icing 0x1 1965 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2571): UpdateCorporaTask done [took 676 ms] updated apps [took 676 ms] 
E/SQLiteDatabase( 4788): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4788): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4788): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4788): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4788): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4788): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4788): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4788): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4788): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4788): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4788): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4788): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4788): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4788): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4788): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4788): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4788): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4788): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4788): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4788): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4788): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4788): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4788): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4788): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4788): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4788): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4788): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4788): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4788): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4788): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4788): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4788): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4788): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4788): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4788): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4788): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4788): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4788): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4788): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4788): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4788): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4788): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4788): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4788): threadid=11: thread exiting with uncaught exception (group=0x41721e30)
E/AndroidRuntime( 4788): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4788): Process: com.google.android.apps.docs, PID: 4788
E/AndroidRuntime( 4788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4788): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4788): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4788): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4788): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4788): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  914): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  914): Can't write: system_app_crash
E/DropBoxManagerService(  914): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  914): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  914): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  914): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  914): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  914): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  914): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  914): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  914): 	... 5 more
I/ActivityManager(  914): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4806 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4788): killProcess, pid=4788
D/Process ( 4788): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  914): Recipient 4788
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Process com.google.android.apps.docs (pid 4788) has died.
W/ContextImpl( 4806): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  914): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4819 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4806): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4806): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4806): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4806): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4806): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4806): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4806): threadid=10: thread exiting with uncaught exception (group=0x41721e30)
E/AndroidRuntime( 4806): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4806): Process: com.android.keychain, PID: 4806
E/AndroidRuntime( 4806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4806): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4806): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4806): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4806): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4806): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  914): App crashed! Process: com.android.keychain
D/ErrorReport(  914): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4819): getInstance(Context context)
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1251): loadItems() com.htc.launcher.pageview.WidgetManager@41be3eb0 +
I/Prism.WidgetManager( 1251): onLoadItems() +
D/Process ( 4806): killProcess, pid=4806
D/Process ( 4806): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4819): getInstance(Context context)
D/AppTag  ( 4819): onCreate()
I/ActivityManager(  914): Recipient 4806
I/DisplayManagerService(  914): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  914): Process com.android.keychain (pid 4806) has died.
E/ErrorReport(  914): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  914): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449685434090.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  914): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  914): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  914): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  914): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  914): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  914): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  914): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  914): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  914): 	... 4 more
W/ActivityManager(  914): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  914): acquireWL(426a9f98): PARTIAL_WAKE_LOCK  AsyncService 0x1 4312 10160 null
D/PMS     (  914): releaseWL(426a9f98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  914): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4837 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
W/PackageManager(  914): Unable to load service info ResolveInfo{41daa448 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  914): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  914): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  914): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  914): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  914): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  914): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  914): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  914): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  914): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  914): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  914): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4837): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/Icing   ( 1965): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
I/PackageManager(  914):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4837, uid=10074, userID:0
D/Finsky  ( 4837): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4837/10074)
E/Icing   ( 1965): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1965): Could not init tag ds.tag.deleted
I/Icing   ( 1965): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
W/dalvikvm( 4837): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 4837): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
E/Icing   ( 1965): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1965): Writing status failed
E/Icing   ( 1965): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
D/PMS     (  914): releaseWL(43ce12f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  914): getAllNetworkInfo called by com.android.vending (4837/10074)

```
