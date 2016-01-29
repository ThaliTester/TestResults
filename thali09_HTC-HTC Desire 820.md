#### Test 5761781115ba656_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,E/cutils-trace( 3882): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3882): ====startRecUseTime====
D/htc.customization.log.level( 3882):  is 
W/CustomizationLogLevel( 3882): Level value is invalid, use default level 2
D/CustomizationManager( 3882):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3882): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3882): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3882): Parsing tag category name = system
I/CustomizationCIDLoader( 3882): Parsing tag category name = application
I/CustomizationCIDLoader( 3882): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3882): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3882): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3882): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3882): Parsing tag category name = Settings
D/CustomizationManager( 3882):  Read CID file spent 0.100 (s)
D/CustomizationManager( 3882):  All configurations done spent 0.100 (s)
W/HtcNativeFlag( 3882): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3882): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3882): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3882): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3882
D/PMS     (  906): acquireHCC(42e09418): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4357b160): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1138122688
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ddaa90
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
D/PMS     (  906): acquireWL(425fa3a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3893 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1247): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3893): Binding Chromium to main looper Looper (main, tid 1) {41b67a90}
I/LibraryLoader( 3893): Expected native library version number "",actual native library version number ""
I/chromium( 3893): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3893): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42cec3e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(43584280): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42eb2638:true
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3893): 1102569624: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): releaseWL(42cec3e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3893): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3893): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3893): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3893): Local Branch: 
I/Adreno-EGL( 3893): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3893): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3893):                  aa63bbd948f41d15fc72f585e
W/chromium( 3893): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3893): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3893): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3893): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3893): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3893): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3893): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3893): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3893): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3893): CordovaWebView is running on device made by: HTC
,W/AwContents( 3893): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1247
W/ResourceType( 3893): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3893): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41baf620, mServedView=org.apache.cordova.engine.SystemWebView{41b753b0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1188): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1188): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=3893
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +290ms
W/AwContents( 3893): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(425fa3a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 3893): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3893): JniHelper::setJavaVM(0x41641048), pthread_self() = 1662664192
I/chromium( 3893): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/HtcModeClient( 1485): handler message = 4011
E/HtcModeClient( 1485): Check connection and retry 11 times.
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 11.228MB for 323830-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 11.435MB for 485740-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 11.838MB for 728606-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 12.435MB for 1092904-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 13.286MB for 1639352-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 14.714MB for 2459024-byte allocation
,I/dalvikvm-heap( 3893): Grow heap (frag case) to 15.407MB for 2287544-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42e09418): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/jxcore-log( 3893): Initializing JXcore engine
,W/jxcore-log( 3893): JXcore engine is ready,
D/PMS     (  906): releaseHCC(4357b160): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 3893): Starting JXcore engine
,W/jxcore-log( 3893): Platform android
W/jxcore-log( 3893): 
,W/jxcore-log( 3893): Process ARCH arm
W/jxcore-log( 3893): 
,I/jxcore-log( 3893): JXcore Cordova bridge is ready!
I/jxcore-log( 3893): 
,W/jxcore-log( 3893): JXcore engine is started
,I/jxcore-log( 3893): Toggling radios to true
I/jxcore-log( 3893): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  906): checking for enable restriction...
D/BluetoothManagerService(  906): checkBTEasState, ret=true
,I/BluetoothManagerService(  906): isBluetoothRestricted(): false
D/BluetoothManagerService(  906): enable(): region ID = 6
D/BluetoothManagerService(  906): enable():  mBluetooth =null mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 1
W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1263
W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:556)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  906): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 3893): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1259
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183),
W/System.err(  906): ,	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	,at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 2(ms)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=3893, uid=10389
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/ActivityManager(  906): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3939 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
,D/WifiManager( 3893): disconnect: Base Package Name=com.test.thalitest, uid=10389,
,D/WifiManager( 3893): reconnect: Base Package Name=com.test.thalitest, uid=10389
,D/PMS     (  906): acquireWL(42f89c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
I/jxcore-log( 3893): Radios toggled
I/jxcore-log( 3893): 
I/jxcore-log( 3893): My device name is: HTC-HTC Desire 820
I/jxcore-log( 3893): 
,D/AdapterServiceConfig( 3939): Adding HeadsetService
D/AdapterServiceConfig( 3939): Adding A2dpService
D/AdapterServiceConfig( 3939): Adding HidService
D/AdapterServiceConfig( 3939): Adding HealthService
D/AdapterServiceConfig( 3939): Adding PanService
,D/AdapterServiceConfig( 3939): Adding GattService
,W/linker  ( 3939): libbt-aptx-4.0.3.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/BluetoothAdapterService( 3939): REFCOUNT: CREATED. INSTANCE_COUNT1
W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c6d48:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothAdapterState( 3939): make
,I/BluetoothAdapterState( 3939): Entering OffState
,I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3939): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:1 len:14
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  906): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapter( 1202): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41e8d9f8
D/BluetoothAdapter( 1202): onBluetoothServiceUp done
,D/BluetoothAdapter( 1234): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c9be10
,D/BluetoothAdapter( 1234): onBluetoothServiceUp done
,D/BluetoothAdapter( 1218): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41c80198
,D/BluetoothAdapter( 1218): onBluetoothServiceUp done
,D/BluetoothAdapter( 3893): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f2d2f8
,D/BluetoothAdapter( 3893): onBluetoothServiceUp done
,D/BluetoothAdapter( 1111): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@41f52898,
,D/BluetoothAdapter( 1111): onBluetoothServiceUp done
D/BluetoothAdapter(  906): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@43d55270
D/BluetoothAdapter(  906): onBluetoothServiceUp done
D/BluetoothAdapter( 3939): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b80f80
D/BluetoothAdapter( 3939): onBluetoothServiceUp done
,D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 3939): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3939): Setting state to 11
I/BluetoothAdapterState( 3939): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3939): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3939): make
I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/BluetoothBondStateMachine( 3939): StableState(): Entering Off State
D/HeadsetService( 3939): Received start request. Starting profile...
D/HeadsetStateMachine( 3939): Version 1.6
,D/HeadsetStateMachine( 3939): make
D/PMS     (  906): acquireWL(43939be8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1202 10029 null
D/PMS     (  906): releaseWL(43939be8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3965 uid=10040 gids={50040, 3002, 3001}
,I/BluetoothAdapterState( 3939): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/HeadsetStateMachine( 3939): setCurrentDevice, the latest mCurrentDevice is:null
,D/A2dpService( 3939): Received start request. Starting profile...
,V/Avrcp   ( 3939): make
D/Avrcp   ( 3939): fillIntentFilter()
,I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/A2dpStateMachine( 3939): make
,D/A2dpStateMachine( 3939): Enter Disconnected: -2
,D/HidService( 3939): Received start request. Starting profile...
,D/HealthService( 3939): Received start request. Starting profile...
,D/PanService( 3939): Received start request. Starting profile...
,D/BluetoothTethering(  906): supplyMessenger
,D/BluetoothTethering(  906): supplyMessenger mAsyncChannel is null
D/PanService( 3939): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothTethering(  906): got MESSAGE_CONNECT_PANSERVICE, call connect
,D/BluetoothTethering(  906): got CMD_CHANNEL_HALF_CONNECTED
,D/BtGatt.DebugUtils( 3939): handleDebugAction() action=null
D/BtGatt.GattService( 3939): Received start request. Starting profile...
,D/BtGatt.GattService( 3939): start()
,D/HtcBtWidget_BTWidgetProvider( 3965): onBTStateChanged() for widget: 
V/BluetoothPbapService( 3939): Pbap Service onCreate
V/BluetoothPbapService( 3939): Starting PBAP service
,D/HtcBtWidget_BTWidgetProvider( 3965): updateWidget(context) for widget: 
,D/Process (  906): killProcessQuiet, pid=3726
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 11
,D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 11
,I/ActivityManager(  906): Killing 3726:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/BluetoothMasService( 3939): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 3939): Add permission for SmsProvider.
V/BluetoothMasService( 3939): Starting MAS instances
,I/ActivityManager(  906): Recipient 3726
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Tethering(  906): interfaceAdded wlan0
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): wlan0 is not a tetherable iface, ignoring
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): interfaceAdded p2p0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/Tethering(  906): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/PMS     (  906): releaseWL(42f89c50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 11
,I/MailMessageReceiver( 3939): reg:com.android.bluetooth.btservice.AdapterApp@41b744e8 with com.htc.util.mail.MailMessageReceiver@41bb4830
I/MailManager( 3939): MailManager contruct! com.htc.util.mail.MailMessageReceiver@41bb4830
,V/EmailUtils( 3939): Manager Instance is not NULL
D/PMS     (  906): releaseWL(43584280): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3985 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/WifiMonitor(  906): startMonitoring(wlan0) with mConnected = false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/ActivityManager(  906): Start proc com.htc.widget.process2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=3999 uid=10050 gids={50050}
,I/wpa_supplicant( 3998): wpa_supplicant v2.1-devel-htc-1.66
D/wpa_supplicant( 3998): Add randomness: count=1 entropy=0
D/wpa_supplicant( 3998): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3998): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 3998): Get randomness: len=20 entropy=1
D/wpa_supplicant( 3998): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 3998): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 3998): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 3998): Successfully initialized wpa_supplicant
I/wpa_supplicant( 3998): NetworkSelection(WPA_SUPPLICANT) version: 1.q.2
D/wpa_supplicant( 3998): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3998): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3998): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3998): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3998): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3998): update_config=1
D/wpa_supplicant( 3998): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3998): device_name='Android_1950'
D/wpa_supplicant( 3998): manufacturer='HTC'
D/wpa_supplicant( 3998): model_name='HTC_PHONE'
D/wpa_supplicant( 3998): model_number='1234'
D/wpa_supplicant( 3998): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3998): p2p_oper_reg_class=126
D/wpa_supplicant( 3998): p2p_oper_channel=36
D/wpa_supplicant( 3998): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 3998): persistent_reconnect=1
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 3
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 3
I/wpa_supplicant( 3998): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 3998): nl80211: RFKILL status not available
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3998): nl80211: Using driver-based roaming
D/wpa_supplicant( 3998): nl80211: TDLS supported
D/wpa_supplicant( 3998): nl80211: TDLS external setup
D/wpa_supplicant( 3998): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3998): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3998): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3998): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3998): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 3998): nl80211: Set mode ifindex 23 iftype 2 (STATION)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3998): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8ecc758
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Re,gister frame type=0xd0 nl_handle=0xb8ecc758
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3998): htc_wext_command_init +
E/wpa_supplicant( 3998): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 3998): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 3998): nl80211: Use Multi channel concurrency
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3998): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 3998): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3998): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3998): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3998): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_ENABLING setEnable:false enableSAA:false
,D/EmailUtils( 3939): ============NULL aList========
V/EmailUtils( 3939): <-getEmailAccountIdList
V/BluetoothMasService( 3939): onCreate: mIsEmailEnabled: true
,D/HtcWiFiWidget_WiFiWidgetProvider( 3999): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 3999): updateWidget(context) for widget: 
D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 11
V/BluetoothMasService( 3939): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3939): Manager Instance is not NULL
,D/Process (  906): killProcessQuiet, pid=3747
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3747:com.htc.backup/1000 (adj 15): empty #17
,D/EmailUtils( 3939): ============NULL aList========
,V/EmailUtils( 3939): <-getEmailAccountIdList
,V/BluetoothSapService( 3939): Sap Service onCreate
,V/BluetoothSapService( 3939): initBinder
V/BluetoothSapService( 3939): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@41bb9c20
,V/BluetoothSapReceiver( 3939): BluetoothSapReceiver init
D/ConnectivityService(  906): getAllNetworkInfo called by com.test.thalitest (3893/10389)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3747
D/BluetoothSapService( 3939): setSapService()
V/BluetoothSapService( 3939): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3939): state: 12
,D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 11
D/BluetoothAdapterService( 3939): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3939): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3939): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3939): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3939): Profile still not running:com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 3939): Profile still not running:com.android.bluetooth.gatt.GattService
D/PanService( 3939): CMD_CHANNEL_FULL_CONNECTION
D/BluetoothAdapterState( 3939): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/BluetoothTethering(  906): got CMD_CHANNEL_FULLY_CONNECTED
,D/Process (  906): killProcessQuiet, pid=3708
,I/ActivityManager(  906): Killing 3708:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/BluetoothMasReceiver( 3939): Bluetooth STATE CHANGED to 11
,I/qcom-bluetooth( 4017): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  906): Start proc com.htc.bluetooth.le.profiles for broadcast com.htc.bluetooth.le.profiles/.receiver.BluetoothAdapterReceiver: pid=4019 uid=1002 gids={41002, 3003, 5012, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3010}
I/ActivityManager(  906): Recipient 3708
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/qcom-bluetooth( 4035): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/wpa_supplicant( 3998): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 3998):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 3998):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3998):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
I/qcom-bluetooth( 4036): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=23 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): nl80211: Flush PMKIDs
E/wpa_supplicant( 3998): send_and_recv error -22 - cmd 54
,I/wpa_supplicant( 3998): State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 4038): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 4039): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 4040): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4019): Received state change = 11
,I/qcom-bluetooth( 4041): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/WifiService(  906): New client listening to asynchronous messages
,D/Process (  906): killProcessQuiet, pid=3767
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 ,
,I/ActivityManager(  906): Killing 3767:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/AuthorizationBluetoothService( 1351): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/wpa_supplicant( 3998): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3998): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3998): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 3998): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 3998): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 3998): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): Using existing control interface directory.
D/wpa_supplicant( 3998): ctrl_iface bind(PF_UNIX) failed: Address already in use
D/wpa_supplicant( 3998): ctrl_iface exists, but does not allow connections - assuming it was leftover from forced program termination
,D/wpa_supplicant( 3998): Successfully replaced leftover ctrl_iface socket '/data/misc/wifi/sockets/p2p0'
,D/wpa_supplicant( 3998): P2P: Own listen channel: 1
D/wpa_supplicant( 3998): P2P: Configured operating channel: 126:36
,D/wpa_supplicant( 3998): P2P: Add operating class 81
,I/wpa_supplicant( 3998): State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 3998): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3998): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 3998): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3998): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 3998): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 3998): disable_scan_offload=1
D/wpa_supplicant( 3998): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 3998): update_config=1
D/wpa_supplicant( 3998): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 3998): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3998): manufacturer='HTC'
D/wpa_supplicant( 3998): model_name='HTC Desire 820'
D/wpa_supplicant( 3998): model_number='HTC Desire 820'
D/wpa_supplicant( 3998): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 3998): persistent_reconnect=1
D/wpa_supplicant( 3998): p2p_disabled=1,
D/wpa_supplicant( 3998): hs20=1
D/wpa_supplicant( 3998): interworking=1
D/wpa_supplicant( 3998): Line: 18 - start of a new network block
D/wpa_supplicant( 3998): key_mgmt: 0x2
D/wpa_supplicant( 3998): priority=1 (0x1)
,D/wpa_supplicant( 3998): signinfail=0 (0x0),
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3767
,D/wpa_supplicant( 3998): Priority group 1
D/wpa_supplicant( 3998):    id=0 ssid='NG700'
I/wpa_supplicant( 3998): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 3998): nl80211: RFKILL status not available
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
D/wpa_supplicant( 3998): nl80211: Using driver-based roaming
D/wpa_supplicant( 3998): nl80211: TDLS supported
D/wpa_supplicant( 3998): nl80211: TDLS external setup
D/wpa_supplicant( 3998): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 3998): nl80211: Using driver-based off-channel TX
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 3998): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 3998): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 3998): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 3998): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3998): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8edc718
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=1, operstate=5
I/wpa_supplicant( 3998): htc_wext_command_init +
I/wpa_supplicant( 3998): htc_wext_command_init -
I/wpa_supplicant( 3998): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 3998): Don't set 00 to countryID.conf
D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 10
D/wpa_supplicant( 3998): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 3998): nl80211: Use separate P2P group interface
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Regulatory information - country=00
D/wpa_supplicant( 3998): nl80211: 2402-2472 @ 40 MHz,
D/wpa_supplicant( 3998): nl80211: 2457-2482 @ 40 MHz
D/wpa_supplicant( 3998): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 3998): nl80211: 5170-5250 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5250-5330 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5490-5710 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5735-5835 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 57240-63720 @ 2160 MHz
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3998): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,I/qcom-bluetooth( 4045): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 b4:ce:f6:ab:a4:6a 
,I/qcom-bluetooth( 4046): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 3939): btu_task pending for preload complete event
,I/wpa_supplicant( 3998): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 3998):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 3998):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 3998):  Initialization: WAPI:set Staues=1 
,D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 3998): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 3998): nl80211: Flush PMKIDs
,E/wpa_supplicant( 3998): send_and_recv error -22 - cmd 54
,D/wpa_supplicant( 3998): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 3998): TDLS: Driver uses external link setup
,D/wpa_supplicant( 3998): WPS: Set UUID for interface wlan0
D/wpa_supplicant( 3998): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: KEY_RX entering state NO_KEY_RECEIVE,
D/wpa_supplicant( 3998): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 3998): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 3998): Using existing control interface directory.
I/wpa_supplicant( 3998): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3998): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd:124 set country (DE) in /data/misc/wifi/countryID.conf
,D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 10
I/wpa_supplicant( 3998): Auto country group 1: ch36
I/wpa_supplicant( 3998): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3998): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 3998): Get randomness: len=20 entropy=0
D/wpa_supplicant( 3998): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
V/RegulatoryObserver(  906): uevent:
V/RegulatoryObserver(  906): {SUBSYSTEM=platform, DEVPATH=/devices/platform/regulatory.0, SEQNUM=4422, ACTION=change, COUNTRY=DE, MODALIAS=platform:regulatory}
V/RegulatoryObserver(  906): Regulatory Country Code:DE
V/RegulatoryObserver(  906): Start wifi-crda service to run crda.
V/RegulatoryObserver(  906): Country Code is DE
V/RegulatoryObserver(  906): Send broadcast country code message.
I/RegulatoryObserver(  906): Broadcast intent for crda country code: DE
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.RegulatoryObserver$1.handleMessage:131 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:157 com.android.server.ServerThread.initAndLoop:1464 
I/wpa_supplicant( 3998): wpa_supplicant_scan enter
I/wpa_supplicant( 3998): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3998): ap_scan=1 , scan_req =1
I/wpa_supplicant( 3998): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3998): Scan req (ret=0) - timeout 10 secs
I/wpa_supplicant( 3998): Attached_Completed, sun_path=/data/misc/wifi/sockets/wpa_ctrl_906-2
D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 1
D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 3998): nl80211: Event message available
D/wpa_supplicant( 3998): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 3998): nl80211: Regulatory domain change
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3998): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3998): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3998): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3998): P2P: Add operating class 81
D/wpa_supplicant( 3998): P2P: Add operating class 115
D/wpa_supplicant( 3998): P2P: Add operating class 116
D/wpa_supplicant( 3998): P2P: Add operating class 117
D/wpa_supplicant( 3998): P2P: Update channel list
D/wpa_supplicant( 3998): p2p0: Updating hw mode
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 95
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 1
D/wpa_supplicant( 3998): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 3998): nl80211: 2400-2483 @ 40 MHz
D/wpa_supplicant( 3998): nl80211: 5150-5250 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5250-5350 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 5470-5725 @ 80 MHz
D/wpa_supplicant( 3998): nl80211: 57240-65880 @ 2160 MHz
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 31
D/wpa_supplicant( 3998): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 3998): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): set wifi ON
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER MACADDR
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiConfigStore(  906): Loading config and enabling all networks
D/WifiNative-wlan0(  906): doString: LIST_NETWORKS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): list_network_info: ret=0x1, pos=0xb8edf117 b,uf=0xb8edf0e8
I/wpa_supplicant( 3998): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3998): 0	NG700	any	
D/WifiNative-wlan0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  906): 0	NG700	any	
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 bssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'bssid'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 priority
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 scan_ssid
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_tx_keyidx
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wep_key0'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wep_key1'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
I/IntentController( 1111): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wep_key2'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wep_key3
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wep_key3'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 as_cert_file
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='as_cert_file'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'as_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 as_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 user_cert_file
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='user_cert_file'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'user_cert_file'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 user_cert_file" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_key_type
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_key_type"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_key_type'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 3998): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 proto
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='proto'
E/WifiConfigStore(  906): Failed to look-up a string: W
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_mgmt
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 auth_alg
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 pairwise
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 group
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/HtcWiFiWidget_WiFiWidgetProvider( 3999): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 3999): updateWidget(context) for widget: 
E/WifiConfigStore(  906): Failed to look-up a string: _SMS4
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/WIFI_ICON( 1111): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_psk'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_psk_hex
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_psk_hex'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_PSK_HEX key
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT index null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_as_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_as_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT as cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 wapi_user_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'wapi_user_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert" Return -1
D/WifiConfigStore(  906): ***WAPI : readNetworkVariables WAPI_CERT user cert null
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 limited
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 limited"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='limited'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 signinfail
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 signinfail"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='signinfail'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 eap
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'eap'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 phase2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'phase2'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 anonymous_identity
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 password
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'password'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 client_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'client_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 ca_cert
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'ca_cert'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 subject_match
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'subject_match'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 engine_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'engine_id'
,D/ConnectivityService(  906): getAllNetworkInfo called by com.test.thalitest (3893/10389)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 key_id
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'key_id'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id" Return -1
D/WifiNative-wlan0(  906): doString: GET_NETWORK 0 private_key
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 3998): CTRL_IFACE: Failed to get network variable 'private_key'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key" Return -1
E/WifiConfigStore(  906): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiNative-wlan0(  906): doBoolean: SET device_name a51ul_htc_europe
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name a51ul_htc_europe"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'device_name'='a51ul_htc_europe'
D/wpa_supplicant( 3998): device_name='a51ul_htc_europe'
D/wpa_supplicant( 3998): WPS: Set UUID for interface wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET manufacturer HTC
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 3998): manufacturer='HTC'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_name HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC Desire 820"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'model_name'='HTC Desire 820'
D/wpa_supplicant( 3998): model_name='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET model_number HTC Desire 820
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC Desire 820"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'model_number'='HTC Desire 820'
D/wpa_supplicant( 3998): model_number='HTC Desire 820'
D/WifiNative-wlan0(  906):    returned true
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET config_methods physical_display virtual_push_button
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 3998): config_methods='physical_display virtual_push_button'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DISABLE_OFFLOAD
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISABLE_OFFLOAD"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): WiFioffload: DISABLE OFFLOAD to 3G
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE UNINITIALIZED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE UNINITIALIZED"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): WiFioffload: update mobile network = UNINITIALIZED
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET auto_interworking 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET auto_interworking 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'auto_interworking'='0'
D/wpa_supplicant( 3998): auto_interworking=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN_INTERVAL 15
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): wlan0: Setting scan interval: 15 sec
W/Settings( 3627): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXSCAN-STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 15
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =SCANNING
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): SET_SCREEN_ON:On
I/wpa_supplicant( 3998): htc_wext_set_keepalive +
I/wpa_supplicant( 3998): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3998): getPrivFuncNum +	
I/wpa_supplicant( 3998): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SET ps 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 3998): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
W/Settings(  906): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  906): doBoolean: CTRL-DAT-AIR_MODE-0:1
D/libc    (  906): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE: field=AIR_MODE id=0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETBAND 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): SETBAND: 0
D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd: SETBAND 0 
D/wpa_supplicant( 3998): P2P: Add operating class 81
D/wpa_supplicant( 3998): P2P: Add operating class 115
D/wpa_supplicant( 3998): P2P: Add operating class 116
D/wpa_supplicant( 3998): P2P: Add operating class 117
D/wpa_supplicant( 3998): P2P: Update channel list
I/wpa_supplicant( 3998): P2P_OP_CH: wpa_supplicant_htc_set_p2p_op_class_and_ch
I/wpa_supplicant( 3998): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 3998): Get_p2p_auto_channel: Auto country group 1: ch36
D/wpa_supplicant( 3998): CTRL_IFACE SET 'p2p_oper_reg_class'='126'
D/wpa_supplicant( 3998): p2p_oper_reg_class=126
D/wpa_supplicant( 3998): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 3998): P2P: New SSID postfix: -Android_1950
E/wpa_supplicant( 3998): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3998): CTRL_IFACE SET 'p2p_oper_channel'='36'
D/wpa_supplicant( 3998): p2p_oper_channel=36
E/wpa_supplicant( 3998): P2P: Own oper channel update failed: -1
D/wpa_supplicant( 3998): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 3998): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 3998): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/wpa_supplicant( 3998): P2P_OP_CH: save_config, class=126, ch=36
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: BSS_FLUSH 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 3998): wpa_supplicant_scan enter
D/WifiMonitor(  906): startMonitoring(p2p0) with mConnected = true
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET persistent_reconnect 1
I/QuickSettingWifi( 1111): receive.wifiState:WIFI_STATE_ENABLED setEnable:true enableSAA:false
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 3998): persistent_reconnect=1
I/wpa_supplicant( 3998): Recv Cmd 2: SET persistent_reconnect=1
D/WifiNative-p2p0(  906):    returned true
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
D/WifiNative-p2p0(  906): doBoolean: SET device_name Android_1950
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_name Android_1950"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'device_name'='Android_1950'
D/wpa_supplicant( 3998): device_name='Android_1950'
I/wpa_supplicant( 3998): Recv Cmd 2: SET device_name=Android_1950
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET p2p_ssid_postfix -Android_1950
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_1950"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_1950'
D/wpa_supplicant( 3998): p2p_ssid_postfix='-Android_1950'
D/wpa_supplicant( 3998): P2P: New SSID postfix: -Android_1950
I/wpa_supplicant( 3998): Recv Cmd 2: SET p2p_ssid_postfix=-Android_1950
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET device_type 10-0050F204-5
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'device_type'='10-0050F204-5'
I/wpa_supplicant( 3998): Recv Cmd 2: SET device_type=10-0050F204-5
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: SET config_methods virtual_push_button physical_display keypad
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 3998): config_methods='virtual_push_button physical_display keypad'
I/wpa_supplicant( 3998): Recv Cmd 2: SET config_methods=virtual_push_button physical_display keypad
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SET conc_pref sta
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
I/wpa_supplicant( 3998): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 3998): Single channel concurrency preference: sta
I/wpa_supplicant( 3998): Recv Cmd 2: P2P_SET conc_pref
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: STATUS
W/WifiHW  (  906): QCOM Debug wifi_send_command "STATUS"
D/WifiNative-p2p0(  906): doBoolean: P2P_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_FLUSH"
I/wpa_supplicant( 3998): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 3998): P2P: Stopping find
D/wpa_supplicant( 3998): P2P: Clear timeout (state=IDLE)
I/wpa_supplicant( 3998): P2P: State IDLE -> IDLE
I/wpa_supplicant( 3998): Recv Cmd 2: P2P_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: P2P_SERVICE_FLUSH
W/WifiHW  (  906): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
I/wpa_supplicant( 3998): [p2p command] (P2P_SERVICE_FLUSH)
I/wpa_supplicant( 3998): Recv Cmd 2: P2P_SERVICE_FLUSH
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doString: LIST_NETWORKS
W/WifiHW  (  906): QCOM Debug wifi_send_command "LIST_NETWORKS"
I/wpa_supplicant( 3998): list_network_info: ret=0x22, pos=0xb8edf10a buf=0xb8edf0e8
I/wpa_supplicant( 3998): list_network_info: buf=network id / ssid / bssid / flags
I/wpa_supplicant( 3998): Recv Cmd 2: LIST_NETWORKS
D/WifiNative-p2p0(  906):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  906): doBoolean: AP_SCAN 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "AP_SCAN 1"
D/WifiNative-p2p0(  906):    returned false
D/WifiNative-p2p0(  906): doBoolean: SET wifi_display 1
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
D/WifiP2pService(  906): InactiveState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-13ms what=139323 arg2=1 obj=WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  906):  WFD CtrlPort: 7236
D/WifiP2pService(  906):  WFD MaxThroughput: 50 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "SET wifi_display 1"
D/wpa_supplicant( 3998): CTRL_IFACE SET 'wifi_display'='1'
D/wpa_supplicant( 3998): WFD: Wi-Fi Display enabled
D/wpa_supplicant( 3998): WFD: Update WFD IE
I/wpa_supplicant( 3998): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3998): Recv Cmd 2: SET wifi_display
D/WifiNative-p2p0(  906):    returned true
D/WifiNative-p2p0(  906): doBoolean: WFD_SUBELEM_SET 0 000600101c440032
W/WifiHW  (  906): QCOM Debug wifi_send_command "WFD_SUBELEM_SET 0 000600101c440032"
D/wpa_supplicant( 3998): WFD: Set subelement 0
D/wpa_supplicant( 3998): WFD: Update WFD IE
I/wpa_supplicant( 3998): WFD: Update WFD IE - DONE
I/wpa_supplicant( 3998): Recv Cmd 2: WFD_SUBELEM_SET 0
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
,D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 3998): nl80211: Event message available
D/wpa_supplicant( 3998): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3998): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3998): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 3998): nl80211: Survey data missing
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3998): Sorted scan results
I/wpa_supplicant( 3998): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 3998): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 3998): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
D/wpa_supplicant( 3998): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 3998): Add randomness: count=2 entropy=0
D/wpa_supplicant( 3998): Add randomness: count=3 entropy=1
D/wpa_supplicant( 3998): Add randomness: count=4 entropy=2
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 3998): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3998): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3998): wpa_supplicant_pick_network+
I/wpa_supplicant( 3998): Selecting BSS from priority group 1
I/wpa_supplicant( 3998): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3998): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3998): 1: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 3998): 2: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 3998): clear disabled list - type=1
I/wpa_supplicant( 3998): No suitable network found
W/wpa_supplicant( 3998): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 3998): p2p0: Updating scan results from sibling
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3998): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 3998): nl80211: Survey data missing
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3998): Sorted scan results
I/wpa_supplicant( 3998): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 3998): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 3998): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
D/wpa_supplicant( 3998): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 3998): Add randomness: count=5 entropy=3
D/wpa_supplicant( 3998): Add randomness: count=6 entropy=4
D/wpa_supplicant( 3998): Add randomness: count=7 entropy=5
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 3998): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3998): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3998): wpa_supplicant_pick_network+
I/wpa_supplicant( 3998): clear disabled list - type=1
I/wpa_supplicant( 3998): No suitable network found
W/wpa_supplicant( 3998): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 3998): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 3998): reply (410) for get BSS: id=0,
I/wpa_supplicant( 3998): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3998): freq=5220
I/wpa_supplicant( 3998): level=-51
I/wpa_supplicant( 3998): tsf=0000000087940952
I/wpa_supplicant( 3998): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3998): ssid=NG7005g
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=1
I/wpa_supplicant( 3998): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3998): freq=2437
I/wpa_supplicant( 3998): level=-83
I/wpa_supplicant( 3998): tsf=0000000087940962
I/wpa_supplicant( 3998): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 3998): ssid=UPC Wi-Free
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=2
I/wpa_supplicant( 3998): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 3998): freq=2437
I/wpa_supplicant( 3998): level=-83
I/wpa_supplicant( 3998): tsf=0000000087940966
I/wpa_supplicant( 3998): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 3998): ssid=UPC5999698
I/wpa_supplicant( 3998): ####
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
D/WifiManager( 1202): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 87940952, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2437, timestamp: 87940962, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 87940966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@425c5f90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@425c5f90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@425c5f90 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 3998): EAPOL: disable timer tick
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
,I/bt-btu  ( 3939): btu_task received preload complete event
,D/bt-btm  ( 3939): btm_acl_device_down
,D/bt-btm  ( 3939): btm_acl_reset_paging
,D/bt-btm  ( 3939): btm_acl_set_discing
,I/bt-btm  ( 3939): btm_reset_complete
,I/bt-btm  ( 3939): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 3939): Start reading local supported commands
,D/bt-btm  ( 3939): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 3939): BTM reads next extended features page (1)
,D/bt-btm  ( 3939): BTM reads next extended features page (2)
D/bt-btm  ( 3939): BTM reached last extended features page (2)
,D/bt-btm  ( 3939): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0f
,D/bt-btm  ( 3939): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x0d
,D/bt-btm  ( 3939): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 3939): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 3939): btm_read_ble_wl_size 
,D/bt-btm  ( 3939): btm_read_white_list_size_complete 
,D/bt-btm  ( 3939): btm_get_ble_buffer_size 
,D/bt-btm  ( 3939): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 3939): btm_read_ble_local_supported_features 
,D/bt-btm  ( 3939): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 3939): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 3939): btm_decode_ext_features_page page: 0
D/bt-btm  ( 3939): Local supported ACL packet types: 0xcc18
,D/bt-btm  ( 3939): Local supported SCO packet types: 0x038f
D/bt-btm  ( 3939): btm_sec_dev_reset : loc_io_caps is 0 
I/bt-btm  ( 3939): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,I/bt-btm  ( 3939):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 3939): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 3939): BTM_SetInquiryMode
I/bt-btm  ( 3939): BTM_SetPageScanType
I/bt-btm  ( 3939): BTM_SetInquiryScanType
,D/bt-btm  ( 3939): btm_decode_ext_features_page page: 1
D/bt-btm  ( 3939): btm_decode_ext_features_page page: 2
D/bt-btm  ( 3939): BTM_BleLoadLocalKeys
D/bt-btm  ( 3939): BTM_BleLoadLocalKeys
,I/bt-btm  ( 3939): BTM_Sec: application registered
E/bt-btm  ( 3939): BTM_SecRegister:p_cb_info->p_le_callback == 0x62024941 
I/bt-btm  ( 3939): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 3939): SMP_Register state=0
E/bt-btm  ( 3939): BTM_SecRegister: btm_cb.api.p_le_callback = 0x62024941 
I/bt-btm  ( 3939): BTM_Sec: application registered
D/bt-btm  ( 3939): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 3939): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 3939): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 3939): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 3939): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 3939): BTM_RegBusyLevelNotif
I/bt-att  ( 3939): GATT_Register
D/bt-att  ( 3939): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 3939): allocated gatt_if=3
I/bt-att  ( 3939): GATT_StartIf gatt_if=3
D/bt-att  ( 3939): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3939): gatt_find_the_connected_bda found=0 found_idx=7
,I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btm  ( 3939): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 3939): BTM_AllocateSCN
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 3939): BTM_AllocateSCN
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btm  ( 3939): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3939):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 3939):                : sec: 0x1086, service name [] (up to 21 chars saved)
E/bt-btif ( 3939): BTM_SEC_REG[5]: id 3
I/bt-btm  ( 3939): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 3939): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 3939): A2D_AddRecord uuid: 110a
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
D/bt-avp  ( 3939): AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 3939): AVRC_AddRecord uuid: 110e
,I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btm  ( 3939): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 3939):                : sec: 0x80, service name [] (up to 21 chars saved)
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 7c:f9:0e:51:18:22
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
I/bt-att  ( 3939): GATT_Register
D/bt-att  ( 3939): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 3939): allocated gatt_if=4
I/bt-att  ( 3939): GATT_StartIf gatt_if=4
D/bt-att  ( 3939): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 3939): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 80:01:84:8a:b3:68
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 14:b4:84:21:3b:49
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 08:ec:a9:50:76:27
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 08:ec:a9:50:75:41
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: f8:cf:c5:d9:e5:61
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 7c:f9:0e:34:8a:a0
,D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 90:e7:c4:f6:69:77
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 90:e7:c4:3c:62:6a
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
D/bt-btm  ( 3939): BTM_GetHCIConnHandle
I/bt-btm  ( 3939): BTM_SecAddDevice()  BDA: 38:94:96:b5:06:dc
D/bt-btm  ( 3939): BTM_SecAddDevice : rmt_io_caps is 0 
E/bt-btif ( 3939): btif_storage_get_adapter_property service_mask:0x140040
,I/bt-btif ( 3939): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3939): Address is:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:1 len:14
,I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3939): Scan Mode:20
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3939): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:8 len:60
,D/BluetoothAdapter( 3939): getBluetoothService(): entry
D/BluetoothAdapter( 3939): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 3939): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41bc4b28
,D/BluetoothDevice( 3939): getService : Register callback
,D/BluetoothAdapterProperties( 3939): Adding bonded device:7C:F9:0E:51:18:22
,D/BluetoothAdapterProperties( 3939): Adding bonded device:80:01:84:8A:B3:68
,D/BluetoothAdapterProperties( 3939): Adding bonded device:14:B4:84:21:3B:49
,D/BluetoothAdapterProperties( 3939): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 3939): Adding bonded device:08:EC:A9:50:75:41
,D/BluetoothAdapterProperties( 3939): Adding bonded device:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3939): Adding bonded device:7C:F9:0E:34:8A:A0
,D/BluetoothAdapterProperties( 3939): Adding bonded device:90:E7:C4:F6:69:77
,D/BluetoothAdapterProperties( 3939): Adding bonded device:90:E7:C4:3C:62:6A
D/BluetoothAdapterProperties( 3939): Adding bonded device:38:94:96:B5:06:DC
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:3 len:48
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 14:B4:84:21:3B:49, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
D/wpa_supplicant( 3998): EAPOL: disable timer tick
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 90:E7:C4:3C:62:6A, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 3939): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
,D/BluetoothRemoteDevices( 3939): Remote class is:5898764
,I/bt-btif ( 3939): BTA_JvEnable
I/bt-btm  ( 3939): BTM_ReadConnectability
I/bt-btm  ( 3939): BTM_ReadDiscoverability
,I/bt-btm  ( 3939): BTM_SetDiscoverability
I/bt-btm  ( 3939): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 3939): br_edr_supported=0x2
,I/bt-btm  ( 3939): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3939): btm_ble_update_adv_flag new=0x0,
I/bt-btm  ( 3939): evt_type=0x3 p-cb->evt_type=0x3 
,I/bt-btm  ( 3939): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3939): BTM_SetConnectability
I/bt-btm  ( 3939): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3939): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3939): BTM_SetDiscoverability
I/bt-btm  ( 3939): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3939): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3939): br_edr_supported=0x0
I/bt-btm  ( 3939): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3939): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3939): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 3939): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3939): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 3939): BTM_SetConnectability
I/bt-btm  ( 3939): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3939): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 3939): bta_pan_co_init
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 3939): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3939):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 3939):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 3939): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3939):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3939): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 3939):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
,I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
,I/bt-btif ( 3939): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 3939): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3939): ScanMode =  20
D/BluetoothAdapterProperties( 3939): State =  11
I/bt-btif ( 3939): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 3939): Setting state to 12
,I/BluetoothAdapterState( 3939): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService( 3939): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btm  ( 3939): BTM_SetDiscoverability
I/bt-btm  ( 3939): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3939): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 3939): br_edr_supported=0x0,
I/bt-btm  ( 3939): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 3939): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 3939): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3939): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 3939): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3939): BTM_SetConnectability
,I/bt-btm  ( 3939): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/bt-btm  ( 3939): new flag=0x0 cur flag=0x4
D/bt-btm  ( 3939): btm_ble_update_adv_flag new=0x0
D/bt-btm  ( 3939): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 3939): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 3939): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3939): Scan Mode:21
I/bt-btif ( 3939): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 3939): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3939): Discoverable Timeout:120
E/bt_mct  ( 3939): hci lib postload completed
I/BluetoothAdapterState( 3939): Entering On State
D/BluetoothHeadset( 1218): Proxy object connected
D/BluetoothAdapterService(1102570512)( 3939): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3939): getBondedDevices: length=10
,D/BluetoothHeadset( 1218): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1218): Proxy object connected
D/BluetoothPhoneService( 1218): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1111): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1218): 1103858760: getState(). Returning 12
D/BluetoothPan(  906): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1111): Proxy object connected
,I/QuickSettingMiniLite( 1111): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@41e7b7d0
,D/BluetoothA2dp(  906): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  906): onBluetoothStateChange: up=true
D/BluetoothPan(  906): BluetoothPAN Proxy object connected
,D/BluetoothHeadset(  906): Proxy object connected
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:206 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp$1.onBluetoothStateChange:131 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset$1.onBluetoothStateChange:249 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:640 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1318 
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapter(  906): 1112467088: getState(). Returning 12
D/BluetoothAdapterService(1102570512)( 3939): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3939): getBondedDevices: length=10
I/IntentController( 1111): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/PMS     (  906): acquireWL(424ad4c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1202 10029 null
D/PMS     (  906): releaseWL(424ad4c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
V/BluetoothPbapReceiver( 3939): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3939): ***********state = 12
D/BluetoothMasReceiver( 3939): Bluetooth STATE CHANGED to 12
D/BluetoothA2dp(  906): Proxy object connected
D/HtcBtWidget_BTWidgetProvider( 3965): onBTStateChanged() for widget: 
V/BluetoothSapReceiver( 3939): SapReceiver onReceive 
V/BluetoothSapReceiver( 3939): action = android.bluetooth.adapter.action.STATE_CHANGED
D/HtcBtWidget_BTWidgetProvider( 3965): updateWidget(context) for widget: 
V/BluetoothSapReceiver( 3939):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 3939): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/PMS     (  906): acquireWL(426d2620): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3323 1000 null
W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  906): releaseWL(426d2620): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  906): acquireWL(43cfddf0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3323 1000 null
D/BluetoothAdapter(  906): 1112467088: getState(). Returning 12
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 12
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42629f80:true
D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 12
V/BluetoothMasService( 3939): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 3939): Manager Instance is not NULL
I/LocationAgent( 3323): new LocationAgent instance!!
D/HtcTagManager( 3323): HtcTagManager construction complete
,D/BluetoothManagerService(  906): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/EmailUtils( 3939): ============NULL aList========
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
V/EmailUtils( 3939): <-getEmailAccountIdList
D/BluetoothInputDevice( 3323): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
,D/BluetoothInputDevice( 3323): BluetoothInputDevice(): Binding service...
W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
D/BluetoothPan( 3323): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 8
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
,D/BluetoothPan( 3323): BluetoothPan(): Binding service...
V/BluetoothSapService( 3939): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 3939): state: 12
,D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 12
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
W/ContextImpl( 3939): Implicit intents with startService are not safe: Intent { act=android.bluetooth.IBluetooth } android.content.ContextWrapper.bindService:524 com.android.bluetooth.sap.BluetoothSapService.parseIntent:468 com.android.bluetooth.sap.BluetoothSapService.onStartCommand:347 
V/BluetoothSapService( 3939): Starting SAP server process
V/BluetoothPbapService( 3939): Handler(): got msg=1
V/BluetoothPbapService( 3939): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 3939): Pbap Service initSocket
V/BluetoothMasService( 3939): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 3939): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 1111): 1105293496: getState(). Returning 12
D/BluetoothAdapter( 1111): 1105293496: getState(). Returning 12
I/QuickSettingBluetooth( 1111): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1111): addIcon slot=bluetooth index=12 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothAdapter( 3939): getBluetoothService(): entry
W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMap( 3323): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
E/BluetoothServiceJni( 3939): SOCK FLAG = 1 ***********************
I/bt-btif ( 3939): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[13]: id 52, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 3939):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 3939): Succeed to create listening socket 
V/BluetoothPbapService( 3939): Accepting socket connection...
E/BluetoothMap( 3323): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 10
D/BluetoothMasService( 3939): Map_prev 1
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3939): getBluetoothService(): entry
W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSap( 3323): BluetoothSap() call bindService
E/BluetoothServiceJni( 3939): SOCK FLAG = 3 ***********************
I/bt-btif ( 3939): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[14]: id 53, is_orig 0, psm 0x0003, proto_id 3, chan_id 16
I/bt-btm  ( 3939):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3939): getBluetoothService(): entry
W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothPbap( 3323): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
E/BluetoothServiceJni( 3939): SOCK FLAG = 3 ***********************
I/bt-btif ( 3939): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[15]: id 54, is_orig 0, psm 0x0003, proto_id 3, chan_id 17
I/bt-btm  ( 3939):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 11
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
,D/BluetoothPbap( 3323): BluetoothPbap(): Binding service...
,D/BluetoothA2dp( 3323): BluetoothA2dp()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 12
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
D/BluetoothA2dp( 3323): BluetoothA2dp(): Binding service...
D/BluetoothHeadset( 3323): BluetoothHeadset()
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
,D/BluetoothHeadset( 3323): BluetoothHeadset(): Binding service...
W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/HtcTagManager( 3323): startProxy
,W/ContextImpl( 3323): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
,D/LocalBluetoothProfileManager( 3323): LocalBluetoothProfileManager construction complete
,D/BluetoothSapService( 3939): Sap_prev 1
,V/BluetoothSapService( 3939): SAP Service startRfcommListenerThread
,D/BluetoothAdapter( 1111): 1105293496: getState(). Returning 12
,W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/DockEventReceiver( 3323): finishStartingService: stopping service
D/BluetoothPan( 3323): BluetoothPAN Proxy object connected
D/PanProfile( 3323): Bluetooth service connected
D/BluetoothA2dp( 3323): Proxy object connected
D/A2dpProfile( 3323): Bluetooth service connected
I/QuickSettingMiniLite( 1111): updateLiteState:no connect device!
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
V/BluetoothSapService( 3939): Sap Service initRfcommSocket
V/TAG     ( 3939): android.bluetooth.IBluetoothSap
V/BluetoothSapService( 3939): Sap Service onBind mSapBinder: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41bbb360
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 3939): Pbap Service onBind
D/BluetoothAdapter( 3939): getBluetoothService(): entry
W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 3323): Proxy object connected
D/HeadsetProfile( 3323): Bluetooth service connected
E/BluetoothServiceJni( 3939): SOCK FLAG = 3 ***********************
I/bt-btif ( 3939): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[16]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 3939):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 3939): Succeed to create listening socket 
V/BluetoothSapService( 3939): Accepting socket connection...
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
D/BluetoothInputDevice( 3323): Proxy object connected
D/HidProfile( 3323): Bluetooth service connected
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3323): 1104163720: getState(). Returning 12
D/BluetoothAdapter( 3939): getBluetoothService(): entry
W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
I/BluetoothFtpService( 3939): Ftp Service onCreate
E/BluetoothServiceJni( 3939): SOCK FLAG = 0 ***********************
I/bt-btif ( 3939): BTA_JvCreateRecordByUser
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[17]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 3939):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,I/BtOppRfcommListener( 3939): Accept thread started.
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4019): onCreate: going to find gatt base service first.
D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 12
D/SapServerProfile( 3323): Bluetooth service connected
D/BluetoothPbap( 3323): Proxy object connected
,D/PbapServerProfile( 3323): Bluetooth service connected
,D/BluetoothMasReceiver( 3939): Bluetooth STATE CHANGED to 12
D/PMS     (  906): releaseWL(43cfddf0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothFtpService( 3939): Ftp_prev 1
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 3939): getBluetoothService(): entry
,W/BluetoothAdapter( 3939): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3939): SOCK FLAG = 1 ***********************
W/System.err(  906): java.lang.Throwable: stack dump
,I/bt-btif ( 3939): BTA_JvCreateRecordByUser
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/bt-sdp  ( 3939): SDP_CreateRecord ok, num_records:16
I/bt-btm  ( 3939): Write Extended Inquiry Response to controller
I/bt-btif ( 3939): BTA_JvRfcommStartServer
I/bt-btm  ( 3939): BTM_SEC_REG[18]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 3939):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426d1c18:true
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3939): Run Accept thread
D/BluetoothAdapter( 3939): 1102588688: getState(). Returning 12
V/BluetoothMasService( 3939): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 3939): Manager Instance is not NULL
,D/[HTC_BLE][Constants]( 4019):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4019):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4019):  + discoverServicesOnBonded = false
,D/EmailUtils( 3939): ============NULL aList========
,V/EmailUtils( 3939): <-getEmailAccountIdList
,D/BluetoothMasService( 3939): Map_prev 1
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4019):  + Google LE service found. Using BaseLeProfilesGoogle.
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4019): HtcBleProximityService HTC_BLE_APK_VERSION: 2013.12.02.SDKBUILD, isTagEnabled = true, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b851b8
D/[HTC_BLE][Constants]( 4019): dumpConstants: CONNECTION_DELAY_TIMEOUT = 3000
D/[HTC_BLE][Constants]( 4019): dumpConstants: CONNECTION_DELAY_INTERVAL = 1500
D/[HTC_BLE][Constants]( 4019): dumpConstants: DISCONNECTION_DELAY_TIMEOUT = 8000
D/[HTC_BLE][Constants]( 4019): dumpConstants: DISCONNECTION_DELAY_INTERVAL = CONNECTION_DELAY_INTERVAL
D/[HTC_BLE][Constants]( 4019): dumpConstants: PINGPONG_BLOCKER_TIMEOUT = 20000
,D/[HTC_BLE][Constants]( 4019): dumpConstants: PINGPONG_BLOCKER_INTERVAL = 10000
,I/[HTC_BLE_2013.12.02.SDKBUILD][HtcBleProximityService]( 4019): onBind Intent: com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService
,D/HtcTagManager( 3323): onServiceConnected
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 4019): Received state change = 12
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4019): onStartCommand: Intent { cmp=com.htc.bluetooth.le.profiles/.HtcBleProximityService }, 0, 1
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4019): initLeServices: null, com.htc.bluetooth.le.profiles.HtcBleProximityService@41b851b8
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 4019): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b851b8
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 4019): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b851b8, com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b90b70
,D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 4019): init: com.htc.bluetooth.le.profiles.HtcBleProximityService@41b851b8
D/HtcTagProfile( 3323): setup proxy
D/HtcPxpProfile( 3323): setup proxy
,D/HtcFmpProfile( 3323): setup proxy
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4267d128:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3863): new LocationAgent instance!!
,D/HtcTagManager( 3863): HtcTagManager construction complete
,D/RingtoneManager( 4019): getExternalStorageState=mounted
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothInputDevice( 3863): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 14
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothInputDevice( 3863): BluetoothInputDevice(): Binding service...
,D/BluetoothPan( 3863): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 15
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothPan( 3863): BluetoothPan(): Binding service...
W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothInputDevice.doBind:257 android.bluetooth.BluetoothInputDevice.<init>:244 android.bluetooth.BluetoothAdapter.getProfileProxy:1385 
,W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPan.doBind:162 android.bluetooth.BluetoothPan.<init>:149 android.bluetooth.BluetoothAdapter.getProfileProxy:1388 
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[-1]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[0]: Crocus
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[1]: Daisy
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[2]: Feverfew
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[3]: Foxglove
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[4]: Goldenrod
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[5]: Hangouts Message
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[6]: Lavender
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[7]: Licorice
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[8]: Olive
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[9]: Rose
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[10]: Snowbell
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[11]: Thalia
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[12]: Tulip
D/BluetoothMap( 3863): Create BluetoothMap proxy object
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[13]: Wintergreen
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + Available RingingTone[14]: Wisteria
D/[HTC_BLE_2013.12.02.SDKBUILD][StateAlerting]( 4019):  + mAlertUri: content://settings/system/alarm_alert
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
E/BluetoothMap( 3863): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothSap( 3863): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 17
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4019): BleProfilesStateMachine is initialized...
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 4019): Enter IdleState
,D/BluetoothPbap( 3863): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 18
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothPbap( 3863): BluetoothPbap(): Binding service...
W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4019): initLeServices_platform
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4019): initScanModeInterface: true
W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42604ad0:true
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothA2dp( 3863): BluetoothA2dp()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 19
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4019): loadDeviceConfiguration() init =true
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 4019):  + mTag.getPrimaryDeviceList() = []
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothA2dp( 3863): BluetoothA2dp(): Binding service...
D/[HTC_BLE][Constants]( 4019):  + defaultServices = 0
D/[HTC_BLE][Constants]( 4019):  + enableOnBonded = false
,D/[HTC_BLE][Constants]( 4019):  + discoverServicesOnBonded = false
W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothPbap.doBind:176 android.bluetooth.BluetoothPbap.<init>:163 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothA2dp.doBind:177 android.bluetooth.BluetoothA2dp.<init>:164 android.bluetooth.BluetoothAdapter.getProfileProxy:1382 
D/BluetoothHeadset( 3863): BluetoothHeadset()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 20
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/BluetoothHeadset( 3863): BluetoothHeadset(): Binding service...
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 4019): onInitialized: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b90b70
,D/HtcTagManager( 3863): startProxy
,W/ContextImpl( 3863): Implicit intents with startService are not safe: Intent { act=com.htc.android.bluetooth.le.profile.pxp.IHtcBleProximityService } android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 
W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothHeadset.doBind:295 android.bluetooth.BluetoothHeadset.<init>:282 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.android.settings.bluetooth.HtcTagManager.startProxy:239 com.android.settings.bluetooth.LocalBluetoothProfileManager.updateLocalProfiles:203 com.android.settings.bluetooth.LocalBluetoothProfileManager.<init>:150 
D/LocalBluetoothProfileManager( 3863): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/LocalBluetoothProfileManager( 3863): setBluetoothStateOn
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/HtcTagManager( 3863): startProxy
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/BluetoothAdapterService(1102570512)( 3939): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3939): getBondedDevices: length=10
D/BluetoothAdapter( 3863): getBluetoothService(): entry
D/BluetoothAdapter( 3863): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3863): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@41bbf8b0
D/BluetoothDevice( 3863): getService : Register callback
E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
,D/HtcTagManager( 3863): addHtcTagProfiles
,E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/HtcTagManager( 3863): addHtcTagProfiles
E/BluetoothDevice( 3863): getBluetoothClass(): COD is 5898764
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/HtcTagManager( 3863): addHtcTagProfiles
D/BluetoothInputDevice( 3863): Proxy object connected
D/HidProfile( 3863): Bluetooth service connected
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/BluetoothPan( 3863): BluetoothPAN Proxy object connected
D/PanProfile( 3863): Bluetooth service connected
D/AuthorizationBluetoothService( 1351): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1351): Proximity feature is not enabled.
D/SapServerProfile( 3863): Bluetooth service connected
D/BluetoothPbap( 3863): Proxy object connected
D/PbapServerProfile( 3863): Bluetooth service connected
D/BluetoothA2dp( 3863): Proxy object connected
D/A2dpProfile( 3863): Bluetooth service connected
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/BluetoothHeadset( 3863): Proxy object connected
D/HeadsetProfile( 3863): Bluetooth service connected
D/BluetoothAdapter( 3863): 1102602680: getState(). Returning 12
D/HtcTagManager( 3863): onServiceConnected
D/HtcTagProfile( 3863): setup proxy
D/HtcPxpProfile( 3863): setup proxy
D/HtcFmpProfile( 3863): setup proxy
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times.
,D/PMS     (  906): acquireWL(4262dcb0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4262dcb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4276bb90): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4276bb90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43d1af10): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43d1af10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e563e0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42e563e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3893): 
,E/BTIF_CORE( 3939): NETI system_power_manager_wake : 259 param 0
I/bt-btif ( 3939): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 3939): Wake lock released
,I/SensorManager(  906): mEventCount = 750
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1485): Don't start project servcice
D/HtcModeClient( 1485): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1485): connectState: CONNECTION_READY = false
D/SilentMusic( 1485): call stop
D/HtcModeClient( 1485): close connection
W/HtcModeClient( 1485): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1485): read the terminate packet, so break
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4079 uid=10078 gids={50078}
,D/PMS     (  906): acquireWL(42bb8a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10078}
V/AlarmManager(  906): sending alarm PendingIntent{426d15f0: PendingIntentRecord{425facc8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454056124519, Int=60000
,D/PMS     (  906): releaseWL(42bb8a38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4079): SMSBackupAgentService started
,D/SMSBackup( 4079): Checking restore status
,D/SMSBackup( 4079): Restore complete
,D/SMSBackup( 4079): cancelCheckAlarm
,D/SMSBackup( 4079): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3627
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
I/ActivityManager(  906): Killing 3627:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3627
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3893): Test app app.js loaded
I/jxcore-log( 3893): 
,W/dalvikvm( 3893): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3893): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3893): BLE advertisement is supported
I/jxcore-log( 3893): 
,I/chromium( 3893): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/LightsService(  906): setLight #0: color=#3d
,V/LightsService(  906): setLight #0: color=#3a
,V/LightsService(  906): setLight #0: color=#33
,V/LightsService(  906): setLight #0: color=#2d
,V/LightsService(  906): setLight #0: color=#26
,V/LightsService(  906): setLight #0: color=#1f
,V/LightsService(  906): setLight #0: color=#19
,V/LightsService(  906): setLight #0: color=#14
,I/wpa_supplicant( 3998): wpa_supplicant_scan enter
I/wpa_supplicant( 3998): ap_scan=1 , scan_req =0
I/wpa_supplicant( 3998): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 3998): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 3998): nl80211: Event message available
,D/wpa_supplicant( 3998): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/SensorManager(  906): mEventCount = 900
,D/wpa_supplicant( 3998): nl80211: Event message available
D/wpa_supplicant( 3998): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 3998): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3998): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 3998): nl80211: Survey data missing
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 3998): Sorted scan results
I/wpa_supplicant( 3998): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 3998): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 3998): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 3998): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-73
I/wpa_supplicant( 3998): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 3998): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
D/wpa_supplicant( 3998): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 3998): Add randomness: count=8 entropy=6
D/wpa_supplicant( 3998): Add randomness: count=9 entropy=7
D/wpa_supplicant( 3998): Add randomness: count=10 entropy=8
D/wpa_supplicant( 3998): Add randomness: count=11 entropy=9
D/wpa_supplicant( 3998): Add randomness: count=12 entropy=10
D/wpa_supplicant( 3998): Add randomness: count=13 entropy=11
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3998): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 3998): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 3998): wpa_supplicant_pick_network+
I/wpa_supplicant( 3998): Selecting BSS from priority group 1
I/wpa_supplicant( 3998): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 3998): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 3998): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 3998): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 3998): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 3998):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 3998):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 3998): Start print parameters
I/wpa_supplicant( 3998): wpa_s->wpa_state is 3
I/wpa_supplicant( 3998): wpa_s->br_have_IP is 0
I/wpa_supplicant( 3998): isConcurrentMode() is 0
I/wpa_supplicant( 3998): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 3998): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 3998): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 3998): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 3998): wpa_s->reassociate is 0
I/wpa_supplicant( 3998): wpa_s->is_screen_on 1
I/wpa_supplicant( 3998): wpa_s->ifname wlan0
I/wpa_supplicant( 3998): End print parameters
I/wpa_supplicant( 3998): selected network = 4
D/wpa_supplicant( 3998,): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8edd4e8  current_ssid=0x0
D/wpa_supplicant( 3998): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3998): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 3998): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 3998): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 3998): check if in concurrent case
I/wpa_supplicant( 3998): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 3998): wpa_supplicant_associate, 1777
D/wpa_supplicant( 3998): wpa_supplicant_associate, 1780
D/wpa_supplicant( 3998): wpa_supplicant_associate, 1795
D/wpa_supplicant( 3998): RSN: PMKSA cache search - network_ctx=0xb8edd4e8 try_opportunistic=0
D/wpa_supplicant( 3998): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3998): RSN: No PMKSA cache entry found
I/wpa_supplicant( 3998): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 3998): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 3998): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 3998): nl80211: Unsubscribe mgmt frames handle 0xb8edc718 (mode change)
D/wpa_supplicant( 3998): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8edc718
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Register frame type=0xd0 nl_handle=0xb8edc718
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 3998): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 3998):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 3998):   * freq=2412
D/wpa_supplicant( 3998):   * Auth Type 0
D/wpa_supplicant( 3998):   * WPA Versions 0x2
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 3998): nl80211: Connect request send successfully
D/wpa_supplicant( 3998): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 3998): EAPOL: Supplic,ant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): RSN: Ignored PMKID candidate without preauth flag
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING,
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 3998): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 3998): reply (779) for get BSS: id=0
I/wpa_supplicant( 3998): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 3998): freq=5220
I/wpa_supplicant( 3998): level=-51
I/wpa_supplicant( 3998): tsf=0000000105102900
I/wpa_supplicant( 3998): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 3998): ssid=NG7005g
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=1
I/wpa_supplicant( 3998): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 3998): freq=2437
I/wpa_supplicant( 3998): level=-83
I/wpa_supplicant( 3998): tsf=0000000105102965
I/wpa_supplicant( 3998): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 3998): ssid=UPC Wi-Free
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=2
I/wpa_supplicant( 3998): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 3998): freq=2437
,I/wpa_supplicant( 3998): level=-83
I/wpa_supplicant( 3998): tsf=0000000105102974
I/wpa_supplicant( 3998): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 3998): ssid=UPC5999698
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=3
I/wpa_supplicant( 3998): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 3998): freq=2412
I/wpa_supplicant( 3998): level=-51
I/wpa_supplicant( 3998): tsf=0000000105102927
I/wpa_supplicant( 3998): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 3998): ssid=01ABC,
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=4
I/wpa_supplicant( 3998): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3998): freq=2412
I/wpa_supplicant( 3998): level=-51
I/wpa_supplicant( 3998): tsf=0000000105102939
I/wpa_supplicant( 3998): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 3998): ssid=NG700
I/wpa_supplicant( 3998): ====
I/wpa_supplicant( 3998): id=5
I/wpa_supplicant( 3998): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 3998): freq=2452
I/wpa_supplicant( 3998): level=-73
I/wpa_supplicant( 3998): tsf=0000000105102951
I/wpa_supplicant( 3998): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 3998): ssid=Gonzos
I/wpa_supplicant( 3998): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105102900, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -83, frequency: 2437, timestamp: 105102965, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 105102974, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 105102927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 105102939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2452, timestamp: 105102951, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiManager( 1202): getScanResults enter 
D/WifiStateMachine(  906): == (6) end of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 3998): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 3998): nl80211: Event message available
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 3998): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 3998): nl80211: Connect event
D/wpa_supplicant( 3998): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 3998): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 3998): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 3998): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 3998): Add randomness: count=14 entropy=12
I/wpa_supplicant( 3998): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 3998): TDLS: Remove peers on association
D/wpa_supplicant( 3998): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48,
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: External notification - portValid=0
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 3998): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 3998): EAPOL: enable timer tick
D/wpa_supplicant( 3998): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 3998): htc_wext_set_keepalive +
I/wpa_supplicant( 3998): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 3998): getPrivFuncNum +	
I/wpa_supplicant( 3998): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 3998): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3998): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 3998): Get randomness: len=32 entropy=13
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Setting MAC Address to c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Associated
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...,
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 3998): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8edc9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 3998):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 3998): EAPOL: External notification - portValid=1
I/wpa_supplicant( 3998): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f14b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 3998):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 3998): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 3998): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 3998): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3998): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 3998): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3998): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 3998): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 3998): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 3998): set send_ind_to_ndc = 0
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 3998): EAPOL: External notification - portValid=1
D/wpa_supplicant( 3998): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 3998): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 3998): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 3998): EAP: EAP entering state DISABLED
D/wpa_supplicant( 3998): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 3998): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 3998): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 3998): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 3998): EAPOL authentication completed successfully
I/wpa_supplicant( 3998): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 3998): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 3998): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 3998): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3323): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 3323): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -9999, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  906): New client listening to asynchronous messages
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:3
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): WiFioffload: set mMobileNetworkType= Unknown
D/WifiNative-wlan0(  906): doBoolean: MOBILE_TYPE Unknown
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 MOBILE_TYPE Unknown"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 3998): WiFioffload: update mobile network = Unknown
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42f17758): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): Power_Mode_Type mode = 1
I/wpa_supplicant( 3998): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426a24e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426a24e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 3998): EAPOL: startWhen --> 0
,D/wpa_supplicant( 3998): EAPOL: disable timer tick
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42275d20
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42275d20, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423daeb0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@43722218
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  906): nativeSetInteractive:false
,D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
,D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1234): ScreenObserver: OFF
,D/NfcService( 1234): applyRouting - 0
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=3893
W/ResourceType( 3893): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3893): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b753b0 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1234): applyRouting -2
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43953640)
D/PMS     (  906): acquireWL(43c12320): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1234 1027 null
D/PMN     (  906): wakingUp
D/PMS     (  906): releaseWL(43c12320): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(4347e750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(4347e750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  906): onScreenOn
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2157): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2157): [MTP][onReceive]-
,D/NfcService( 1234): applyRouting - 0
,D/NfcService( 1234): applyRouting -2
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(43bc0da0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1234 1027 null
,D/PMS     (  906): releaseWL(43bc0da0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1111): stop update clock
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4110 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
I/wpa_supplicant( 3998): SET_SCREEN_ON:On
I/wpa_supplicant( 3998): htc_wext_set_keepalive +
I/wpa_supplicant( 3998): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 3998): getPrivFuncNum +	
I/wpa_supplicant( 3998): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 3998): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  906): updateScreenOn: false
,W/ContextImpl( 4110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(42f0b580): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4110 1000 null
,D/PMS     (  906): releaseWL(42f0b580): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4110): getMobilePolicyEnabled, result = true
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1297): receiver - intent: android.intent.action.USER_PRESENT
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/TetherSettings( 3323): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3323): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3323): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3323): Cust_ConnectToPC   : spcsc>false
D/        ( 3323): Cust_ConnectToPC   : IPT>true
D/        ( 3323): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3323): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3323): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3323): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3323): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1297): service - onCreate()
,I/PSReceiver( 3323): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1297): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3323): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3323): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3323):  defaultType:0
D/PMS     (  906): acquireWL(43616430): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43616430): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3323): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(426d11e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1297): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  906): request 41c7aa78 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/PMS     (  906): releaseWL(426d11e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4019): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4019): onScreenOn: 1454056135593
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4019): onScreenOn: 1454056135593
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423daeb0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423daeb0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@43722218
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(42e016c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19948 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): SET_SCREEN_ON:Off
I/wpa_supplicant( 3998): htc_wext_set_keepalive +
I/wpa_supplicant( 3998): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3998): getPrivFuncNum +	
I/wpa_supplicant( 3998): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3998): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 3998): get_ip_address source addr = 02000000
I/wpa_supplicant( 3998): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 3998): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): releaseWL(42e016c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  906): acquireWL(42eb4c88): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42eb4c88): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1218): start background delete task...
,D/NetworkPolicy(  906): updateScreenOn: false
D/ContactMessageStore( 1218): size: 0 , 0
,D/ContactMessageStore( 1218): Background delete complete
W/ContextImpl( 4110): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4110): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4110): getMobilePolicyEnabled, result = true
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43722218
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43722218, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  906): New client listening to asynchronous messages
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@43722218, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@43722218
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e15c30 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42e15c30 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42e68208): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42e68208): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43d68410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43d68410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 4019): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4019): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4019): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 4019): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 4019): onScreenOff
D/AutoSetting( 1297): service - mHandler: cancel location update
,D/AutoSetting( 1297): service -           changes count: 0
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): Power_Mode_Type mode = 0
,I/wpa_supplicant( 3998): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 3998): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(42f17758): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 3998): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 3998): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 3998): htc_wext_set_keepalive +
I/wpa_supplicant( 3998): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 3998): getPrivFuncNum +	
I/wpa_supplicant( 3998): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 3998): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 3998): get_ip_address source addr = c0a80175
I/wpa_supplicant( 3998): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 3998): htc_wext_set_keepalive - ret = 0
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  906): WAN detection
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/MDST    (  906): default: setTeardownRequested(true)
,D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 3323): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(53),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424f4290
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(43cc7a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(43cc7a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/PMS     (  906): acquireWL(434f0ce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/NetworkMonitor( 3375): type=WIFI subType= reason=null isConnected=true
,I/Tethering(  906): Found interface wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1247/10076)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3375/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,I/ConnectivityHelper( 1247): [onReceive] WIFI(1): CONNECTED
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
D/libc    (  363): [NET] +++++ res_nsend xid =a458 +++++
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3398/10053)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426bfb20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 95
D/libc    (  363): [NET]res_nsend:resplen=104
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4175 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/PMS     (  906): acquireWL(442c3f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/IntentController( 1111): receive(android.intent.action.TIME_SET,4,false)
,D/DotMatrix( 1528): [EventService] EVENT_RESET_THEME_TIMESTAMP
I/FeedActionBar( 1247): updateLastUpdatedTime(in String) LAST UPDATED 9:27
,D/DotMatrix( 1528): [EventService] isTheSameDay:false,timestamp is early than today:true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(442be218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1202): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(4248a308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(41bb9db8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): acquireWL(43688710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): acquireWL(4262d2b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 906 1000 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4247e478): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 906 1000 WorkSource{10029}
,I/GamesSyncServiceMain( 1966): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1966): Failed to execute periodic sync, missing client context - aborting
D/PMS     (  906): releaseWL(426bfb20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4248a308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426ad2f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ACRA    ( 4175): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4175): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4175): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/PMS     (  906): acquireWL(425438f0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
,I/ActivityManager(  906): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4200 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME
,D/GpsLocationProvider(  906): NTP server returned: 1454056140689 (Fri Jan 29 09:29:00 CET 2016) reference: 108889 certainty: 33 system time offset: -237
D/PMS     (  906): releaseWL(442be218): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4226cfa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(426ad2f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426cadf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4226cfa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4389f920): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4389f920): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(420a5698): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/GpsLocationProvider(  906): [handleMessage] INJECT_NTP_TIME_FINISHED
D/PMS     (  906): releaseWL(420a5698): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(434f0ce0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
D/PMS     (  906): acquireWL(42644038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42644038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1966): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42d92c80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24418, reason: UserStart, SyncResult: databaseError: true stats []
,D/PMS     (  906): releaseWL(4247e478): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/SyncManager(  906): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 109171, reason: UserStart
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426cadf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42e0e808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
W/dalvikvm( 1966): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(42e840d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
W/SystemClassLoaderAdder( 4175): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,V/DexLibLoader( 4175): Preparing secondary program dexes.
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
V/DexLibLoader( 4175): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4175): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4175): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4175): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4175): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4175): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4175): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4175): Dex already copied
D/OdexVerifier( 4175): Odex verification is skipped.
,V/DexLibLoader( 4175): Creating class loader
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42e0e808): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1202): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1202): [NET] getaddrinfo-,err=8
D/libc    ( 1202): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1202): [NET] getaddrinfo-, 1
,D/libc    ( 1202): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5cdc +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,V/DexLibLoader( 4175): Finished creating class loader
V/DexLibLoader( 4175): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4175): Dex already copied
D/OdexVerifier( 4175): Odex verification is skipped.
,V/DexLibLoader( 4175): Creating class loader
,V/DexLibLoader( 4175): Finished creating class loader
V/DexLibLoader( 4175): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4175): Dex already copied
D/OdexVerifier( 4175): Odex verification is skipped.
,V/DexLibLoader( 4175): Creating class loader
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DexLibLoader( 4175): Finished creating class loader
V/DexLibLoader( 4175): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4175): Dex already copied
D/OdexVerifier( 4175): Odex verification is skipped.
,V/DexLibLoader( 4175): Creating class loader
,V/DexLibLoader( 4175): Finished creating class loader
,V/DexLibLoader( 4175): Verifying classes from secondary dexes.
,D/DexLibLoader( 4175): DexLibLoader.ensureDexLoaded took 206 ms
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/Auth.Api.Credentials( 1966): [CredentialSyncAdapter] Unknown sync event.
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42d92c80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43506870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43506870): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42c85640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43688710): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 13851
D/libc    (  363): [NET]res_nsend:resplen=45
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1202): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): acquireWL(42e3c450): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 906 1000 WorkSource{10029}
,D/PMS     (  906): releaseWL(42c85640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/DelayedSyncController( 4200): Delaying sync.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43d67850): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43d67850): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43585718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/libc    ( 1351): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/libc    ( 1351): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1351): [NET] getaddrinfo-, 1
D/libc    ( 1351): [NET] getaddrinfo_proxy+
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] +++++ res_nsend xid =9689 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(41bb9db8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(42c83700): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/PMS     (  906): releaseWL(43585718): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42fae640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PhoneStatusBar( 1111): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42fae640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42db9f58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/Process (  906): killProcessQuiet, pid=3554
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/PMS     (  906): releaseWL(425438f0): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
,I/ActivityManager(  906): Killing 3554:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 3554
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42db9f58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4409e3c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4409e3c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/DriveInitializer( 1966): Awaiting to be initialized
W/DriveInitializer( 1966): Background init thread started
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 265
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1351): [NET] getaddrinfo_proxy-, success
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 1966): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/libc    ( 1351): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,W/DriveInitializer( 1966): Background init thread ended
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(437c12e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [4][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(4262d2b0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(437c12e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42b5dbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): releaseWL(42e3c450): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42e84898): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(42b5dbf8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42fca288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(42c83700): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43cdb598): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 906 1000 WorkSource{10096}
D/PMS     (  906): releaseWL(42fca288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43979e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/DelayedSyncController( 4200): Delaying sync.
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/libc    ( 1351): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1351): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/PMS     (  906): releaseWL(43979e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4276c3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(4276c3d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c4ac58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43cdb598): PARTIAL_WAKE_LOCK  *sync*/com.android.chrome/com.google/***** 0x1 WorkSource{10096}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43c8a670): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
D/PMS     (  906): releaseWL(43c4ac58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(44085c10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e84898): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10029}
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(435b5880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=4248 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/PMS     (  906): releaseWL(44085c10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4384d110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(4384d110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(426ecc88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(426ecc88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(43cc3de0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4248 10160 null
,D/PMS     (  906): acquireWL(433af5c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4248 10160 null
,D/PMS     (  906): releaseWL(43cc3de0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4248/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42fdf110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4248/10160)
,D/PMS     (  906): releaseWL(435b5880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): acquireWL(44028880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42fdf110): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c22258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43c22258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(433af5c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4408c2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(44028880): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): killProcessQuiet, pid=3211
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Killing 3211:com.htc.task/u0a71 (adj 15): empty #17
D/PMS     (  906): releaseWL(4408c2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    ( 1202): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1202): [NET] getaddrinfo-,err=8
D/libc    ( 1202): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1202): [NET] getaddrinfo-,err=8
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{43ec9af8: PendingIntentRecord{4401f6c8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360110213 win=-1 tElapsed=315360110213 maxElapsed=551880110212 interval=0 standalone=false
,I/ActivityManager(  906): Recipient 3211
,W/dalvikvm( 4175): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4175): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4175): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 1966): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
W/dalvikvm( 4175): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4175): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4175): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4175): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4408a800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43c8a670): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43c76948): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(4408a800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43c76808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43c76808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,W/PhenotypeConfigurator( 1202): Server returned 404
,D/PMS     (  906): releaseWL(442c3f88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4351fd88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(42e13628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43c76948): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(4351fd88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1111): removeIcon slot=sync_active index=7 viewIndex=0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(42e13628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425ddc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(425ddc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4175): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4175): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =660e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/FbInjectorInitializer( 4175): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,W/fb4a(:<default>):StaticBindingVerifier( 4175): Verify
,D/libc    ( 1966): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 1966): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 1966): [NET] getaddrinfo-, 1
D/libc    ( 1966): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =19a9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 261
D/libc    (  363): [NET]res_nsend:resplen=86
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1966): [NET] getaddrinfo_proxy-, success
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4175): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4175): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3821
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3821:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3821
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/AutoSetting( 1297): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4290 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1297): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1297): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1297/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1297/10055)
D/AutoSetting( 1297): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1297): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4175): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4175): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4175): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 1966): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/MobileConnectivityChangeReceiver( 4290): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4290): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4290): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4290): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4290/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4290/10079)
,D/PMS     (  906): acquireWL(41fb9a78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.NetworkChangeReceiver: pid=4304 uid=10098 gids={50098, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3357
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3357:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4290/10079)
,I/ActivityManager(  906): Recipient 3357
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(41ef4b70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1453535441479 min interval config: 0 actual interval: 520701563
D/PMS     (  906): releaseWL(41fb9a78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checking schedule, now: 1454056143050 next: 1453535471408
,I/CheckinService( 1966): active receiver: enabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1966, uid=10029, userID:0
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1454056075939
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,I/DeviceManagement( 4304): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4304 dbg=false s=true
,I/DeviceManagement( 4304): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.NetworkChangeWorkflow] args=[Bundle[{networkChangeIntent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.htc.cs.dm/.receiver.NetworkChangeReceiver (has extras) }}]]
,I/DeviceManagement( 4304): WorkflowService: Starting workflow service
,I/DeviceManagement( 4304): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b97d88] args=[Bundle[mParcelledData.dataSize=804]]
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4320 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4175): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4175): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [6][0][0]
E/dalvikvm( 4175): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4175): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4175): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4175): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4175): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4175): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4175): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4175): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4175): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/DeviceManagement( 4304): NetworkChangeWorkflow: ==================================================
I/DeviceManagement( 4304): NetworkChangeWorkflow: NetworkChange: networkAvailable=true
,I/DeviceManagement( 4304): NetworkChangeWorkflow: ==================================================
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
,W/dalvikvm( 4175): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4175): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4175): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
E/dalvikvm( 4175): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4175): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
I/DeviceManagement( 4304): ModelRegistry: Loading model meta data from resources...
W/dalvikvm( 4175): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4175): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/WifiService(  906): New client listening to asynchronous messages
,I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,I/DeviceManagement( 4304): SessionStateController: Checking invariants...
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 9.916MB for 39954-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4320): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4320): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4175): Grow heap (frag case) to 9.993MB for 79892-byte allocation
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 10.063MB for 84664-byte allocation
,I/DeviceManagement( 4304): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4304): SessionStateController: Checking invariants...
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4320/10151)
,V/WebViewChromiumFactoryProvider( 4320): Binding Chromium to main looper Looper (main, tid 1) {41b69a98}
,I/LibraryLoader( 4320): Expected native library version number "",actual native library version number ""
,I/chromium( 4320): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4320): Initializing chromium process, renderers=0
,I/DeviceManagement( 4304): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/PMS     (  906): acquireWL(43bf2410): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4320): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(4261ac18): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(43bf2410): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4320): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4320): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4320): Local Branch: 
I/Adreno-EGL( 4320): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4320): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4320):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,I/NSApplication( 4320): Starting up...
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42dfd2d0 u0 ReceiverList{426c9ce0 4175 com.facebook.katana/10027/u0 remote:42649d50}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e54708 u0 ReceiverList{42e546c8 4175 com.facebook.katana/10027/u0 remote:42bb8238}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4320/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4320/10151)
,I/DeviceManagement( 4304): Perf: *** Cache update - start...
,I/DeviceManagement( 4304): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4304): EnabledAppController: *** Updating enabled app database...
,I/DeviceManagement( 4304): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 4304): Perf: *** Config cache update - start...
I/DeviceManagement( 4304): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4304): ConfigCacheController: *** Updating stale config cache entries...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!,
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=3526
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/dalvikvm( 4304): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 4304): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4304): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4248/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4248/10160)
I/ActivityManager(  906): Killing 3526:com.google.android.gm/u0a107 (adj 15): empty #17
,D/ContactMessageStore( 1218): notify MmsSms
,D/AccFlag ( 1218): sense_version=6.0
,D/AccFlag ( 1218): sku_id=99
,W/System.err( 4304): Starting the internal HTTP client
D/PMS     (  906): acquireWL(4364a9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029}
V/AlarmManager(  906): sending alarm PendingIntent{43c032c0: PendingIntentRecord{43cd30d0 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
D/PMS     (  906): releaseWL(4364a9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.reportagent/versions/687983cc-3a99-4a94-8c51-4a06dce9d091/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNzE2Wg
D/PMS     (  906): acquireWL(42b86eb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
D/PMS     (  906): releaseWL(42b86eb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,I/iu.SyncManager( 1966): SYNC; picasa accounts
I/ActivityManager(  906): Recipient 3526
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/NetworkLogImpl( 1966): Loaded NetworkSpeedPredictor
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 28
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/AccFlag ( 1218): sku_id=99
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,I/iu.Environment( 1966): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 1966): num queued entries: 0
,I/iu.UploadsManager( 1966): num updated entries: 0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/iu.SyncManager( 1966): NEXT; no task
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/BuildInfo( 4304): Created new instance: com.htc.cs.lib.hms.BuildInfo@41e03e08
,I/DeviceManagement( 4304): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  906): getAllNetworkInfo called by com.test.thalitest (3893/10389)
,W/ContextImpl( 4175): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.android.phone ] tid: 35
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/PMS     (  906): acquireWL(43ead3c8): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/AlertReceiver( 3849): beginStartingService
,W/ContextImpl( 4175): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1351): [NET] getaddrinfo-, 1
,D/libc    ( 1351): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/libc    (  363): [NET] +++++ res_nsend xid =ce6c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(43d58c88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  906): acquireWL(43873878): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3849 10013 null
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4175): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
,D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d889 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  906): acquireWL(4359e198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 297
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1351): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4381 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,W/WeatherRequest( 1111): request cur loc, but there is no sys cur
,D/AlertService( 3849): start to updateAlertNotification!
D/PMS     (  906): releaseWL(42e840d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AlertService( 3849): No fired or scheduled alerts
,D/HtcAlertUtils( 3849): -- cancelReminderNotification --
,D/HtcAlertUtils( 3849): broadcastExistReminder!
,D/PMS     (  906): releaseWL(43873878): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): acquireWL(43ceb680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,W/AlertReceiver( 3849): stopSelfResult true
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4396 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 4381): can't get weather sync account
,I/VacuumService( 1202): Vacuum at: now=1454056143697 tag=VacuumService
,D/PMS     (  906): releaseWL(4359e198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42dfcdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(42dfcdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/WeatherRequest( 4381): request cur loc, but there is no sys cur
,W/Settings( 4381): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 9 17
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(43ceb680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4408ab90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(44088028): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4396 10071 null
,D/PMS     (  906): acquireWL(44087550): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4396 10071 null
,D/PMS     (  906): releaseWL(44088028): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=4412 uid=10090 gids={50090, 3003, 5012, 1028}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/TodoTaskshortcut( 4396): update TASK shortcut>
D/PMS     (  906): releaseWL(4408ab90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43f58e18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,I/TodoTaskNotifyService( 4396): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4424 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=15 [13][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/TodoTaskNotifyService( 4396): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 4396): stopSelfResult true
D/PMS     (  906): releaseWL(44087550): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/Process (  906): killProcessQuiet, pid=3577
I/WorldClock.Global( 4412): isHtcDevice = true
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3577:com.android.vending/u0a74 (adj 15): empty #17
,D/PMS     (  906): releaseWL(43f58e18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4424): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/ContextImpl( 3863): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/WorldClock.Global( 4412): isHtcDevice = true
W/dalvikvm( 4424): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4424): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4424): install
I/MultiDex( 4424): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/WorldClock.AlarmUtils( 4412): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/ActivityManager(  906): Recipient 3577
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/MultiDex( 4424): loading existing secondary dex files
,I/MultiDex( 4424): load found 3 secondary dex files
,I/MultiDex( 4424): install done
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4439 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 4412): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 4412): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1111): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43cf3800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/GCM     ( 1351): GCM config loaded
,D/TimeService( 4439): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454056144203
,D/Process (  906): killProcessQuiet, pid=3999
,W/dalvikvm( 4424): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,I/ActivityManager(  906): Killing 3999:com.htc.widget.process2/u0a50 (adj 15): empty #17
W/dalvikvm( 4424): VFY: unable to resolve instance field 36
W/dalvikvm( 4424): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,V/JNIHelp ( 4424): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Process (  906): killProcessQuiet, pid=3965
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Recipient 3999
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Killing 3965:com.htc.widget.hmsproc3/u0a40 (adj 15): empty #17
I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/PMS     (  906): acquireWL(42e695a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(425e0548): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
I/ActivityManager(  906): Recipient 3965
W/dalvikvm( 4304): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4304): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 4304): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 4304): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4304): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 4304): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4304): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 4304): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4304): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4304): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4304): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4304): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(425e0548): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1453535441479 min interval config: 0 actual interval: 520702783
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/dalvikvm( 1966): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
W/dalvikvm( 1966): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 1966): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
D/PMS     (  906): releaseWL(42e695a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4365d578): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1966 10029 null
,D/PMS     (  906): acquireWL(424730f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42c9d0a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  906): acquireWL(4254f840): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  906): releaseWL(43d58c88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): releaseWL(4365d578): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  906): releaseWL(4254f840): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42c9d0a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42630230): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43cf3800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4347e528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424730f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  906): releaseWL(4347e528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
D/PMS     (  906): acquireWL(426b1d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(426b1d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,I/ProviderInstaller( 4424): Installed default security provider GmsCore_OpenSSL
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(42630230): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.dm/versions/b5b04a47-d585-4433-9a63-6f3f39989144/cid/MDowOjIwMTMtMDktMzBUMTA6MzA6NTAuNjA2Wg
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=20 [5][1][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,W/dalvikvm( 4424): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4424): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e7da +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,W/dalvikvm( 4424): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4424): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4424): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4424): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4424): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4469 uid=10041 gids={50041}
,D/Process (  906): killProcessQuiet, pid=3985
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Delay finish: com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent
I/ActivityManager(  906): Killing 3985:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3985
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4424): Install completed successfully. count=14 extracted=0
,W/dalvikvm( 4424): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,W/dalvikvm( 4424): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4424): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4424): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4424): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 4424): Using platform SSLCertificateSocketFactory
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2456807480
,D/libc    ( 4424): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4424): [NET] getaddrinfo-,err=8
D/libc    ( 4424): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4424): [NET] getaddrinfo-, 1
,D/libc    ( 4424): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8640 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4424): [NET] getaddrinfo_proxy-, success
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Icing   ( 1966): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,D/libc    ( 4424): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4424): [NET] getaddrinfo-,err=8
D/libc    ( 4424): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4424): [NET] getaddrinfo-,err=8
,I/Icing   ( 1966): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
D/PMS     (  906): releaseWL(43ead3c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4079
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4079:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  906): acquireWL(424b4e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/PMS     (  906): acquireWL(4264b3e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4396 10071 null
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=11 [17][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [5][0][0]
D/PMS     (  906): acquireWL(423daae8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4396 10071 null
I/ActivityManager(  906): Recipient 4079
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(4264b3e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 4396): java.lang.NullPointerException
W/System.err( 4396): java.lang.NullPointerException
W/System.err( 4396): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4396): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4396): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
D/PMS     (  906): releaseWL(423daae8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,W/NotifyReceiver( 4396): stopSelfResult true
D/PMS     (  906): acquireWL(42d499e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4396 10071 null
D/PMS     (  906): acquireWL(4357e5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4396 10071 null
,D/PMS     (  906): releaseWL(42d499e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4396): java.lang.NullPointerException
W/System.err( 4396): java.lang.NullPointerException
W/System.err( 4396): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4396): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4396): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4396): stopSelfResult true
D/PMS     (  906): releaseWL(4357e5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  906): releaseWL(424b4e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/GCM     ( 1351): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=33 [3][1][0]
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(437ceaf0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4492 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  906): releaseWL(437ceaf0): PARTIAL_WAKE_LOCK  GCMSEND 0x1 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
,D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9142 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,I/Babel   ( 4492): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4492): MmsConfig.loadMmsSettings
,W/dalvikvm( 4492): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4492): VFY: unable to resolve instance field 36
,W/dalvikvm( 4492): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4517 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4492, uid=10111, userID:0
,W/Settings( 4492): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4517): onCreate
,D/MmsCustomizationProvider( 4517): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4517): GetPrviateResource
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4492, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4492, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4492, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4492, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4492, uid=10111, userID:0
V/GetPrviateResource( 4517): GetPrviateResource
D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/MmsCustomizationProvider( 4517): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4492): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4492): MmsConfig.loadFromDatabase
,E/Babel   ( 4492): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4492): MmsConfig.loadFromResources
,E/Babel   ( 4492): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4492): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver
,D/Process (  906): killProcessQuiet, pid=4110
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 4110:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ProviderInstaller( 4492): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.talk (4492/10111)
,D/MessageCustFlag( 4517): sense_version=6.0
,D/BTAccessoryUtil( 4517): createReceiver
,D/BTAccessoryUtil( 4517): registerReceiver return intent = null
D/MessageCustFlag( 4517): sku_id=99
,W/SystemReader( 4517): Cannot find message_ambs_application_id, use default value instead
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.talk (4492/10111)
,D/Messaging( 4517): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4517): networkCode: 
,D/MessageCustFlag( 4517): sku_id=99
D/MmsConfig( 4517): SIE smsPri: null
,D/MmsConfig( 4517): networkCode: 
,D/HtcTelephonyCapability( 4517): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4517): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4517): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4517): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  906): Recipient 4110
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
,I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=12 [31][4][0]
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =224b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success,
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4424/10029)
,W/Settings( 4424): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    ( 4492): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4492): [NET] getaddrinfo-,err=8
D/libc    ( 4492): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4492): [NET] getaddrinfo-, 1
,D/libc    ( 4492): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b914 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4492): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4492): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4492): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/Process (  906): killProcessQuiet, pid=3398
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3398:com.htc.musicenhancer/u0a53 (adj 15): empty #17
W/fb4a(:<default>):UserScope( 4175): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4175): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Recipient 3398
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/PMS     (  906): acquireWL(43d047f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10014}
,V/AlarmManager(  906): sending alarm PendingIntent{4384a3e0: PendingIntentRecord{437cd658 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=113933, Int=0
,E/fb4a(:<default>):LocalFbBroadcastManager( 4175): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027),
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/libc    ( 4175): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4175): [NET] getaddrinfo-,err=8
D/libc    ( 4175): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4175): [NET] getaddrinfo-, 1
,D/libc    ( 4175): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ed9e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,D/WVCdm   (  371): PrepareKeyRequest: nonce=640748644
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 29
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4175): [NET] getaddrinfo_proxy-, success
,I/global  ( 4175): call createSocket() return a new socket.
D/libc    ( 4175): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4175): [NET] getaddrinfo-, SUCCESS
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [11][0][0]
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =30e9 +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/PMS     (  906): releaseWL(4261ac18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4,
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1966): [NET] getaddrinfo-, 1
D/libc    ( 1966): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =112e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1966): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4175): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4175): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 10.992MB for 32784-byte allocation
D/PMS     (  906): acquireWL(43d68910): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4492 10111 null
,I/CheckinTask( 1966): Sending checkin request (13201 bytes)
,I/Babel   ( 4492): Account registration complete:Redacted-21
,D/PMS     (  906): releaseWL(43d68910): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,D/PMS     (  906): acquireWL(43c9b0f0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4175 10027 null
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=12 [40][5][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =98bd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4175/10027)
,D/Messaging( 4517): mNeedToUpdateDate2 start
,D/MmsConfig( 4517): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4517): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4517): 
D/MmsAsyncWorkHandler( 4517): HM tk = 20001
,D/ReportIndicatorCache( 4517): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4517): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b704f0
,I/Messaging( 4517): mccmnc> 
D/DraftCache( 4517): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4517): [DraftCache/1] refresh
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4517): networkCode: 
,D/Messaging( 4517): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4517): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4517): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4517): createReceiver
,D/MessageCustFlag( 4517): sense_version=6.0
,D/Jerry   ( 4517): start to preload cursor >>>>>>>
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1218): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
V/MmsProvider( 1218): Update uri=content://mms, match=0
,V/MmsProvider( 1218): selection=st=129 AND m_type!=134
,D/Messaging( 4517): Reset downloading state: 0
D/Messaging( 4517): mNeedToUpdateDate2: false
,V/MmsSystemEventReceiver( 4517): TransactionService is going to be woken up.
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1218): sku_id=99
,I/ActivityManager(  906): Delaying start of: ServiceRecord{43d221c0 u0 com.htc.sense.mms/.transaction.TransactionService}
D/DraftCache( 4517): [DraftCache/445] rebuildCache
D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/MmsSmsV2Provider( 1218):  phoneType = -1
,D/MmsSmsV2Provider( 1218): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4517): ViewCache CreatePreload
,D/Messaging( 4517): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4517): _has_set_default_values_2=true
,D/Messaging( 4517): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/Jerry   ( 1218): URI_DRAFT
,D/MsgPreferenceUtils( 4517): def_index: 0
,D/MsgPreferenceUtils( 4517): globalIndex = 1
D/MsgPreferenceUtils( 4517): phone state: true
D/MsgPreferenceUtils( 4517): sd state: false
,D/MsgPreferenceUtils( 4517): vIndex = 0
,D/DraftCache( 4517): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4517): [DraftCache/445] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4517): 
D/MmsAsyncWorkHandler( 4517): HM tk = 20002
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
,D/AccFlag ( 1218): sku_id=99
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1218): sku_id=99
,I/CheckinResponseProcessor( 1966): From server: 12 gservices updates and 1 deletes
,I/CertBlacklister(  906): Certificate blacklist changed, updating...
,I/CertBlacklister(  906): Certificate blacklist updated
,I/GservicesProvider( 1351): main difference update completed
,I/CheckinRequestBuilder( 1966): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4290/10079)
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
,I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=7 [14][1][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9ff9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [7][0][0]
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1454056148075 next: 1454579085058
,I/CheckinService( 1966): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1454056148096
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(41ef4b70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4320): Thread[GAThread,5,main]: No campaign data found.
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
,I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.csrecommend/versions/f26b54be-e9ca-4494-ba25-56712573f3ab/cid/MDoxMDoyMDE1LTA4LTI2VDEwOjE0OjI0LjczNVo
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [11][0][0]
I/global  ( 4175): I/O error closing connection
I/global  ( 4175): java.net.SocketException: Socket is closed
I/global  ( 4175): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4175): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4175): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4175): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4175): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4175): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4175): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4175): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4175): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4175): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4175): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4175): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4175): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4175): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4175): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4175): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4175): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4175): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4175): Removing a connection that never existed!
D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(43c9b0f0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3f3c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
,I/DeviceManagement( 4304): ConfigCacheController: Getting config update from server: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.sense.socialnetwork.facebook/versions/2adae5da-a4df-4cc3-b772-ea9aaa6301b2/cid/MDowOjIwMTUtMDQtMTVUMDk6MDM6NTguMjk2Wg
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,I/DeviceManagement( 4304): DeviceClientResource: Active network...
I/DeviceManagement( 4304):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=5 [18][1][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4304/10098)
,D/libc    ( 4304): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4304): [NET] getaddrinfo-,err=8
D/libc    ( 4304): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4304): [NET] getaddrinfo-, 1
,D/libc    ( 4304): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fa3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4304): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4304): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4304): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4304): DeviceClientResourceController: handleDirectives: []
I/System.out( 4304): isCompatible false
I/System.out( 4304): createObjectMapper
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
,I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false
I/System.out( 4304): isCompatible false,
,I/System.out( 4304): isCompatible false
,I/DeviceManagement( 4304): ConfigCacheController: *** Update config cache: updating 9 entries...
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, statusCode=0, authCode=0>
,I/DeviceManagement( 4304): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4304): AlarmController: Scheduling TTL alarm for: 2016.01.30 at 09:29:09.821 CET (due to: com.htc.launcher)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4304, uid=10098, userID:0
,I/DeviceManagement( 4304): Perf: *** Config cache update - complete: 6710 ms
,I/DeviceManagement( 4304): Perf: *** Cache update - complete: 6716 ms
,I/DeviceManagement( 4304): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.NetworkChangeWorkflow@41b97d88]
,I/DeviceManagement( 4304): WorkflowService: Stopping workflow service
,V/TransactionService( 4517): 1-Creating TransactionService
,V/TransactionService( 4517): onStartCommand: 1
,D/MmsSystemEventReceiver( 4517): unRegisterForConnectionStateChanges
V/TransactionService( 4517): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4517): Loading previous transactions.
,D/TelephUtils( 1218): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1218): device_type: 1
,D/TransactionService( 4517): Force set service start id to 1
,V/TransactionService( 4517): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4517): unRegisterForConnectionStateChanges
,V/TransactionService( 4517): Destroying TransactionService
,D/TransactionService( 4517): stopSelfResult: true, mLastHandledServiceId: 1
,D/Process (  906): killProcessQuiet, pid=3323
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3323:com.android.settings/1000 (adj 15): empty #17
V/TransactionService( 4517): 4-Handling incoming message: { when=-12ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/LocationInitializer( 1966): Restart initialization of location
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1202): location=null
,D/WearableService( 1202): callingUid 10029, callindPid: 1202
,D/AuthorizationBluetoothService( 1351): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1351): Proximity feature is not enabled.
D/PMS     (  906): acquireWL(424a0950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(424a0950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,E/MDM     ( 1202): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4606 uid=10078 gids={50078}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3323
,D/WifiService(  906): Client connection lost with reason: 4
,D/SMSBackup( 4606): Got a database change event,
,D/PMS     (  906): acquireWL(423de920): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1485 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(423de920): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(43d047f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10014}
,I/ActivityManager(  906): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4619 uid=10016 gids={50016, 3003, 5012, 2001}
,D/Process (  906): killProcessQuiet, pid=3375
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3375:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.music (pid 3375): Died!
,I/ActivityManager(  906): Recipient 3375
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4619): Update started
,I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4619): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4619): Update started
,I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/DownloadManager( 2157): Download 299 starting
D/PMS     (  906): acquireWL(43887630): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2157 10021 WorkSource{10016}
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
W/ActivityThread( 2157): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [17][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,E/UpdateRequestReceiver( 4619): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,E/UpdateRequestReceiver( 4619): Received malformed URL while handling Gservices.CHANGED_ACTION
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,E/UpdateRequestReceiver( 4619): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/PMS     (  906): acquireWL(43ce16d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2157 10021 WorkSource{10016}
,I/DownloadManager( 2157): Download 300 starting
,D/Process (  906): killProcessQuiet, pid=4175
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4650 uid=10032 gids={50032, 3003, 5012}
I/ActivityManager(  906): Killing 4175:com.facebook.katana/u0a27 (adj 15): empty #17
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 2157): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/libc    ( 2157): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e3b4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f34 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 264
D/libc    (  363): [NET]res_nsend:resplen=49
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): acquireWL(439536d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4650, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4650, uid=10032, userID:0
,D/PMS     (  906): releaseWL(439536d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4650, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4650, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4650, uid=10032, userID:0
,D/PMS     (  906): acquireWL(42688078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42688078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 4175
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(43d35778): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43d35778): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43cf7e50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43cf7e50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): acquireWL(4253af60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4253af60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43d11578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43d11578): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  906): acquireWL(42f18a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f18a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4290
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4290:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4290
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4673 uid=10079 gids={50079, 3003, 5012}
,I/DownloadManager( 2157): Ignoring Content-Length since Transfer-Encoding is also defined
E/PhoneMonitor( 4673): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4673): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4673/10079)
,D/PMS     (  906): acquireWL(442c3f88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=4200
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4200:com.android.chrome/u0a96 (adj 15): empty #17
,I/ContactAccountLoggerTas( 2573): canRun() : Opted Out
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4673/10079)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4673/10079)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=15 [13][2][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/Search.GservicesUpdateTask( 2573): Updating Gservices keys
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4408e0c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
I/ActivityManager(  906): Recipient 4200
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(442c3f88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1454056148096 min interval config: 0 actual interval: 3088
,D/Process (  906): killProcessQuiet, pid=4304
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/CheckinService( 1966): Checking schedule, now: 1454056151212 next: 1454056178058
,I/CheckinService( 1966): active receiver: disabled
I/ActivityManager(  906): Killing 4304:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/PMS     (  906): releaseWL(4408e0c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/GStaticConfiguration( 2573): #getNewConfigurationUrl [pref=2015_09_15_14_04_18, gservice=2016_01_27_20_58_17
,I/DownloadManager( 2157): Download 300 finished with status SUCCESS
D/libc    ( 2573): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2573): [NET] getaddrinfo-,err=8
D/libc    ( 2573): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2573): [NET] getaddrinfo-, 1
,D/libc    ( 2573): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d80b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2573): [NET] getaddrinfo_proxy-, success
D/PMS     (  906): releaseWL(43ce16d0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.googlequicksearchbox (2573/10086)
,I/ActivityManager(  906): Recipient 4304
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DownloadManager( 2157): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=20 [24][5][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2157): Download 299 finished with status SUCCESS
D/PMS     (  906): releaseWL(43887630): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/libc    ( 2573): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
,D/libc    ( 2573): [NET] getaddrinfo-,err=8
,I/ContactAccountLoggerTas( 2573): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2573): canRun() : Opted Out
,I/GAV4    ( 4492): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, state=2, flag=1, pid=4492, uid=10111, userID:0
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/Process (  906): killProcessQuiet, pid=4320
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4320:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/PMS     (  906): acquireWL(4244e510): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e01110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1454056148096 min interval config: 0 actual interval: 3733
D/PMS     (  906): releaseWL(4244e510): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checking schedule, now: 1454056151835 next: 1454056178058
,I/CheckinService( 1966): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,I/SystemUpdateService( 1966): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1966): onCreate
D/PMS     (  906): acquireWL(425055c0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42e01110): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
,D/SystemUpdateService( 1966): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4248, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4248, uid=10160, userID:0
,I/SystemUpdateService( 1966): cancelUpdate (empty URL)
,I/SystemUpdateService( 1966): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
,I/ActivityManager(  906): Recipient 4320
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SQLiteConnectionPool( 1966): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/SystemUpdateService( 1966): onDestroy
D/PMS     (  906): releaseWL(425055c0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,E/DynamiteModule( 1966): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1966): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1966): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1966): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1966): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1966): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1966): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 1966): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 1966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1966): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 1966): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 1966): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1966): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 1966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 1966): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1966): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1966): Selected local version of com.google.android.gms.flags
,D/PMS     (  906): acquireWL(43503830): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/SystemEventReceiver( 1966): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1966): Updating ocr activity enabled=false
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=1966, uid=10029, userID:0
,D/PMS     (  906): releaseWL(43503830): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1202, uid=10029, userID:0
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43645a10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/OcrModelManager( 1966): Updating downloaded model state (gservices changed)
,D/GCM     ( 1351): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/PMS     (  906): acquireWL(42663788): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=1966, uid=10029, userID:0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(43645a10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428f44b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(428f44b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1111): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(424b9fe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42663788): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1111): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(424b9fe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1111): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1202): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1202): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  906): acquireWL(44013a88): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{424f9490: PendingIntentRecord{424f9458 com.google.android.gms startService}}) : type=2 triggerAtTime=315360121123 win=-1 tElapsed=315360121123 maxElapsed=551880121122 interval=0 standalone=false
,I/GCoreUlr( 1202): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1202): DispatchingService.onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(44088f08): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.google.android.talk
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=38, title=Hangouts, componentNameComponentInfo{com.google.android.talk/com.google.android.talk.SigningInActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.htc.cs.dm
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/Launcher( 1247): Deferring update until onResume
,D/Launcher( 1247): waitUntilResume // bindAppsUpdated
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 1202): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1247): Deferring update until onResume
,D/Launcher( 1247): waitUntilResume // bindAppsUpdated
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/DownloadManager( 2157): Download 301 starting
D/PMS     (  906): acquireWL(43931b80): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2157 10021 WorkSource{10016}
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  906): Resuming delayed broadcast
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
D/PMS     (  906): acquireWL(43587048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43587048): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
,E/ctxmgr  ( 1202): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/DownloadManager( 2157): Ignoring Content-Length since Transfer-Encoding is also defined
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PMS     (  906): acquireWL(42ceddf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [16][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/PMS     (  906): acquireWL(43d5be78): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2157 10021 WorkSource{10016}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,I/DownloadManager( 2157): Download 302 starting
,W/PackageManager(  906): Unable to load service info ResolveInfo{42a06dd8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getAllNetworkInfo called by  (2157/10021)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/PackageManager(  906):   Scheme: "mmsto"
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  906): acquireWL(43bf4388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/DownloadManager( 2157): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  906): releaseWL(42ceddf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ctxmgr  ( 1202): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ctxmgr  ( 1202): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/PMS     (  906): releaseWL(44013a88): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=3 [31][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2157/10021)
D/PMS     (  906): acquireWL(4365ac10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
,I/DownloadManager( 2157): Download 301 finished with status SUCCESS
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
D/PMS     (  906): releaseWL(43931b80): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/PMS     (  906): releaseWL(4365ac10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43995bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(43995bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4429fa68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(4429fa68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4408d248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43c49520 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
I/DownloadManager( 2157): Download 302 finished with status SUCCESS
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43d5be78): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(4408d248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(435182d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,I/[PluginManager]RegisterService( 1297): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.talk
,I/[PluginManager]RegisterService( 1297): handle notify Blinkfeed plugin client changed
,D/PMS     (  906): releaseWL(435182d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/IcingCorporaProvider( 2573): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,D/PMS     (  906): acquireWL(42f14638): PARTIAL_WAKE_LOCK  AsyncService 0x1 4248 10160 null
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42f14638): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,I/ActivityManager(  906): Resuming delayed broadcast
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4744 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/GCoreUlr( 1202): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42583618): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2573): UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,D/PMS     (  906): releaseWL(42583618): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1202): Unbound from all location providers
I/GCoreUlr( 1202): Place inference reporting - stopped
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(44088f08): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,D/HtcFingerPrintQuickLaunchProvider( 4744): -onCreate()
,I/ContactAccountLoggerTas( 2573): canRun() : Opted Out
,V/Settings:HtcSettingsApplication( 4744): [4744/4744] onCreate()
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4759 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3849
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3849:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3849
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GCoreUlr( 1202): DispatchingService.onDestroy()
,I/GCoreUlr( 1202): Stopping handler for UlrDispSvcFast
,D/PMS     (  906): acquireWL(425fac48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/PhenotypeConfigurator( 1202): Scheduling Phenotype for one-off execution 13898 seconds from now (1454056154211)
,I/GCoreUlr( 1202): Unbound from all location providers
,I/GCoreUlr( 1202): Place inference reporting - stopped
D/PMS     (  906): releaseWL(425fac48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/GetConfigurationSnapshotOperation( 1202): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 4744): id/is att sku: 99/false
,I/PhenotypeFlagCommitter( 1202): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4759, uid=10074, userID:0
,W/SystemReader( 4744): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,W/SystemReader( 4744): Cannot find support_harman, use default value instead
,W/SystemReader( 4744): Cannot find effect_manager_id, use default value instead
,D/Finsky  ( 4759): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4759/10074)
E/Settings:HtcWrapHeaderInfo( 4744): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4744): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4744): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4744): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]support         :false
,W/FingerprintManager( 4744): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4744): isSupportVoWifi: null
E/ActivityThread( 4744): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4759/10074)
,W/PackageManager(  906): Unable to load service info ResolveInfo{42e3b1b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/Finsky  ( 4759): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,W/Settings( 4759): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4759): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4744): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4744): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4744): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportRecentAppsButton]support         :false
,I/GCoreNlp( 1202): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4744): [supportHomeButton]support         :false
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4759, uid=10074, userID:0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
,W/FingerprintManager( 4744): hasFingerprint() - sSensorCode = 0
,W/PackageManager(  906): Unable to load service info ResolveInfo{4363b1b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4744): isSupportVoWifi: null
E/ActivityThread( 4744): Failed to find provider info for com.htc.vowifi
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/PMS     (  906): acquireWL(442add20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(442add20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/Ads     ( 4759): Skipping gmscore version check
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4759): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4759): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4759): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,W/dalvikvm( 4759): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4759): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  906): acquireWL(42d7e708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/libc    ( 1202): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1202): [NET] getaddrinfo-,err=8
D/libc    ( 1202): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1202): [NET] getaddrinfo-, 1
,D/libc    ( 1202): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5123 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/LocationProviderProxy(  906): applying state to connected service
,D/PMS     (  906): releaseWL(42d7e708): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  906): acquireWL(43cf1d50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(438b08a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4492 10111 null
,D/PMS     (  906): acquireWL(43c11d28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(435fffd0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43c11d28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(438b08a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  906): releaseWL(435fffd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 +
I/Prism.WidgetManager( 1247): onLoadItems() +
,D/Process (  906): killProcessQuiet, pid=4381
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4381:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1966, uid=10029, userID:0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1202): [NET] getaddrinfo_proxy-, success
I/[PluginManager]RegisterService( 1297): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1297): handle notify Blinkfeed plugin client changed
,D/PMS     (  906): acquireWL(43492918): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 4381
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43492918): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2573): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PMS     (  906): releaseWL(43cf1d50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42a1cb18): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43cfaf50): PARTIAL_WAKE_LOCK  AsyncService 0x1 4248 10160 null
,D/PMS     (  906): releaseWL(43cfaf50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/[PluginManager]RegisterService( 1297): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.cs.dm
,I/[PluginManager]RegisterService( 1297): handle notify Blinkfeed plugin client changed
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  906): acquireWL(42e7bb98): PARTIAL_WAKE_LOCK  AsyncService 0x1 4248 10160 null
D/libc    ( 4759): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4759): [NET] getaddrinfo-,err=8
D/libc    ( 4759): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4759): [NET] getaddrinfo-, 1
D/libc    ( 4759): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c53 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4759): [NET] getaddrinfo_proxy-, success
D/PMS     (  906): releaseWL(42e7bb98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.cs.dm
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1966, uid=10029, userID:0
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4619): Update downloaded, starting installation
,I/UpdateFetcherService( 4619): Started installation
,W/ContextImpl( 4619): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4619): Update downloaded, starting installation
I/UpdateFetcherService( 4619): Started installation
D/libc    ( 1202): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1202): [NET] getaddrinfo-,err=8
D/libc    ( 1202): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1202): [NET] getaddrinfo-,err=8
,I/ConfigUpdateInstallReceiver(  906): Not installing, new version is <= current version
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 -
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [23][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/IcingCorporaProvider( 2573): UpdateCorporaTask done [took 456 ms] updated apps [took 456 ms] 
,I/IcingCorporaProvider( 2573): Updating corpora: APPS=com.htc.cs.dm, CONTACTS=MAYBE
,I/IcingCorporaProvider( 2573): UpdateCorporaTask done [took 51 ms] updated apps [took 50 ms] 
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4759): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4759): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  906): acquireWL(42ecdb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{426c2d38: PendingIntentRecord{4389e228 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454056155436, Int=0
D/PMS     (  906): releaseWL(42ecdb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4759/10074)
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4759): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4759): [NET] getaddrinfo-,err=8
D/libc    ( 4759): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4759): [NET] getaddrinfo-, 1
,D/libc    ( 4759): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1fac +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4759): [NET] getaddrinfo_proxy-, success
I/global  ( 4759): call createSocket() return a new socket.
D/libc    ( 4759): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4759): [NET] getaddrinfo-, SUCCESS
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1218): -- N1 =0
,D/PhoneApp( 1218): -- N2 =0
,D/PhoneApp( 1218): -- N3 =0
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=25 [16][4][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,I/Icing   ( 1966): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms,
,D/libc    ( 4759): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4759): [NET] getaddrinfo-,err=8
,D/Icing   ( 1966): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1966): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/Icing   ( 1966): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,I/Icing   ( 1966): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42a1cb18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1202/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
,W/NetworkManagementSocketTagger( 4759): untagSocket(72) failed with errno -22
,D/Finsky  ( 4759): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/PMS     (  906): releaseWL(43bf4388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43d09730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(43d09730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43cfabb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [7][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(43cfabb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
,W/NetworkManagementSocketTagger( 4759): untagSocket(72) failed with errno -22
,I/GAV2    ( 4248): Thread[GAThread,5,main]: No campaign data found.
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 -
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4759): untagSocket(72) failed with errno -22
,D/Finsky  ( 4759): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.maps to true
,D/Finsky  ( 4759): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to true
,D/Finsky  ( 4759): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.marvin.talkback to true
,D/Finsky  ( 4759): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.marvin.talkback from  to d_AAAAAAADF8w=
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4759/10074)
,D/Finsky  ( 4759): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(4265f6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{4406d938: PendingIntentRecord{41d32980 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454056158594, Int=0
,D/WearableService( 1202): callingUid 10029, callindPid: 1202
,D/Finsky  ( 4759): [492] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  906): acquireWL(42688220): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4759 10074 null
D/PMS     (  906): releaseWL(4265f6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/DeviceConnectionService( 1202): client connected with version: 8296000
,D/Finsky  ( 4759): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 4759): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4759/10074)
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.vending.verifier.VerifyInstalledPackagesReceiver
,D/Finsky  ( 4759): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4759): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 -
,D/PMS     (  906): releaseWL(42688220): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,W/PackageSettings(  906): Skipping PackageSetting{42254f00 com.example.hello/10397} due to missing metadata
,D/PMS     (  906): acquireWL(42e1b3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42e1b3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43883ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42e3ce18: PendingIntentRecord{42f4dfd0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137271, Int=0
,D/PMS     (  906): releaseWL(43883ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  906): acquireWL(42e0b160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c5b470: PendingIntentRecord{42558c68 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=139124, Int=0
,D/PMS     (  906): acquireWL(43bedba8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e0b160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43849328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43bedba8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43849328): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1297): service - mHandler: update timezone
,D/AutoSetting( 1297): service - handleMessage() stop self
,D/AutoSetting( 1297): service - handleMessage() quit looper
,D/AutoSetting( 1297): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4412
,I/ActivityManager(  906): Killing 4412:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4412
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1485): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1485): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1485): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1485): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1485): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1485): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1485): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1485): service - mHandler: update timezone
,D/AutoSetting( 1485): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1485): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1485): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1485): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1528): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41f1cb78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 2 11 3 11
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/PMS     (  906): acquireWL(43938920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4238d5c0: PendingIntentRecord{422d0658 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141416, Int=0
D/PMS     (  906): acquireWL(426e8608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
V/AlarmManager(  906): sending alarm PendingIntent{426c7068: PendingIntentRecord{426f4130 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454056172538, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42581818: PendingIntentRecord{42fe4ee0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454056178058, Int=522937000
D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  906): acquireWL(435f0fc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43938920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a058 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/CheckinService( 1966): Checkin interval check for package: unspecified last checkin: 1454056148096 min interval config: 0 actual interval: 30021
D/PMS     (  906): acquireWL(42df86c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(435f0fc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1966): Checking schedule, now: 1454056178142 next: 1454056178058
,I/CheckinService( 1966): active receiver: enabled,
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1966, uid=10029, userID:0
,I/CheckinService( 1966): Preparing to send checkin request
,I/EventLogService( 1966): Accumulating logs since 1454056143079
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,I/CheckinRequestBuilder( 1966): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 58
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=6 [62][4][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/Finsky  ( 4759): [482] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4759): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3169538105
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4424/10029)
,W/Settings( 4424): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1051469107
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4424): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4424): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4424): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4424): Local Branch: 
I/Adreno-EGL( 4424): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4424): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4424):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 1966): [NET] getaddrinfo-, 1
,D/libc    ( 1966): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  363): [NET] +++++ res_nsend xid =ca5b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1966): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,D/libc    ( 1966): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1966): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1966): Sending checkin request (12247 bytes)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/CheckinRequestBuilder( 1966): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1966): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1966/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 3998): environment dirty rate=0 [62][0][0]
,I/CheckinRequestBuilder( 1966): Classify the device as Phone.
,I/CheckinTask( 1966): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1966): Checking schedule, now: 1454056181718 next: 1454579118712
,I/CheckinService( 1966): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1966, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023844
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023990
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024066
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024069
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024072
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024076
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025476
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028392
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360110213
,D/CheckinService( 1966): Recording last checkin time for package unspecified as 1454056181740
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360121123
,D/PMS     (  906): releaseWL(42df86c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1966/10029)
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): releaseWL(426e8608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{425e2b10 u0 com.htc.htclocationservice/.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,D/PMS     (  906): acquireWL(43473cb8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4492 10111 null
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/dalvikvm-heap( 1247): Grow heap (frag case) to 12.648MB for 53840-byte allocation
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1247): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/[PluginManager]RegisterService( 1297): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1297): handle notify Blinkfeed plugin client changed
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1247): Deferring update until onResume
,D/Launcher( 1247): waitUntilResume // bindAppsUpdated
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
D/PMS     (  906): releaseWL(43473cb8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/IcingCorporaProvider( 2573): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  906): acquireWL(4357d1c0): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43d38be0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4248 10160 null
,D/PMS     (  906): releaseWL(43d38be0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 1966): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/Icing   ( 1966): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2573): UpdateCorporaTask done [took 1129 ms] updated apps [took 1129 ms] 
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
,I/Icing   ( 1966): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/PackageManager(  906): Unable to load service info ResolveInfo{43cdaee8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Icing   ( 1966): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(4357d1c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1218): -- N1 =0
,D/PhoneApp( 1218): -- N2 =0
,D/PhoneApp( 1218): -- N3 =0
,E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
,I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 -
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1202): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  906): acquireWL(433bcd00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(433bcd00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42f30b38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42f30b38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(43d6b988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(438af060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms},
D/PMS     (  906): releaseWL(43d6b988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(438af060): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(442f1fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(442f1fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43f45d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422615f0: PendingIntentRecord{41e72790 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=168200, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f45d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43f054b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): acquireWL(43d69978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,V/AlarmManager(  906): sending alarm PendingIntent{41c5b470: PendingIntentRecord{42558c68 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=169202, Int=0
,D/PMS     (  906): releaseWL(43d69978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43d4e6b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=14 [7][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 3998): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 3998): nl80211: survey data missing!
E/wpa_supplicant( 3998): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 3998): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4383e4f8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(43f054b8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(43d4e6b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43799f68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43799f68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.android.contacts.metadata
E/ActivityThread( 1966): Failed to find provider info for com.android.contacts.metadata
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42fab4d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 24402, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  906): not retrying sync operation because the error is a hard error:  u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 169274, reason: UserStart
D/PMS     (  906): releaseWL(4383e4f8): PARTIAL_WAKE_LOCK  *sync*/com.android.contacts.metadata/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  906): releaseWL(42fab4d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42dec448): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1540/10029)
D/PMS     (  906): releaseWL(42dec448): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
,D/AutoSetting( 1485): service - handleMessage() stop self
,D/AutoSetting( 1485): service - onDestroy() END
,D/AutoSetting( 1485): service - handleMessage() quit looper
,D/TelephonyReceiver( 1218): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4267bb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4267bb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PowerUI ( 1111): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4263b118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c5b470: PendingIntentRecord{42558c68 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=199249, Int=0
,D/PMS     (  906): acquireWL(42636bc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(4263b118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42626ed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42636bc8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42626ed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(424a2648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424a2648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428eead0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422615f0: PendingIntentRecord{41e72790 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=228200, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428eead0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425aef60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425aef60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4248bae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1528): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1528): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4248bae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424497f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422615f0: PendingIntentRecord{41e72790 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=288200, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424497f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 3893): --= Surplus to requirements =--
I/jxcore-log( 3893): 
I/jxcore-log( 3893): ****TEST TOOK:  ms ****
I/jxcore-log( 3893): 
,I/jxcore-log( 3893): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3893): 
,E/cutils-trace( 4894): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4894): ====startRecUseTime====
D/htc.customization.log.level( 4894):  is 
,W/CustomizationLogLevel( 4894): Level value is invalid, use default level 2
,D/CustomizationManager( 4894):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4894): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4894): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4894): Parsing tag category name = system
,I/CustomizationCIDLoader( 4894): Parsing tag category name = application
I/CustomizationCIDLoader( 4894): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4894): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4894): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4894): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4894): Parsing tag category name = Settings
D/CustomizationManager( 4894):  Read CID file spent 0.123 (s)
,D/CustomizationManager( 4894):  All configurations done spent 0.123 (s)
,W/HtcNativeFlag( 4894): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4894): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4894): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4894): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4894, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=3893
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906): Killing 3893:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  906):   Force finishing activity ActivityRecord{42dd6998 u0 com.test.thalitest/.MainActivity t2}
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1188): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3893 uid 10389
,W/PackageSettings(  906): Skipping PackageSetting{42254f00 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/WindowState(  906): WIN DEATH: Window{4382acb8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1528): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1528): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1318): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(42f19458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,D/VoicemailCleanupService( 1264): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PMS     (  906): releaseWL(42f19458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/Launcher( 1247): Deferring update until onResume
,D/Launcher( 1247): waitUntilResume // bindAppsRemoved
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/AccTypeManager( 1318): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1318): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/[PluginManager]RegisterService( 1297): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1297): handle notify Blinkfeed plugin client changed
,W/SystemReader( 1234): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 1318): Unsupported attribute readOnly
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/IcingCorporaProvider( 2573): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4910 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  906): acquireWL(43955c38): PARTIAL_WAKE_LOCK  Icing 0x1 1966 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2573): UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
,E/SQLiteDatabase( 4910): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4910): 	at java.lang.reflect.Method.invoke(Method.java:515),
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4910): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4910): Couldn't open ClientFlag.db for writing (will try read-only):
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
,W/SQLiteOpenHelper( 4910): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4910): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
,W/dalvikvm( 4910): threadid=11: thread exiting with uncaught exception (group=0x41739e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
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
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,D/Process ( 4910): killProcess, pid=4910
,D/Process ( 4910): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4928 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 4910
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4910) has died.
,W/ContextImpl( 4928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4941 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
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
,W/dalvikvm( 4928): threadid=10: thread exiting with uncaught exception (group=0x41739e30)
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
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4928): killProcess, pid=4928
,D/Process ( 4928): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 4941): getInstance(Context context)
,E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454056327095.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
,D/AppTag  ( 4941): getInstance(Context context)
,D/AppTag  ( 4941): onCreate()
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(425698f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4248 10160 null
,D/PMS     (  906): releaseWL(425698f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Recipient 4928
,I/ActivityManager(  906): Process com.android.keychain (pid 4928) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3863
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 3863:com.android.settings:remote/1000 (adj 15): empty #17
W/dalvikvm( 4759): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,I/ActivityManager(  906): Recipient 3863
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 1966): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,V/BluetoothSapService( 3939): onUnbind: android.bluetooth.IBluetoothSap
D/WifiService(  906): Client connection lost with reason: 4
,D/AccountUtils( 1966): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/ChimeraCfgMgr( 1966): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1966): Module APK com.google.android.play.games already loaded
,I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bfbe10 +
,I/Prism.WidgetManager( 1247): onLoadItems() +
,I/LocationSettingsChecker( 1966): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 1966): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1966): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1966): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d5c5c70
,E/SQLiteDBG( 1966): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6d584c70
,W/dalvikvm( 1966): threadid=28: thread exiting with uncaught exception (group=0x41739e30)
,E/DriveAsyncService( 1966): disk I/O error (code 3850)
E/DriveAsyncService( 1966): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1966): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1966): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1966): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1966): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 1966): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1966): Process: com.google.android.gms, PID: 1966
E/AndroidRuntime( 1966): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1966): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1966): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1966): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1966): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1966): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1966): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1966): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1966): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1966): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms
D/Process ( 1966): killProcess, pid=1966
D/Process ( 1966): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,I/ActivityManager(  906): Recipient 1966
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): handleWLDeath(43955c38): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Process com.google.android.gms (pid 1966) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
,I/ActivityManager(  906): Resuming delayed broadcast
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20991ms
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20990ms
,E/SQLiteLog( 1351): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1351): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x6610f6a0
,W/dalvikvm( 1351): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
,E/AndroidRuntime( 1351): FATAL EXCEPTION: main
E/AndroidRuntime( 1351): Process: com.google.process.gapps, PID: 1351
E/AndroidRuntime( 1351): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1351): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1351): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1351): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1351): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1351): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1351): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1351): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1351): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1351): 	... 10 more
,E/ActivityManager(  906): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,D/Process ( 1351): killProcess, pid=1351
,D/Process ( 1351): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4973 uid=10098 gids={50098, 3003, 5012}

```
