#### Test 5065027857de7f1_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 2015): GC_EXPLICIT freed 1295K, 41% free 10292K/17224K, paused 2ms+4ms, total 34ms
D/AndroidRuntime( 3574): 
D/AndroidRuntime( 3574): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3574): CheckJNI is OFF
D/dalvikvm( 3574): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3574): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3574): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3574): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3574): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3574): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3574): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3574): failed to load memtrack module: -2
D/AndroidRuntime( 3574): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3574
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3591 uid=10464 gids={50464, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3574): Shutting down VM
D/dalvikvm( 3574): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3591): Binding Chromium to main looper Looper (main, tid 1) {41f23bd8}
I/LibraryLoader( 3591): Expected native library version number "",actual native library version number ""
I/chromium( 3591): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3591): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d156d8:true
D/BluetoothAdapter( 3591): 1106478152: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3591): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3591): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3591): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3591): Local Branch: 
I/Adreno-EGL( 3591): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3591): Local Patches: NONE
I/Adreno-EGL( 3591): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3591): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3591): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3591): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3591): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3591): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3591): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3591): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3591): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3591): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3591): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3591): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3591): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3591): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3591): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3591): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3591): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3591): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3591): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3591): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3591): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3591): Enabling debug mode 0
,W/AwContents( 3591): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3591): showStatusIcon on inactive InputConnection
I/SFPerfTracer(  274):      triggers: (rate: 1:31) (compose: 0:4) (post: 0:1) (render: 0:4) (0:125 frames) (1:535)
D/SFPerfTracer(  274):        layers: (0:13) (FocusedStackFrame: 1:9)* (StatusBar: 0:195)* (NavigationBar: 0:41)* (com.android.systemui.ImageWallpaper: 0:6)* (com.android.launcher/com.android.launcher2.Launcher: 0:9)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:11)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:2)* 
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,403
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +377ms (total +403ms)
,D/JsMessageQueue( 3591): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3591): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f282e8
,D/dalvikvm( 3591): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f282e8
,D/jxcore_app_log( 3591): JniHelper::setJavaVM(0x41577fa8), pthread_self() = 1613928136
,D/JX-Cordova( 3591): jxcore cordova android initializing
,I/dalvikvm( 3591): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3591): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3591): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3591): GC_CONCURRENT freed 2810K, 17% free 14366K/17224K, paused 3ms+2ms, total 63ms
,D/dalvikvm( 3591): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 113K, 17% free 14366K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 130K, 17% free 14387K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 16.174MB for 96598-byte allocation
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 184K, 17% free 14421K/17320K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 16.254MB for 144892-byte allocation
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 258K, 18% free 14468K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 16.370MB for 217334-byte allocation
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 369K, 18% free 14542K/17680K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 16.544MB for 325996-byte allocation
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 571K, 19% free 14665K/18000K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 16.820MB for 488990-byte allocation
,W/PluginManager( 3591): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 872K, 20% free 14841K/18480K, paused 26ms, total 26ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 1291K, 19% free 15099K/18480K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 17.827MB for 1100216-byte allocation
,D/dalvikvm( 3591): GC_CONCURRENT freed 1721K, 21% free 15478K/19556K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 340K, 22% free 15424K/19556K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 18.669MB for 1650320-byte allocation
,D/dalvikvm( 3591): GC_CONCURRENT freed 1740K, 25% free 16020K/21168K, paused 1ms+4ms, total 42ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 1336K, 25% free 16075K/21168K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 20.091MB for 2475476-byte allocation
,D/dalvikvm( 3591): GC_CONCURRENT freed 201K, 22% free 18441K/23588K, paused 5ms+3ms, total 50ms
,D/dalvikvm( 3591): GC_CONCURRENT freed 4438K, 28% free 17058K/23588K, paused 3ms+6ms, total 46ms
,D/dalvikvm( 3591): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/dalvikvm-heap( 3591): Grow heap (frag case) to 22.232MB for 3713210-byte allocation
,D/dalvikvm( 3591): GC_CONCURRENT freed 340K, 25% free 20642K/27216K, paused 5ms+6ms, total 70ms
,D/dalvikvm( 3591): GC_FOR_ALLOC freed 3187K, 34% free 17997K/27216K, paused 28ms, total 28ms
,W/jxcore-log( 3591): Initializing JXcore engine
,W/jxcore-log( 3591): JXcore engine is ready
,D/dalvikvm( 3591): GC_CONCURRENT freed 354K, 25% free 20620K/27216K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 3591): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3591): Starting JXcore engine
,W/jxcore-log( 3591): Platform android
W/jxcore-log( 3591): 
,W/jxcore-log( 3591): Process ARCH arm
W/jxcore-log( 3591): 
,I/jxcore-log( 3591): JXcore Cordova bridge is ready!
I/jxcore-log( 3591): 
,W/jxcore-log( 3591): JXcore engine is started
,I/chromium( 3591): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3591): Toggling radios to true
I/jxcore-log( 3591): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1017): Message: 1
,D/BluetoothManagerService( 1017): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1242): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1017): New client listening to asynchronous messages
D/WifiService( 1017): setWifiEnabled: true pid=3591, uid=10464
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
,W/XTWiFiOS( 1260): Active network info is not available
,I/ActivityManager( 1017): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3638 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/Settings( 1242): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1242): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1017): setting operational mode to 1
D/WifiStateMachine( 1017): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1017): processMsg: InitialState
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1242): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3591): Radios toggled
I/jxcore-log( 3591): 
D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3591): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3591): 
,I/jxcore-log( 3591): Perf Test app loaded loaded
I/jxcore-log( 3591): 
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1260): Active network info is not available
,I/jxcore-log( 3591): check test folder
I/jxcore-log( 3591): 
,I/jxcore-log( 3591): found test : ./testFindPeers.js
I/jxcore-log( 3591): 
,I/jxcore-log( 3591): found test : ./testSendData.js
I/jxcore-log( 3591): 
,D/AdapterServiceConfig( 3638): Adding HeadsetService
,D/AdapterServiceConfig( 3638): Adding A2dpService
D/AdapterServiceConfig( 3638): Adding HidService
D/AdapterServiceConfig( 3638): Adding HealthService
D/AdapterServiceConfig( 3638): Adding PanService
D/AdapterServiceConfig( 3638): Adding GattService
,D/AdapterServiceConfig( 3638): Adding BluetoothMapService
,D/BluetoothAdapterService( 3638): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d64478:true
,D/BluetoothAdapterState( 3638): make
,I/BluetoothAdapterState( 3638): Entering OffState
,I/bluedroid( 3638): init
,I/bte_conf( 3638): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3638): get_profile_interface socket
,D/BluetoothManagerService( 1017): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1017): Message: 40
,D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3638): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3638): config_hci_snoop_log
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1017): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterProperties( 3638): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1017): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1017): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3638): Name is: XT1039
D/BluetoothAdapterState( 3638): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3638): Setting state to 11
I/BluetoothAdapterState( 3638): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3638): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1017): Message: 60
D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1017): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3638): make
,I/BluetoothBondStateMachine( 3638): StableState(): Entering Off State
,I/ActivityManager( 1017): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3675 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1235): Proxy object connected
D/BluetoothHeadset( 1017): Proxy object connected
D/BluetoothHeadset( 1235): Proxy object connected
D/BluetoothHeadset( 1235): Proxy object connected
D/HeadsetService( 3638): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3638): classInitNative: succeeds
D/HeadsetStateMachine( 3638): Version 1.6
D/HeadsetStateMachine( 3638): make
,I/BluetoothAdapterState( 3638): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3638): get_profile_interface handsfree
,D/BluetoothA2dp( 1017): Proxy object connected
D/A2dpService( 3638): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3638): classInitNative: succeeds
V/Avrcp   ( 3638): make
,I/bluedroid( 3638): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3638): classInitNative: succeeds
,D/A2dpStateMachine( 3638): make
,I/bluedroid( 3638): get_profile_interface a2dp
,I/GKI_LINUX( 3638): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3638): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3638): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3638): classInitNative: succeeds
D/HidService( 3638): Received start request. Starting profile...
,I/bluedroid( 3638): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3638): classInitNative: succeeds
,D/HealthService( 3638): Received start request. Starting profile...
,I/bluedroid( 3638): get_profile_interface health
,I/BluetoothPanServiceJni( 3638): classInitNative(L105): succeeds
,D/BluetoothPan( 1017): BluetoothPAN Proxy object connected
I/chromium( 3591): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  273): NetlinkHandler, interfaceAdded
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
E/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  273): , Wifi = 0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/PanService( 3638): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3638): initializeNative(L110): pan
,I/bluedroid( 3638): get_profile_interface pan
,D/BluetoothTethering( 1017): got CMD_CHANNEL_HALF_CONNECTED
D/TCMD    (  470): NL - Read 1004 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
D/BluetoothTethering( 1017): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43c891e8
,D/Tethering( 1017): InitialState.processMessage what=4
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
,I/BtGatt.JNI( 3638): classInitNative(L684): classInitNative: Success!
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  273): NetlinkHandler, interfaceAdded
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
E/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  273): , Wifi = 0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BtGatt.DebugUtils( 3638): handleDebugAction() action=null
D/BtGatt.GattService( 3638): Received start request. Starting profile...
D/BtGatt.GattService( 3638): start()
,I/bluedroid( 3638): get_profile_interface gatt
D/TCMD    (  470): NL - Read 1004 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,D/QsoftapCmd(  271): Got softap fwreload command we are passing on
,D/SoftapController(  271): Softap fwReload - Ok
,D/BluetoothMapService( 3638): Received start request. Starting profile...
,D/BluetoothMapService( 3638): start()
,D/HeadsetPhoneState( 3638): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring down wlan0
,D/HeadsetPhoneState( 3638): onSignalStrengthsChanged..for signal  prevSignal=0
,D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 3638): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3638): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3638): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3638): enable
,I/bt_hci_bdroid( 3638): init
I/bt_vendor( 3638): bt-vendor : init
I/bt_hci_bdroid( 3638): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3638): userial_init
I/bt_hci_bdroid( 3638): bt_hc_worker_thread started
I/bt_hwcfg( 3638): Starting hciattach daemon
,I/bt_hwcfg( 3638): try to set false
I/bt_hwcfg( 3638): Starting hciattach daemon
,I/bt_hwcfg( 3638): try to set true
,I/ActivityManager( 1017): Killing 3351:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/qcom-bluetooth( 3700): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WifiService( 1017): New client listening to asynchronous messages
,V/BluetoothFtpReceiver( 3638): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/qcom-bluetooth( 3707): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/AuthorizationBluetoothService( 2015): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 3708): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 3710): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3711): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3712): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/Diag_Lib( 3714): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3714): Setting internal use port to rmnet0
E/Diag_Lib( 3714):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3714): Failed on DIAG init
E/Diag_Lib( 3714): linux_qmi_qmux_if_client_get_proc_name: pid=3714, proc_name=hci_qcomm_init
E/Diag_Lib( 3714): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3714): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3714): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3714): qmi_client [3714]: successfully connected to server, attempt=1
E/Diag_Lib( 3714): linux_qmi_qmux_if_client_get_client_id [3714]: qmux_client_id=13
E/Diag_Lib( 3714): qmi_client [3714] 13: qmux_client ID is initialized
E/Diag_Lib( 3714): qmi_client [3714] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3714): qmi_client [3714] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3714): qmi_client [3714] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3714): Sending signal ...... to read cmd data 
E/Diag_Lib( 3714): qmi error code.........:0
E/Diag_Lib( 3714): qmi sys error code.........:0
E/Diag_Lib( 3714): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3714): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3714): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3714): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3714): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3714): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3714): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3714): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3714): qmi_init:  Created client handle b7619788
,E/Diag_Lib( 3714): qmi_client [3714] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3714): qmi_client [3714] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3714): Sending signal ...... to read cmd data 
E/Diag_Lib( 3714): qmi error code.........:0
,E/Diag_Lib( 3714): qmi sys error code.........:0
E/Diag_Lib( 3714): Setting the api flag to : 1
,E/Diag_Lib( 3714): qmi_client [3714] 13: sending 54 bytes on fd = 8
,E/WifiHW  ( 1017): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1017): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 3717): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3717): rfkill: Cannot open RFKILL control device
D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,I/rmt_storage(  455): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85a11d0
I/rmt_storage(  455): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  455): wakelock acquired: 1, error no: 42
,I/rmt_storage(  455): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202056648)
E/Diag_Lib( 3714): qmi_client [3714] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3714):  API Flag .............. 1 
,E/Diag_Lib( 3714):  Message ID ............... 92 
,D/WifiStateMachine( 1017): setWifiState: enabling
,I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1260): Active network info is not available
D/WifiStateMachine( 1017): Supplicant start successful
,D/WifiMonitor( 1017): startMonitoring(wlan0) with mConnected = false
,E/Diag_Lib( 3717): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3717): Setting internal use port to rmnet0
,E/wpa_supplicant( 3717): baseband property is set to [msm]
,E/Diag_Lib( 3714): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3714): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3714): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3714): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3714): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3714): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3714): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3714): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3714): qmi_client [3714] 13: sending 880 bytes on fd = 8
,E/wpa_supplicant( 3717):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/Diag_Lib( 3714): qmi_client [3714] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3714): Sending signal ...... to read cmd data 
E/Diag_Lib( 3714): qmi error code.........:0
E/Diag_Lib( 3714): qmi sys error code.........:0
E/Diag_Lib( 3714): qmi_release: Released client handle ff
E/Diag_Lib( 3714): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3714): Ca,lled qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3714): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3714): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3714): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3714): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3714): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3714): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3714): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3714): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3714): qmi_client [3714] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3714): qmi_client [3714] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3714): Sending signal ...... to read cmd data 
E/Diag_Lib( 3714): qmi error code.........:0
E/Diag_Lib( 3714): qmi sys error code.........:0
E/Diag_Lib( 3714): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3714] 13
E/Diag_Lib( 3714): qmi_client [3714] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3714): qmi_client [3714] 13: failed to locate client data
E/Diag_Lib( 3714): qmi_client [3714] 13: calling release of fd=8
E/Diag_Lib( 3714): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
E/wpa_supplicant( 3717): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3717): card_info[i].card_state: 0x2
E/wpa_supplicant( 3717): card_info[i].error_code: 0x3
E/wpa_supplicant( 3717): SIM/USIM not ready
E/wpa_supplicant( 3717): Error while reading SIM card status
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/wpa_supplicant( 3717): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3717): card_info[i].card_state: 0x2
E/wpa_supplicant( 3717): card_info[i].error_code: 0x3
E/wpa_supplicant( 3717): SIM/USIM not ready
,I/wpa_supplicant( 3717): eap_proxy: Card not ready
,I/rmt_storage(  455): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  455): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  455): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202056648) wakelock released: 1, error no: 0
I/rmt_storage(  455): 
,I/rmt_storage(  455): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb85a11d0
,I/qcom-bluetooth( 3722): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3723): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3638): bluetooth satus is on
I/GKI_LINUX( 3638): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3638): btu_task pending for preload complete event
D/bt_userial_mct( 3638): userial_open(port:0)
,I/bt_userial_vendor( 3638): Done intiailizing UART
I/bt_userial_vendor( 3638): Done intiailizing UART
,I/bt_userial_mct( 3638): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3638): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3638): Entering userial_read_thread()
,I/bt-btu  ( 3638): btu_task received preload complete event
,I/wpa_supplicant( 3717): Long line in configuration file truncated
,I/wpa_supplicant( 3717): rfkill: Cannot open RFKILL control device
,I/        ( 3638): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3638): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3638): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3638): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3638): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3638): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3638): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 3638): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3638): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3638): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3638): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3638): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3638): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3638): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3638): BTE_InitTraceLevels -- TRC_BTIF
D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,E/bt-btm  ( 3638): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f1be049 
,E/bt-btm  ( 3638): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f1be049 
,E/bt-btif ( 3638): Calling BTA_HhEnable
E/bt-btif ( 3638): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:2 len:6
,E/wpa_supplicant( 3717): COUNTRY Code Recived
,E/wpa_supplicant( 3717): COUNTRY Code Recived -COUNTRY PL
,D/BluetoothAdapterProperties( 3638): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3638): Name is: XT1039
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:7 len:4
E/wpa_supplicant( 3717): baseband property is set to [msm]
,D/BluetoothManagerService( 1017): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1017): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3638): Scan Mode:21
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3638): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3638): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3638): hci lib postload completed
,I/bte_conf( 3638): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3638): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3638): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 3638): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothAdapterState( 3638): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3638): ScanMode =  21
D/BluetoothAdapterProperties( 3638): State =  11
D/BluetoothAdapterProperties( 3638): Setting state to 12
,I/BluetoothAdapterState( 3638): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3638): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3638): Discoverable Timeout:120
E/wpa_supplicant( 3717):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
D/BluetoothManagerService( 1017): Message: 60
D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1017): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=true
D/BluetoothPan( 1017): onBluetoothStateChange on: true
D/BluetoothHeadset( 1017): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3638): Entering On State
,D/BluetoothHeadset( 1235): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106466096)( 3638): Get Bonded Devices being called
,D/BluetoothHeadset( 1235): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106466096)( 3638): Get Bonded Devices being called
D/BluetoothHeadset( 1235): onBluetoothStateChange: up=true
E/wpa_supplicant( 3717): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3717): card_info[i].card_state: 0x2
E/wpa_supplicant( 3717): card_info[i].error_code: 0x3
E/wpa_supplicant( 3717): SIM/USIM not ready
,E/wpa_supplicant( 3717): Error while reading SIM card status
,D/BluetoothManagerService( 1017): Bluetooth State Change Intent: 11 -> 12
E/wpa_supplicant( 3717): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3717): card_info[i].card_state: 0x2
E/wpa_supplicant( 3717): card_info[i].error_code: 0x3
E/wpa_supplicant( 3717): SIM/USIM not ready
,I/wpa_supplicant( 3717): eap_proxy: Card not ready
,D/BluetoothManagerService( 1017): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3638): onReceive
,D/BluetoothMapService( 3638): STATE_ON
,D/BluetoothMapService( 3638): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1106466096)( 3638): Get Bonded Devices being called
,D/BluetoothManagerService( 1017): Message: 40
,D/BluetoothManagerService( 1017): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/WifiStateMachine( 1017): transitionTo: destState=SupplicantStartingState
D/BluetoothMapService( 3638): Map Service initSocket
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine( 1017): invokeExitMethods: InitialState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=1
,D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1017): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131144
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1017): deferMessage: msg=131144
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131085
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1017): deferMessage: msg=131085
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131149
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1017): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1017): handleMessage: X
W/BluetoothAdapter( 3638): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/BluetoothServiceJni( 3638): SOCK FLAG = 1 ***********************
D/WifiStateMachine( 1017): handleMessage: E msg.what=131145
D/BluetoothMapService( 3638): Accepting socket connection...
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131146
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
I/BluetoothAdapterProperties( 3638): adapterPropertyChangedCallback with type:7 len:4
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
D/WifiStateMachine( 1017): processMsg: DefaultState
I/qcom-bt-wlan-coex( 3737): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/WifiStateMachine( 1017): handleMessage: X
D/BluetoothAdapterProperties( 3638): Scan Mode:21
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
D/WifiStateMachine( 1017): processMsg: DefaultState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147457
D/WifiStateMachine( 1017): processMsg: SupplicantStartingState
D/WifiStateMachine( 1017): Supplicant connection established
D/WifiStateMachine( 1017): setWifiState: enabled
W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1260): Active network info is not available
,I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/WifiConfigStore( 1017): Loading config and enabling all networks
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/BluetoothManagerService( 1017): Message: 20
,D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434ffa80:true
D/BluetoothPbapService( 3638): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3638): Handler(): got msg=1
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,W/BluetoothAdapter( 3638): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3638): SOCK FLAG = 1 ***********************
,E/WifiConfigStore( 1017): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/LocalBluetoothProfileManager( 3675): Adding local A2DP profile
,E/wpa_supplicant( 3717): COUNTRY Code Recived -COUNTRY PL
,D/BluetoothManagerService( 1017): Message: 30
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3675): Adding local HEADSET profile
,D/BluetoothManagerService( 1017): Message: 30
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/WifiStateMachine( 1017): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1017): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine( 1017): invokeEnterMethods: SupplicantStartedState
D/BluetoothManagerService( 1017): Message: 30
,D/WifiStateMachine( 1017): invokeEnterMethods: DriverStartedState
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/dalvikvm( 1017): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/WifiStateMachine( 1017): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3717): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3717): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1017): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1017): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1017): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1017): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1017): invokeEnterMethods: DisconnectedState
,D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring up p2p0
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131144
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131085
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131152
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): set country code PL
,E/wpa_supplicant( 3717): COUNTRY Code Recived
,E/wpa_supplicant( 3717): COUNTRY Code Recived
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131162
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): set frequency band 2
,D/WifiMonitor( 1017): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1017): P2pEnablingState
D/WifiP2pService( 1017): P2pEnablingState{ when=-4ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnablingState{ when=-4ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=-4ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2p socket connection successful
D/WifiP2pService( 1017): P2pEnabledState
,D/WifiP2pService( 1017): sending p2p connection changed broadcast
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131167
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=143371
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1017): MCC mode enabled 0
D/WifiP2pService( 1017): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1017): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1017): InactiveState
D/WifiP2pService( 1017): InactiveState{ when=-5m48s784ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-5m48s784ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): InactiveState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3717): COUNTRY Code Recived
E/wpa_supplicant( 3717): COUNTRY Code Recived
,D/dalvikvm( 1017): GC_EXPLICIT freed 22710K, 65% free 17902K/50336K, paused 3ms+11ms, total 145ms
,D/BluetoothManagerService( 1017): Message: 30
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3675): Adding local MAP profile
D/BluetoothMap( 3675): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1017): Message: 30
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1017): Message: 30
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3675): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3675): finishStartingService: stopping service
,D/BluetoothAdapterService(1106466096)( 3638): Get Bonded Devices being called
,D/BluetoothA2dp( 3675): Proxy object connected
,D/A2dpProfile( 3675): Bluetooth service connected
,D/BluetoothHeadset( 3675): Proxy object connected
,D/HeadsetProfile( 3675): Bluetooth service connected
,D/BluetoothInputDevice( 3675): Proxy object connected
,D/HidProfile( 3675): Bluetooth service connected
,D/BluetoothPan( 3675): BluetoothPAN Proxy object connected
D/PanProfile( 3675): Bluetooth service connected
,D/BluetoothMap( 3675): Proxy object connected
D/MapProfile( 3675): Bluetooth service connected
,D/BluetoothMap( 3675): getConnectedDevices()
,D/BluetoothPbap( 3675): Proxy object connected
,D/PbapServerProfile( 3675): Bluetooth service connected
,V/BluetoothFtpReceiver( 3638): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3638): BluetoothFtpReceiver Start Service
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3638): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3638): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3638): Accept thread started.
,V/BluetoothFtpService( 3638): Ftp Service onCreate
I/BluetoothFtpService( 3638): FFFFFtp Service onCreate
V/BluetoothFtpService( 3638): Starting FTP service
D/AuthorizationBluetoothService( 2015): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2015): Proximity feature is not enabled.
,V/BluetoothFtpService( 3638): Ftp Service onStartCommand
,V/BluetoothFtpService( 3638): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3638): Handler(): got msg=1
,V/BluetoothFtpService( 3638): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3638): Ftp Service initSocket
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3638): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3638): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3638): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3638): Run Accept thread
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  273): wifi_close_sockets: Exit
E/MDMCTBK (  273): Attach monitor thread
I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1210461072
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2158): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1017): InactiveState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledStateupdate channel list
,D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/TCMD    (  470): NL - Read 56 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
I/wpa_supplicant( 3716): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3716): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 38:f8:89:11:e9:11
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c2,
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 38
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 38,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS ,
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i,
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiP2pService( 1017): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4215eb30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4215eb30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4215eb30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): handleMessage: X
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3591): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3591): 
,V/AlarmManager( 1017): sending alarm Alarm{4301e2e8 type 3 android}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 8e
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 8e
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  470): NL - Read 56 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
,D/WifiP2pService( 1017): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiP2pService( 1017): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiP2pService( 1017): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 3717): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  470): NL - Read 56 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 3717): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,I/wpa_supplicant( 3717): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3717): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  470): NL - Read 312 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 88 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 68 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3717): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/TCMD    (  470): NL - Read 80 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 80 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/TCMD    (  470): NL - Read 68 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Tethering( 1017): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1017): handleMessage: E msg.what=131101
D/WifiStateMachine( 1017): processMsg: DisconnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3717): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3717): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273):  STA Connected !!
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/TCMD    (  470): NL - Read 1000 bytes from update socket.
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/TCMD    (  470): NL - message type is RTM_NEWLINK
D/TCMD    (  470): Listening for incoming client connection request
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147459
D/WifiStateMachine( 1017): processMsg: DisconnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): Network connection established
D/WifiStateMachine( 1017): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19,
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1210465408
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1017): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1017): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1017): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=147462
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-15ms what=147462 obj=android.net.wifi.StateChangeResult@42053638 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=196612
D/WifiStateMachine( 1017): processMsg: ObtainingIpState
D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1017): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421639a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1017): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@421639a8 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  470): NL - Read 56 bytes from update socket.
D/TCMD    (  470): NL - message type is RTM_NEWLINK
,D/TCMD    (  470): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 c0,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService( 1017): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiP2pService( 1017): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): handleMessage: X
,D/TCMD    (  470): NL - Read 60 bytes from update socket.
D/TCMD    (  470): NL - ignore NL message, type = 20
,D/TCMD    (  470): Listening for incoming client connection request
,D/WifiStateMachine( 1017): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1017): processMsg: ObtainingIpState
,D/WifiStateMachine( 1017): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1017): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1017): DHCP successful
D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1017): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1017): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1017): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState enter
D/WifiStateMachine( 1017): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=151572
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=135190
D/WifiStateMachine( 1017): processMsg: VerifyingLinkState
D/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1017): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1017): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState enter
,D/WifiStateMachine( 1017): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1017): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1017): handleMessage: X
D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1017): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1017): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1017): WiFi NOT Tethered!
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42008c68
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1017): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1017): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1017): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1017): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1017): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1017): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1017): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1017): handleMessage: X
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131092
D/WifiStateMachine( 1017): processMsg: ConnectedState
D/WifiStateMachine( 1017): processMsg: L2ConnectedState
D/WifiStateMachine( 1017): processMsg: ConnectModeState
D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): handleMessage: X
,D/Checkin ( 1017): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1017): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1017): WiFi NOT Tethered!
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1017): Unexpected mtu value: android.net.wifi.WifiStateTracker@42008c68
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1281): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1017): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1017): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1017): processMsg: ConnectedState
,D/WifiStateMachine( 1017): processMsg: L2ConnectedState
,D/WifiStateMachine( 1017): processMsg: ConnectModeState
,D/WifiStateMachine( 1017): processMsg: DriverStartedState
,D/WifiStateMachine( 1017): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1017): processMsg: DefaultState
,D/WifiStateMachine( 1017): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1017): handleMessage: X
,D/ConnectivityService( 1017): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1017):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1017): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1017): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1543): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1017): Setting time of day to sec=1449832588
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/        ( 1017): Unable to set rtc to 1449832588: Invalid argument
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1017): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3845 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/jxcore-log( 3591): Connected to the server!
I/jxcore-log( 3591): 
,I/chromium( 3591): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PollingManager( 1543): now: 387118 ,futureTime: 12110148
,D/PollingManager( 1543): Polling alarm set to expire at: 12110148 Current Time: 387119
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1543): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1543): registerApp(): CCE
I/CCE     ( 1543): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1543): Registering with Alarm Manager to restart CCE
,D/TelephonyProvider( 1235): Column apn id key is 'apn_id'
,D/MMApiWebService( 1543): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1543): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1543): isRequestAllowed(): already have outstanding request ... ignoring request
,D/PollingManager( 1543): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1543): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1543): [debug] > CusSM.onRadioUp
D/PollingManager( 1543): now: 387169 ,futureTime: 12110148
,D/PollingManager( 1543): Polling alarm set to expire at: 12110148 Current Time: 387169
,D/OtaApp  ( 1543): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 1543): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,E/ActivityThread( 1543): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1543): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/CCE     ( 1543): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1543): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1543): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/OtaApp  ( 1543): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MMApiWebService( 1543): generating token using payload instead of using session token
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1235): Column apn id key is 'apn_id'
,D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1543): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/ActivityManager( 1017): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3883 uid=10056 gids={50056, 3003, 1028, 1015}
D/OtaApp  ( 1543): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1543): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/MMApiWSBase( 1543): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
D/TelephonyProvider( 1235): Column apn id key is 'apn_id'
I/MMApiWSBase( 1543): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1543): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1543): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1543): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/dalvikvm( 1197): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1197): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1197): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1197): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1197): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1197): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1197): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 3845): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f2e078, skipping init
I/openssl ( 3845): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3845): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3909 uid=10030 gids={50030, 3003, 1028, 1015}
,I/PhenotypeConfigurator( 1197): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/ActivityManager( 1017): Killing 3438:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 3909): mnc/mcc: 
,V/MmsConfig( 3909): tag: bool value: enabledMMS - true
V/MmsConfig( 3909): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3909): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3909): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3909): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3909): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3909): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3909): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3909): tag: int value: recipientLimit - 20
V/MmsConfig( 3909): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3909): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3909): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 3909): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3909): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3909): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3909): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3909): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3909): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1017): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3928 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1017): Killing 3113:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 1367): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1367): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1367): VFY: replacing opcode 0x6e at 0x003d
I/dalvikvm( 1197): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1197): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1197): VFY: replacing opcode 0x6e at 0x003d
,D/GpsLocationProvider( 1017): NTP server returned: 1449832587602 (Fri Dec 11 12:16:27 CET 2015) reference: 386257 certainty: 11 system time offset: -1294
E/LocSvc_ApiV02( 1017): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/TelephonyProvider( 1235): Column apn id key is 'apn_id'
,D/dalvikvm( 1235): GC_EXPLICIT freed 1457K, 45% free 9515K/17224K, paused 2ms+5ms, total 68ms
,D/MobileConnectivityChangeReceiver( 3928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3928): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager( 1017): Killing 3468:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/PhoneMonitor( 3928): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3928): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3949 uid=10076 gids={50076, 3003, 1028, 1015}
,E/ActivityThread( 1367): Failed to find provider info for com.android.contacts.metadata
D/DelayedSyncController( 3883): Delaying sync.
,E/Auth.Api.Credentials( 1367): [CredentialSyncAdapter] Unknown sync event.
,D/SyncManager( 1017): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 387650, reason: UserStart
,I/ActivityManager( 1017): Killing 3135:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1017): GC_EXPLICIT freed 1731K, 65% free 17918K/50336K, paused 5ms+10ms, total 105ms
,I/CheckinService( 1367): Checkin interval check for package: unspecified last checkin: 1449796230744 min interval config: 0 actual interval: 36358321
,I/CheckinService( 1367): Checking schedule, now: 1449832589075 next: 1449796260721
,I/CheckinService( 1367): active receiver: enabled
,I/CheckinService( 1367): Preparing to send checkin request
,I/EventLogService( 1367): Accumulating logs since 1449832236061
,I/CheckinRequestBuilder( 1367): Checkin reason type: 8 attempt count: 1
D/WifiService( 1017): New client listening to asynchronous messages
E/ActivityThread( 1367): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 3949): Binding Chromium to main looper Looper (main, tid 1) {41f2afb8}
,I/LibraryLoader( 3949): Expected native library version number "",actual native library version number ""
,I/chromium( 3949): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3949): Initializing chromium process, renderers=0
,D/dalvikvm( 1543): GC_CONCURRENT freed 2175K, 38% free 10725K/17224K, paused 2ms+3ms, total 35ms
,E/AudioManagerAndroid( 3949): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3949): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3949): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3949): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3949): Local Branch: 
I/Adreno-EGL( 3949): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3949): Local Patches: NONE
I/Adreno-EGL( 3949): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1017): Jit: resizing JitTable from 8192 to 16384
,W/chromium( 3949): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/DelayedSyncController( 3883): Delaying sync.
,W/GAV2    ( 3949): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3949): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1197): GC_EXPLICIT freed 1164K, 36% free 11130K/17224K, paused 3ms+6ms, total 37ms
,I/NSApplication( 3949): Starting up...
,I/ImageResourceManager( 3151): ImageResourceManager: uninitalized
,I/iu.Environment( 3151): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3151): SYNC; picasa accounts
I/ActivityManager( 1017): Killing 3496:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3151): num queued entries: 0
,I/iu.UploadsManager( 3151): num updated entries: 0
,I/iu.SyncManager( 3151): NEXT; no task
,I/iu.SyncManager( 1367): SYNC; picasa accounts
,D/NetworkLogImpl( 1367): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1367): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1367): num queued entries: 0
,I/iu.UploadsManager( 1367): num updated entries: 0
,I/iu.SyncManager( 1367): NEXT; no task
,D/DEBUG   ( 1543): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1543): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1543): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1543): ServiceHandler.handleMessage: mWaitCount=1
I/openssl ( 3845): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3845): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3928): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3928): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3151): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4014 uid=10007 gids={50007, 3003}
,D/dalvikvm( 3151): GC_CONCURRENT freed 621K, 5% free 16454K/17224K, paused 2ms+3ms, total 28ms
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 3ms+2ms, total 23ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/ExtensionsFactory( 4014): No custom extensions.
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4031 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 3191:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4041 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 3675:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1017): Client connection lost with reason: 4
,V/AlarmClock( 4031): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 4041): Created com.android.providers.calendar.CalendarAlarmManager@41f3bff8(com.android.providers.calendar.CalendarProvider2@41f33bb0)
,I/AlarmClock( 4031): Displaying next alarm time: ''
,V/AlarmClock( 4031): AlarmInitReceiver finished
,I/ActivityManager( 1017): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4059 uid=10098 gids={50098}
,D/dalvikvm( 4059): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f280b8, skipping init
D/TimeService( 4059): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832589834
D/        ( 4059): TimeServiceNative: User Time to be set is 1449832589835
D/QC-time-services( 4059): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4059): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4059): Lib:time_genoff_operation: pargs->ts_val = 1449832589835
,D/QC-time-services(  447): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4059): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  447): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832589835
D/QC-time-services(  447): Daemon:genoff_opr: Base = 2, val = 1449832589835, operation = 0
D/QC-time-services(  447): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/11/115 11:10:35
D/QC-time-services(  447): Daemon:Value read from RTC seconds = 1449832235000
D/QC-time-services(  447): Daemon:new time 1449832589835 
D/QC-time-services(  447): Daemon: delta 354835 genoff 354835 
D/QC-time-services(  447): Daemon:genoff_persistent_update: Writing genoff = 354835 to memory
D/QC-time-services(  447): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  447): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  447): Updating the TOD offset
D/QC-time-services(  447): Daemon:genoff_persistent_update: Writing genoff = 354835 to memory
D/QC-time-services(  447): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  447): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  447): Daemon:Update to modem bit set
D/QC-time-services(  447): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  447): Daemon: Base = 2, Value being sent to MODEM = 18446743757745106451
,E/QC-time-services( 4059): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager( 1017): Killing 3845:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  447): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  447): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1367): Checkin interval check for package: unspecified last checkin: 1449796230744 min interval config: 0 actual interval: 36359109
,D/DEBUG   ( 1543): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1543): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1543): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1543): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1543): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1543): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1543
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1543): [info] > Updatetime from metadata: 10
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1543): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1543): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1543): [info] > Updatetime from metadata: 10
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1543): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1543): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1543): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1543): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1017): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1543
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/IInputConnectionWrapper( 3591): showStatusIcon on inactive InputConnection
,I/OtaApp  ( 1543): [info] > Updatetime from metadata: 10
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1543): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1543): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1543): [info] > Updatetime from metadata: 10
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1543): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1543): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
I/LaunchCheckinHandler( 1017): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,104
,D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1017): Activity reported stop, but no longer stopping: ActivityRecord{427ab160 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/MMApiWSBase( 1543): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1543): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1543): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1543): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1543): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1543): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1543): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1543): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1543): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1543): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1543): unbindWebServices(): un-registering our AIDL callback...
,D/MMApiProvisionService( 1543): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"11702","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1543): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1543): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1543): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1543): handleResponse(): Session Expiration alarm set to expire at: Fri Dec 11 15:31:32 CET 2015
,D/MMApiProvisionService( 1543): _setMMApiCredInfo: storing credential info 
,E/MMApiProvisionService( 1543): handleResponse(): no settings sent by the server:
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1543): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DEBUG   ( 1543): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,W/ContextImpl( 1543): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1543): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1543): onServiceConnected()
I/SundryService( 1543): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1543): Received shoulder tap
,D/GetNotificationsWS( 1543): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1543): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1543): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1543): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1543): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1543): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1543): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,I/GCM     ( 2015): GCM config loaded
,I/CalendarProvider2( 4041): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4041): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/dalvikvm( 2015): GC_CONCURRENT freed 1913K, 40% free 10407K/17224K, paused 2ms+4ms, total 43ms
,D/AlertReceiver( 4014): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4014): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/PhenotypeConfigurator( 1197): Scheduling Phenotype for one-off execution 5430 seconds from now (1449832591104)
,D/GetConfigurationSnapshotOperation( 1197): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager( 1017): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4101 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/PhenotypeFlagCommitter( 1197): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1197): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1017): GC_EXPLICIT freed 892K, 65% free 17895K/50336K, paused 4ms+10ms, total 90ms
,W/dalvikvm( 4101): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4101): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4101): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 4101): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4101): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4101): install
,I/MultiDex( 4101): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4101): loading existing secondary dex files
,I/MultiDex( 4101): load found 3 secondary dex files
,I/MultiDex( 4101): install done
,D/MMApiWSBase( 1543): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1543): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1543): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/dalvikvm( 4101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4101): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4101): VFY: unable to resolve instance field 36
,D/dalvikvm( 4101): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4101): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4101): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4101): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4101): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4101): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f29aa8
,D/dalvikvm( 4101): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f29aa8
,D/dalvikvm( 4101): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f29aa8, skipping init
,D/dalvikvm( 4101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f29aa8
D/dalvikvm( 4101): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f29aa8
,V/JNIHelp ( 4101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Checkin ( 1543): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/dalvikvm( 1197): GC_CONCURRENT freed 1506K, 33% free 11623K/17224K, paused 3ms+7ms, total 38ms
,D/SundryService( 1543): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1543): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1543): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1543): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1543): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1543): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1543): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 4101): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f29aa8
,D/dalvikvm( 4101): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f29aa8
D/dalvikvm( 4101): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f29aa8
,D/dalvikvm( 4101): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f29aa8
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1281): Inetcondition changed, white->blue
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/ProviderInstaller( 4101): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 2015): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2015): Proximity feature is not enabled.
,D/LocationInitializer( 1367): Restart initialization of location
,D/WearableService( 1197): callingUid 10022, callindPid: 1197
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1197): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4101): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4101): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4101): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4101): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x000d
,W/GCoreFlp( 1197): No location to return for getLastLocation()
,W/FusedLocationProvider( 1197): location=null
,I/dalvikvm( 4101): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4101): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4101): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4101): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4101): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4101): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4101): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4101): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4101): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4101): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 1367): GC_CONCURRENT freed 1756K, 31% free 11988K/17224K, paused 3ms+6ms, total 43ms
,W/PhenotypeConfigurator( 1197): Server returned 404
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  279): App is not loaded in QSEE
,D/NativeLibraryUtils( 4101): Install completed successfully. count=14 extracted=0
,I/dalvikvm( 4101): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4101): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 4101): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4101): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4101): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4101): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4101): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4101): VFY: replacing opcode 0x6e at 0x00bb
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51e1000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb51e1000
,I/GoogleURLConnFactory( 4101): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=4013541188
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4101): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422ea8f0
,D/dalvikvm( 4101): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422ea8f0
,D/dalvikvm( 4101): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422ea8f0, skipping init
,D/dalvikvm( 4101): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4155): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4101): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4101): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4101): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4101): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4101): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4101): Local Branch: 
I/Adreno-EGL( 4101): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4101): Local Patches: NONE
I/Adreno-EGL( 4101): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4101): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4101): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4101): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4101): Local Branch: 
I/Adreno-EGL( 4101): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4101): Local Patches: NONE
I/Adreno-EGL( 4101): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4101): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4101): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4101): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4101): Local Branch: 
I/Adreno-EGL( 4101): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4101): Local Patches: NONE
I/Adreno-EGL( 4101): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4101): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4101): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4101): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4101): Local Branch: 
I/Adreno-EGL( 4101): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4101): Local Patches: NONE
I/Adreno-EGL( 4101): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=66402833
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/GAV2    ( 3949): Thread[GAThread,5,main]: No campaign data found.
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Settings( 4101): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1367): Classify the device as Phone.
,D/dalvikvm( 1367): GC_CONCURRENT freed 1933K, 31% free 11993K/17224K, paused 4ms+5ms, total 38ms
,I/CheckinTask( 1367): Sending checkin request (12054 bytes)
,I/GlobalDismissManager( 4014): no sender configured
,D/AlertService( 4014): Beginning updateAlertNotification
,D/AlertService( 4014): No fired or scheduled alerts
,D/AlertService( 4014): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4014): No events found starting within 1 week.
I/ActivityManager( 1017): Killing 3909:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinResponseProcessor( 1367): From server: 2 gservices updates and 0 deletes
,E/UlpEngine( 1017): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
,E/UlpEngine( 1017): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1260): No entry in secure settings for enhanced location services: false
I/CertBlacklister( 1017): Certificate blacklist changed, updating...
I/CertBlacklister( 1017): Certificate blacklist updated
,I/GservicesProvider( 2015): main difference update completed
,I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4192 uid=10009 gids={50009, 3003, 2001}
,I/CheckinRequestBuilder( 1367): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1367): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4192): Update started
,E/UpdateRequestReceiver( 4192): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4210 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4192): Update started
,E/UpdateRequestReceiver( 4192): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4192): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4192): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4231 uid=10025 gids={50025, 3003}
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 4210): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f2d2c0, skipping init
I/openssl ( 4210): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4210): Crypto mode 0 already enabled
,I/CheckinRequestBuilder( 1367): Classify the device as Phone.
,I/ContactAccountLoggerTas( 2190): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2190): Updating Gservices keys
,D/dalvikvm( 2015): GC_EXPLICIT freed 772K, 40% free 10365K/17224K, paused 4ms+5ms, total 37ms
,I/CheckinTask( 1367): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ContactAccountLoggerTas( 2190): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2190): canRun() : Opted Out
,I/CheckinService( 1367): Checking schedule, now: 1449832597218 next: 1450425667195
,I/CheckinService( 1367): active receiver: disabled
,D/CheckinService( 1367): Recording last checkin time for package unspecified as 1449832597233
,I/DownloadManager( 4210): Download 271 starting
,I/DownloadManager( 4210): Download 272 starting
,W/ActivityThread( 4210): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ContactAccountLoggerTas( 2190): canRun() : Opted Out
,I/ActivityManager( 1017): Killing 3883:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3151): GC_FOR_ALLOC freed 161K, 5% free 16521K/17224K, paused 19ms, total 20ms
,I/CheckinService( 1367): Checkin interval check for package: unspecified last checkin: 1449832597233 min interval config: 0 actual interval: 90
,I/CheckinService( 1367): Checking schedule, now: 1449832597358 next: 1450425667195
,I/CheckinService( 1367): active receiver: disabled
,I/SystemUpdateService( 1367): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/dalvikvm( 1017): GC_EXPLICIT freed 720K, 65% free 17792K/50336K, paused 4ms+10ms, total 101ms
,D/SystemUpdateService( 1367): onCreate
,D/SystemUpdateService( 1367): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager( 1017): Killing 3949:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3151): GC_FOR_ALLOC freed 16K, 4% free 18311K/19004K, paused 28ms, total 28ms
,I/SystemUpdateService( 1367): cancelUpdate (empty URL)
,I/SystemUpdateService( 1367): active receiver: disabled
I/dalvikvm( 1367): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1367): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1367): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 2015): GC_EXPLICIT freed 561K, 40% free 10369K/17224K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 1367): GC_EXPLICIT freed 711K, 31% free 12032K/17224K, paused 4ms+6ms, total 43ms
,W/SQLiteConnectionPool( 1367): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SystemUpdateService( 1367): onDestroy
,E/DynamiteModule( 1367): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1367): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1367): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1367): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1367): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1367): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1367): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1367): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1367): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1367): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1367): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/DynamiteModule( 1367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/DynamiteModule( 1367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/DynamiteModule( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1367): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 1367): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/DynamiteModule( 1367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/DynamiteModule( 1367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/DynamiteModule( 1367): 	at dalvik.system.NativeStart.main(Native Method)
,I/DynamiteModule( 1367): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1367): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1367): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1367): Updating ocr activity enabled=false
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1367): Updating downloaded model state (gservices changed)
,D/GCM     ( 2015): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 2015): GC_EXPLICIT freed 162K, 40% free 10387K/17224K, paused 2ms+5ms, total 28ms
,D/dalvikvm( 1197): GC_CONCURRENT freed 1997K, 33% free 11589K/17224K, paused 3ms+7ms, total 43ms
,E/dalvikvm( 1197): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm( 1197): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 1197): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 1197): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 1197): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm( 1197): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1197): VFY: replacing opcode 0x6e at 0x0012
,I/GCoreUlr( 1197): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1197): DispatchingService.onCreate()
,D/GCM     ( 2015): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 2015): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GeofencerStateMachine( 1197): Ignoring removeGeofence because network location is disabled.
,D/CaptivePortalTracker( 1017): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,E/ctxmgr  ( 1197): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1197): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ctxmgr  ( 1197): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10022, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1197): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/GCoreUlr( 1197): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1197): Unbound from all location providers
,I/GCoreUlr( 1197): Place inference reporting - stopped
,D/CaptivePortalTracker( 1017): Checking http://216.58.209.46/generate_204
,I/GCoreUlr( 1197): DispatchingService.onDestroy()
,I/GCoreUlr( 1197): Stopping handler for UlrDispSvcFast
W/ActivityThread( 1017): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/GCoreUlr( 1197): Unbound from all location providers
,I/GCoreUlr( 1197): Place inference reporting - stopped
,I/Auth    ( 2015): [BroadcastManager] Broadcasting account services changed.
,D/dalvikvm( 2015): GC_EXPLICIT freed 350K, 40% free 10369K/17224K, paused 2ms+4ms, total 32ms
,I/DownloadManager( 4210): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Checkin ( 4210): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4210): Download 272 finished with status SUCCESS
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 4210): Download 273 starting
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1292): Deferring update until onResume
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4342 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
D/CaptivePortalTracker( 1017): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 1017): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1017): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1017): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1017): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/Launcher( 1292): Deferring update until onResume
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/Auth    ( 2015): [BroadcastManager] Broadcasting account services changed.
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/Babel   ( 4342): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4342): MmsConfig.loadMmsSettings
I/Babel   ( 4342): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4342): MmsConfig.loadFromDatabase
,E/Babel   ( 4342): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4342): MmsConfig.loadFromResources
,E/Babel   ( 4342): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4342): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1197): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 4342): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 4210): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager( 1017): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4369 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/DownloadManager( 4210): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1017): GC_EXPLICIT freed 1680K, 65% free 18051K/50336K, paused 5ms+12ms, total 108ms
,D/Checkin ( 4210): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/ActivityManager( 1017): Killing 4041:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4389 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4059:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4210): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4210): Download 271 finished with status SUCCESS
,I/DownloadManager( 4210): Download 273 finished with status SUCCESS
,I/InternalIcingCorporaPro( 2190): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4406 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1017): Killing 4031:com.android.deskclock/u0a15 (adj 15): empty #9
,I/ActivityManager( 1017): Killing 4014:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  275): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 23ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,I/ContactLocale( 4369): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 1197): GC_EXPLICIT freed 1216K, 34% free 11533K/17224K, paused 6ms+6ms, total 45ms
,I/dalvikvm( 4406): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4406): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4406): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4406): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4406): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4406): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4406): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/InternalIcingCorporaPro( 2190): UpdateCorporaTask done [took 281 ms] updated apps [took 281 ms] 
I/dalvikvm( 4406): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4406): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4406): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4406): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4406): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4406): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4406): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4406): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4406): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4406): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4406): Skipping gmscore version check
,D/Finsky  ( 4406): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4406): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4406): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4406): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4406): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x0017
,D/Finsky  ( 4406): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1367): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1367): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1367): updateResources: need to parse f{com.google.android.gms}
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/openssl ( 4210): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4210): Crypto mode 0 already enabled
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4192): Update downloaded, starting installation
,I/UpdateFetcherService( 4192): Started installation
,I/ActivityManager( 1017): Killing 4231:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/DownloadManager( 4210): Download 274 starting
,I/DownloadManager( 4210): Ignoring Content-Length since Transfer-Encoding is also defined
,I/Icing   ( 1367): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1367): GC_CONCURRENT freed 1854K, 30% free 12114K/17224K, paused 5ms+7ms, total 45ms
,D/Icing   ( 1367): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1367): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449832601
,I/GAV2    ( 3151): Thread[GAThread,5,main]: No campaign data found.
,I/ContactAccountLoggerTas( 2190): canRun() : Opted Out
,D/Checkin ( 4210): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4210): Download 274 finished with status SUCCESS
,W/ContextImpl( 4192): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4192): Update downloaded, starting installation
,I/UpdateFetcherService( 4192): Started installation
,I/ConfigUpdateInstallReceiver( 1017): Not installing, new version is <= current version
,I/openssl ( 4210): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4210): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Killing 3928:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/PackageSettings( 1017): Skipping PackageSetting{421e72c8 com.example.hello/10442} due to missing metadata
,V/AlarmManager( 1017): sending alarm Alarm{427a03d8 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{4277fdf8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43cf6c80 type 2 android}
,E/ActivityThread( 1367): Failed to find provider info for com.android.contacts.metadata
D/SyncManager( 1017): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 447584, reason: UserStart
,V/AlarmManager( 1017): sending alarm Alarm{41f62d10 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{42897300 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{44641880 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d852e8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42addf30 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{43cb6688 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d2c840 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{44641958 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d0d9d0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{4210cf38 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43ddf710 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{4297f3d0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42898dd0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43c80da8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{4271b798 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{44641a30 type 1 com.android.deskclock}
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4558 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4342:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d15ae0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4204daa0 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1281): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1281): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1281): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d14328 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42fc4458 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{4296d060 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42b322a0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43d54b88 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d63e18 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{432e0fc0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{427f4e48 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43b6f2b0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42773390 type 3 android}
,D/dalvikvm( 1017): GC_CONCURRENT freed 2118K, 64% free 18151K/50336K, paused 5ms+9ms, total 123ms
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42b18960 type 3 android}
,I/ProcessStatsService( 1017): Prepared write state in 19ms
,I/ProcessStatsService( 1017): Prepared write state in 20ms
,I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-32.bin
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{446594d8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43ff13d8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d92dc0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{43d173f0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43d54d38 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43d54d88 type 3 com.google.android.gms}
,V/AlarmManager( 1017): sending alarm Alarm{43d54dd8 type 3 com.google.android.gms}
,V/AlarmManager( 1017): sending alarm Alarm{43d54f50 type 0 com.google.android.gms}
,V/AlarmManager( 1017): sending alarm Alarm{43d54c60 type 1 com.android.deskclock}
,I/EventLogService( 1367): Aggregate from 1449832589099 (log), 1449832236061 (data)
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2015): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4657): 
D/AndroidRuntime( 4657): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4657): CheckJNI is OFF
D/dalvikvm( 4657): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4657): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4657): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4657): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4657): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4657): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4657): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4657): failed to load memtrack module: -2
D/AndroidRuntime( 4657): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10464 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 3591:com.test.thalitest/u0a464 (adj 9): stop com.test.thalitest
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{44667a20 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1017): WIN DEATH: Window{447419d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1017): Client connection lost with reason: 4
W/PackageSettings( 1017): Skipping PackageSetting{421e72c8 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10464 user=0: pkg removed
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449834354
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2158): GC_EXPLICIT freed 6346K, 44% free 9742K/17224K, paused 2ms+28ms, total 91ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
W/GeofencerStateMachine( 1197): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 4369): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
D/dalvikvm( 1017): GC_EXPLICIT freed 1319K, 65% free 18038K/50336K, paused 6ms+10ms, total 149ms
D/dalvikvm( 1017): WAIT_FOR_CONCURRENT_GC blocked 70ms
D/dalvikvm( 1292): GC_EXPLICIT freed 2896K, 33% free 11596K/17224K, paused 78ms+5ms, total 143ms
I/Launcher( 1292): Deferring update until onResume
D/dalvikvm( 1367): GC_EXPLICIT freed 864K, 31% free 12048K/17224K, paused 10ms+8ms, total 194ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
D/dalvikvm( 2190): GC_EXPLICIT freed 3500K, 42% free 10081K/17224K, paused 2ms+15ms, total 201ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2190): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1017): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4686 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449834354
I/Launcher( 1292): Deferring update until onResume
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10464 #1
I/InternalIcingCorporaPro( 2190): UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
D/dalvikvm( 1017): GC_EXPLICIT freed 406K, 65% free 18054K/50336K, paused 8ms+14ms, total 202ms
D/AndroidRuntime( 4657): Shutting down VM
D/dalvikvm( 4657): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4686): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4707 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4686): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4707): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4406): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4406): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4406): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1367): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1367): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1367): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1367): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1367): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1367): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1367): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 2015): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2015): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/FileUtils( 1367): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4737 uid=10058 gids={50058}
E/SQLiteDatabase( 1367): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1367): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1367): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1367): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1367): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1367): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1367): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1367): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1367): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1367): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1367): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1367): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1367): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1367): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1367): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1367): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1367): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1367): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1367): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1367): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1367): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1367): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 1367): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SharedPreferencesImpl( 1367): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
I/Icing   ( 1367): doRemovePackageData com.test.thalitest
W/SQLiteOpenHelper( 1367): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1367): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1367): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1367): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1367): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1367): threadid=51: thread exiting with uncaught exception (group=0x41656d40)
E/AndroidRuntime( 1367): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1367): Process: com.google.android.gms, PID: 1367
E/AndroidRuntime( 1367): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1367): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1367): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1367): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1367): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1367): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1367): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1367): Failed to open Apps corpus file.
E/Icing   ( 1367): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1367): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
I/Process ( 1367): Sending signal. PID: 1367 SIG: 9
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1017): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1017): 	... 5 more
E/SQLiteDatabase( 4707): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4707): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4707): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4707): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4707): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4707): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4707): threadid=10: thread exiting with uncaught exception (group=0x41656d40)
E/AndroidRuntime( 4707): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4707): Process: com.android.keychain, PID: 4707
E/AndroidRuntime( 4707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4707): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4707): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4707): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4707): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4707): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1017): Process com.google.android.gms (pid 1367) has died.
D/WifiService( 1017): Client connection lost with reason: 4
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
I/Process ( 4707): Sending signal. PID: 4707 SIG: 9
E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1017): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1017): 	... 5 more
I/ActivityManager( 1017): Process com.android.keychain (pid 4707) has died.
W/ActivityManager( 1017): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20990ms

```
