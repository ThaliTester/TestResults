#### Test 51986340a77003b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of /dev/log/system
W/SocketClient(  275): write error (Broken pipe)
,D/AndroidRuntime( 3526): 
D/AndroidRuntime( 3526): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3526): CheckJNI is OFF
D/dalvikvm( 3526): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3526): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3526): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3526): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3526): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3526): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3526): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3526): failed to load memtrack module: -2
D/AndroidRuntime( 3526): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3526
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3550 uid=10417 gids={50417, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3526): Shutting down VM
D/dalvikvm( 3526): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3550): Binding Chromium to main looper Looper (main, tid 1) {41f9ed08}
I/LibraryLoader( 3550): Expected native library version number "",actual native library version number ""
I/chromium( 3550): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3550): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothAdapter( 3550): 1106981176: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434b6f98:true
I/Adreno-EGL( 3550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3550): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3550): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3550): Local Branch: 
I/Adreno-EGL( 3550): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3550): Local Patches: NONE
I/Adreno-EGL( 3550): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3550): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3550): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3550): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3550): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3550): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3550): VFY: unable to resolve virtual method 208: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3550): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3550): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3550): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3550): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3550): VFY: unable to resolve virtual method 266: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3550): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3550): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3550): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3550): VFY: unable to resolve virtual method 224: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3550): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3550): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 3550): VFY: unable to resolve virtual method 229: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3550): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3550): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3550): Enabling debug mode 0
,W/AwContents( 3550): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,402
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +373ms (total +402ms)
W/AwContents( 3550): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3550): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3550): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3550): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa2fd8
,D/dalvikvm( 3550): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa2fd8
D/jxcore_app_log( 3550): JniHelper::setJavaVM(0x415ecfa8), pthread_self() = 1614318896
,D/JX-Cordova( 3550): jxcore cordova android initializing
,D/dalvikvm( 3550): GC_CONCURRENT freed 2832K, 17% free 14357K/17224K, paused 2ms+2ms, total 59ms
,D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 209K, 17% free 14334K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 188K, 17% free 14363K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3550): Grow heap (frag case) to 16.199MB for 146998-byte allocation
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 258K, 18% free 14411K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3550): Grow heap (frag case) to 16.316MB for 220492-byte allocation
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 375K, 18% free 14487K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3550): Grow heap (frag case) to 16.495MB for 330734-byte allocation
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 582K, 19% free 14611K/17908K, paused 26ms, total 26ms
I/dalvikvm-heap( 3550): Grow heap (frag case) to 16.774MB for 496096-byte allocation
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 885K, 20% free 14790K/18396K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3550): Grow heap (frag case) to 17.185MB for 744140-byte allocation
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 1310K, 22% free 15051K/19124K, paused 28ms, total 28ms
,D/dalvikvm( 3550): GC_CONCURRENT freed 1673K, 20% free 15425K/19124K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 3550): GC_FOR_ALLOC freed 418K, 20% free 15389K/19124K, paused 27ms, total 29ms
I/dalvikvm-heap( 3550): Grow heap (frag case) to 18.658MB for 1674304-byte allocation
D/dalvikvm( 3550): GC_CONCURRENT freed 1728K, 24% free 15965K/20760K, paused 1ms+4ms, total 45ms
D/dalvikvm( 3550): GC_FOR_ALLOC freed 1401K, 23% free 16049K/20760K, paused 30ms, total 30ms
I/dalvikvm-heap( 3550): Grow heap (frag case) to 20.100MB for 2511452-byte allocation
D/dalvikvm( 3550): GC_CONCURRENT freed 1877K, 28% free 16720K/23216K, paused 4ms+3ms, total 37ms
D/dalvikvm( 3550): GC_CONCURRENT freed 2308K, 27% free 16984K/23216K, paused 2ms+6ms, total 56ms
D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 3550): GC_FOR_ALLOC freed 668K, 28% free 16880K/23216K, paused 29ms, total 29ms
I/dalvikvm-heap( 3550): Grow heap (frag case) to 22.109MB for 3767174-byte allocation
D/dalvikvm( 3550): GC_CONCURRENT freed 425K, 25% free 20426K/26896K, paused 8ms+4ms, total 62ms
D/dalvikvm( 3550): GC_FOR_ALLOC freed 2768K, 34% free 17970K/26896K, paused 26ms, total 26ms
W/jxcore-log( 3550): Initializing JXcore engine
W/jxcore-log( 3550): JXcore engine is ready
D/dalvikvm( 3550): GC_CONCURRENT freed 335K, 24% free 20612K/26896K, paused 1ms+2ms, total 37ms
D/dalvikvm( 3550): WAIT_FOR_CONCURRENT_GC blocked 34ms
W/jxcore-log( 3550): Starting JXcore engine
,W/jxcore-log( 3550): Platform android
W/jxcore-log( 3550): 
,W/jxcore-log( 3550): Process ARCH arm
W/jxcore-log( 3550): 
,I/jxcore-log( 3550): JXcore Cordova bridge is ready!
I/jxcore-log( 3550): 
,W/jxcore-log( 3550): JXcore engine is started
,I/chromium( 3550): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3550): Toggling radios to true
I/jxcore-log( 3550): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1019): Message: 1
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1233): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1263): Active network info is not available
,D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3596 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1233): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1019): setting operational mode to 1
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): Active network info is not available
I/jxcore-log( 3550): Radios toggled
I/jxcore-log( 3550): 
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3596): Adding HeadsetService
D/AdapterServiceConfig( 3596): Adding A2dpService
D/AdapterServiceConfig( 3596): Adding HidService
D/AdapterServiceConfig( 3596): Adding HealthService
D/AdapterServiceConfig( 3596): Adding PanService
D/AdapterServiceConfig( 3596): Adding GattService
,D/AdapterServiceConfig( 3596): Adding BluetoothMapService
,D/BluetoothAdapterService( 3596): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d1c880:true
,D/BluetoothAdapterState( 3596): make
,I/BluetoothAdapterState( 3596): Entering OffState
,I/bluedroid( 3596): init
,I/bte_conf( 3596): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3596): get_profile_interface socket
,I/GKI_LINUX( 3596): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3596): Address is:F4:F1:E1:5C:3B:E2
,I/bluedroid( 3596): config_hci_snoop_log
D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 3596): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3596): Name is: XT1039
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3596): Setting state to 11
I/BluetoothAdapterState( 3596): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3596): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3596): make
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3630 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1251): Proxy object connected
,D/BluetoothHeadset( 1251): Proxy object connected
,D/BluetoothHeadset( 1251): Proxy object connected
,D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 29ms
,D/BluetoothHeadset( 1019): Proxy object connected
,D/HeadsetService( 3596): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3596): classInitNative: succeeds
I/BluetoothAdapterState( 3596): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3596): Version 1.6
,D/HeadsetStateMachine( 3596): make
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,I/bluedroid( 3596): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
D/A2dpService( 3596): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3596): classInitNative: succeeds
,V/Avrcp   ( 3596): make
,I/bluedroid( 3596): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3596): classInitNative: succeeds
,D/A2dpStateMachine( 3596): make
,I/bluedroid( 3596): get_profile_interface a2dp
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,I/GKI_LINUX( 3596): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3596): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3596): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3596): classInitNative: succeeds
D/HidService( 3596): Received start request. Starting profile...
,I/bluedroid( 3596): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3596): classInitNative: succeeds
,D/HealthService( 3596): Received start request. Starting profile...
,I/bluedroid( 3596): get_profile_interface health
,I/BluetoothPanServiceJni( 3596): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3596): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3596): initializeNative(L110): pan
,I/bluedroid( 3596): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43cd9048
,I/BtGatt.JNI( 3596): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3596): handleDebugAction() action=null
D/BtGatt.GattService( 3596): Received start request. Starting profile...
D/BtGatt.GattService( 3596): start()
,I/bluedroid( 3596): get_profile_interface gatt
,D/BluetoothMapService( 3596): Received start request. Starting profile...
,D/BluetoothMapService( 3596): start()
,D/HeadsetPhoneState( 3596): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3596): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3596): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 3596): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3596): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3596): enable
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/bt_hci_bdroid( 3596): init
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,I/bt_vendor( 3596): bt-vendor : init
I/bt_hci_bdroid( 3596): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3596): userial_init
I/bt_hwcfg( 3596): Starting hciattach daemon
,I/bt_hwcfg( 3596): try to set false
I/bt_hwcfg( 3596): Starting hciattach daemon
,I/bt_hwcfg( 3596): try to set true
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,I/bt_hci_bdroid( 3596): bt_hc_worker_thread started
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/MDMCTBK (  277): send SAR ctrl over QMI
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,I/qcom-bluetooth( 3658): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/QsoftapCmd(  275): Got softap fwreload command we are passing on
,D/SoftapController(  275): Softap fwReload - Ok
I/ActivityManager( 1019): Killing 3216:com.android.providers.calendar/u0a8 (adj 15): empty #9
,I/qcom-bluetooth( 3667): /system/etc/init.qcom.bt.sh: Transport : smd 
D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring down wlan0
,I/qcom-bluetooth( 3668): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/qcom-bluetooth( 3670): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,I/qcom-bluetooth( 3671): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/qcom-bluetooth( 3672): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
D/WifiService( 1019): New client listening to asynchronous messages
,I/rmt_storage(  470): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb81ad1d0
I/rmt_storage(  470): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  470): wakelock acquired: 1, error no: 42
I/rmt_storage(  470): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1206201800)
E/Diag_Lib( 3675): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3675): Setting internal use port to rmnet0
E/Diag_Lib( 3675):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3675): Failed on DIAG init
E/Diag_Lib( 3675): linux_qmi_qmux_if_client_get_proc_name: pid=3675, proc_name=hci_qcomm_init
E/Diag_Lib( 3675): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3675): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3675): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3675): qmi_client [3675]: successfully connected to server, attempt=1
E/Diag_Lib( 3675): linux_qmi_qmux_if_client_get_client_id [3675]: qmux_client_id=13
E/Diag_Lib( 3675): qmi_client [3675] 13: qmux_client ID is initialized
E/Diag_Lib( 3675): qmi_client [3675] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3675): qmi_client [3675] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3675): qmi_client [3675] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3675): Sending signal ...... to read cmd data 
E/Diag_Lib( 3675): qmi error code.........:0
E/Diag_Lib( 3675): qmi sys error code.........:0
E/Diag_Lib( 3675): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3675): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3675): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3675): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3675): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3675): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3675): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3675): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3675): qmi_init:  Created client handle b8a88788
,E/Diag_Lib( 3675): qmi_client [3675] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3675): qmi_client [3675] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3675): Sending signal ...... to read cmd data 
E/Diag_Lib( 3675): qmi error code.........:0
,E/Diag_Lib( 3675): qmi sys error code.........:0
E/Diag_Lib( 3675): Setting the api flag to : 1
,E/Diag_Lib( 3675): qmi_client [3675] 13: sending 54 bytes on fd = 8
E/Diag_Lib( 3675): qmi_client [3675] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3675):  API Flag .............. 1 
,E/Diag_Lib( 3675):  Message ID ............... 92 
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1324): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3677): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3677): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/Diag_Lib( 3675): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3675): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3675): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3675): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3675): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3675): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3675): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3675): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3675): qmi_client [3675] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3675): qmi_client [3675] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3675): Sending signal ...... to read cmd data 
E/Diag_Lib( 3675): qmi error code.........:0
E/Diag_Lib( 3675): qmi sys error code.........:0
E/Diag_Lib( 3675): qmi_release: Released client handle ff
E/Diag_Lib( 3675): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3675): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3675): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3675): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3675): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3675): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3675): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3675): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3675): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3675): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3675): qmi_client [3675] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3675): qmi_client [3675] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3675): Sending signal ...... to read cmd data 
E/Diag_Lib( 3675): qmi error code.........:0
E/Diag_Lib( 3675): qmi sys error code.........:0
E/Diag_Lib( 3675): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3675] 13
E/Diag_Lib( 3675): qmi_client [3675] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3675): qmi_client [3675] 13: failed to locate client data
E/Diag_Lib( 3675): qmi_client [3675] 13: calling release of fd=8
E/Diag_Lib( 3675): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
D/WifiStateMachine( 1019): setWifiState: enabling
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,I/qcom-bluetooth( 3679): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3680): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/rmt_storage(  470): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  470): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  470): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1206201800) wakelock released: 1, error no: 0
I/rmt_storage(  470): 
E/Diag_Lib( 3677): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3677): Setting internal use port to rmnet0
,I/rmt_storage(  470): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb81ad1d0
,E/wpa_supplicant( 3677): baseband property is set to [msm]
,E/wpa_supplicant( 3677):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): card_info[i].card_state: 0x2
E/wpa_supplicant( 3677): card_info[i].error_code: 0x3
E/wpa_supplicant( 3677): SIM/USIM not ready
,E/wpa_supplicant( 3677): Error while reading SIM card status
,I/bt_hwcfg( 3596): bluetooth satus is on
I/GKI_LINUX( 3596): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,D/bt_userial_mct( 3596): userial_open(port:0)
I/bt-btu  ( 3596): btu_task pending for preload complete event
I/bt_userial_vendor( 3596): Done intiailizing UART
I/bt_userial_vendor( 3596): Done intiailizing UART
I/bt_userial_mct( 3596): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
,I/bt_vendor( 3596): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 3596): btu_task received preload complete event
,D/bt_userial_mct( 3596): Entering userial_read_thread()
E/wpa_supplicant( 3677): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): card_info[i].card_state: 0x2
E/wpa_supplicant( 3677): card_info[i].error_code: 0x3
E/wpa_supplicant( 3677): SIM/USIM not ready
,I/wpa_supplicant( 3677): eap_proxy: Card not ready
I/        ( 3596): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3596): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3596): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3596): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3596): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3596): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3596): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3596): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3596): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3596): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3596): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3596): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3596): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3596): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3596): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3596): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f12e049 
,E/bt-btm  ( 3596): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f12e049 
,E/bt-btif ( 3596): Calling BTA_HhEnable
E/bt-btif ( 3596): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3596): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3596): Name is: XT1039
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3596): Scan Mode:21
I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3596): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:8 len:6
D/BluetoothAdapterProperties( 3596): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3596): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,I/bte_conf( 3596): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,E/bt_mct  ( 3596): hci lib postload completed
I/bte_conf( 3596): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3596): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3596): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3596): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothPanServiceJni( 3596): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 3596): ScanMode =  21
D/BluetoothAdapterProperties( 3596): State =  11
D/BluetoothAdapterProperties( 3596): Setting state to 12
I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:9 len:4
I/BluetoothAdapterState( 3596): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 3596): Discoverable Timeout:120
,D/BluetoothAdapterService( 3596): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 3596): Entering On State
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1251): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothHeadset( 1251): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1251): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/qcom-bt-wlan-coex( 3694): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/BluetoothMapService( 3596): onReceive
,D/BluetoothMapService( 3596): STATE_ON
,D/BluetoothMapService( 3596): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothMapService( 3596): Map Service initSocket
,I/wpa_supplicant( 3677): Long line in configuration file truncated
W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/wpa_supplicant( 3677): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Message: 20
W/BluetoothAdapter( 3596): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@437b2218:true
E/BluetoothServiceJni( 3596): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 3596): Accepting socket connection...
I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3596): Scan Mode:21
D/LocalBluetoothProfileManager( 3630): Adding local A2DP profile
D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/BluetoothPbapService( 3596): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3596): Handler(): got msg=1
D/LocalBluetoothProfileManager( 3630): Adding local HEADSET profile
D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/BluetoothManagerService( 1019): Message: 30
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3596): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/BluetoothManagerService( 1019): Message: 30
E/BluetoothServiceJni( 3596): SOCK FLAG = 1 ***********************
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3630): Adding local MAP profile
D/BluetoothMap( 3630): Create BluetoothMap proxy object
D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3630): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3630): finishStartingService: stopping service
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/wpa_supplicant( 3677): COUNTRY Code Recived
,E/wpa_supplicant( 3677): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3677): baseband property is set to [msm]
,D/BluetoothA2dp( 3630): Proxy object connected
,D/A2dpProfile( 3630): Bluetooth service connected
,E/wpa_supplicant( 3677):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): card_info[i].card_state: 0x2
E/wpa_supplicant( 3677): card_info[i].error_code: 0x3
E/wpa_supplicant( 3677): SIM/USIM not ready
,E/wpa_supplicant( 3677): Error while reading SIM card status
E/wpa_supplicant( 3677): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3677): card_info[i].card_state: 0x2
E/wpa_supplicant( 3677): card_info[i].error_code: 0x3
E/wpa_supplicant( 3677): SIM/USIM not ready
,I/wpa_supplicant( 3677): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/dalvikvm( 1019): GC_EXPLICIT freed 22135K, 65% free 17800K/49980K, paused 6ms+10ms, total 151ms
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/BluetoothHeadset( 3630): Proxy object connected
,D/HeadsetProfile( 3630): Bluetooth service connected
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/BluetoothInputDevice( 3630): Proxy object connected
,D/HidProfile( 3630): Bluetooth service connected
,D/BluetoothPan( 3630): BluetoothPAN Proxy object connected
D/PanProfile( 3630): Bluetooth service connected
,D/BluetoothMap( 3630): Proxy object connected
D/WifiConfigStore( 1019): Loading config and enabling all networks
,D/MapProfile( 3630): Bluetooth service connected
,D/BluetoothMap( 3630): getConnectedDevices()
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3677): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothPbap( 3630): Proxy object connected
,D/PbapServerProfile( 3630): Bluetooth service connected
D/AuthorizationBluetoothService( 1324): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 3596): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothServiceJni( 3596): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 3596): Accept thread started.
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/CommandListener(  275): Setting iface cfg
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/CommandListener(  275): Trying to bring up p2p0
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
V/BluetoothFtpService( 3596): Ftp Service onCreate
I/BluetoothFtpService( 3596): FFFFFtp Service onCreate
V/BluetoothFtpService( 3596): Starting FTP service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
V/BluetoothFtpService( 3596): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3596): Handler(): got msg=1
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
,D/WifiP2pService( 1019): P2pEnabledState
V/BluetoothFtpService( 3596): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3596): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
W/BluetoothAdapter( 3596): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3596): SOCK FLAG = 3 ***********************
V/BluetoothFtpService( 3596): Succeed to create listening socket on channel 20
D/WifiStateMachine( 1019): handleMessage: X
V/BluetoothFtpService:RfcommSocketAcceptThread( 3596): Run Accept thread
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set country code PL
E/wpa_supplicant( 3677): COUNTRY Code Recived
E/wpa_supplicant( 3677): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
E/AuthorizationBluetoothService( 1324): Proximity feature is not enabled.
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set frequency band 2
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
,W/wpa_supplicant( 3677): wlan0: Failed to initiate AP scan
,D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1019): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-17ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-17ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3677): COUNTRY Code Recived
,E/wpa_supplicant( 3677): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-11ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-12ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  277): wifi_close_sockets: Exit
,E/MDMCTBK (  277): Attach monitor thread
,I/MDMCTBK (  277): createWifiMonitorThread: Started the wifi monitor thread -1205226456
,D/MDMCTBK (  277): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3677): wlan0: Failed to initiate AP scan
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  277): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3677): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3676): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3676): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/wpa_supplicant( 3677): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3677): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  499): NL - Read 312 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 192 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,I/wpa_supplicant( 3677): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3677): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3677): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3677): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277):  STA Connected !!
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
,I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit,
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205230792
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
,D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-53ms what=147462 obj=android.net.wifi.StateChangeResult@42151698 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-38ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4285e7b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246f190 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4246f190 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3550): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): my name is : motorola-XT1039_PT6617
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): attempting to connect to test coordinator
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): check test folder
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): found test : ./testFindPeers.js
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): found test : ./testReConnect.js
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): found test : ./testSendData.js
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Test app app.js loaded
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS ,
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 0c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 0c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i,
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42909100 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42909100 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42909100 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 20
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-8ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Coordinator is now connected to the server!
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42077868
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42077868
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1019): Setting time of day to sec=1448877100
,W/        ( 1019): Unable to set rtc to 1448877100: Invalid argument
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3801 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/PollingManager( 1530): now: 354874 ,futureTime: 86439121
,D/PollingManager( 1530): Polling alarm set to expire at: 86439121 Current Time: 354876
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1530): registerApp(): CCE
I/CCE     ( 1530): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1530): Registering with Alarm Manager to restart CCE
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/MMApiWebService( 1530): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
D/CCE     ( 1530): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/PollingManager( 1530): now: 354952 ,futureTime: 86439121
,D/PollingManager( 1530): Polling alarm set to expire at: 86439121 Current Time: 354952
,D/OtaApp  ( 1530): [debug] > CusSM.onRadioUp
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 1530): generating token using payload instead of using session token
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1530): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1530): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3837 uid=10056 gids={50056, 3003, 1028, 1015}
,I/jxcore-log( 3550): BLE advertisement not supported: Not supported
I/jxcore-log( 3550): 
,I/VacuumService( 1324): Vacuum at: now=1448877101046 tag=VacuumService
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3801): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f9dfa8, skipping init
I/openssl ( 3801): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3801): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3862 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3385:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
I/dalvikvm( 1354): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1354): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1354): VFY: replacing opcode 0x6e at 0x0033
,V/MmsConfig( 3862): mnc/mcc: 
V/MmsConfig( 3862): tag: bool value: enabledMMS - true
V/MmsConfig( 3862): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3862): tag: int value: maxImageHeight - 1944
D/DelayedSyncController( 3837): Delaying sync.
V/MmsConfig( 3862): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3862): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3862): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3862): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3862): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3862): tag: int value: recipientLimit - 20
V/MmsConfig( 3862): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3862): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3862): tag: bool value: enableSlideDuration - true
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
V/MmsConfig( 3862): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3862): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3862): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3862): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3862): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3862): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/GpsLocationProvider( 1019): NTP server returned: 1448877097805 (Mon Nov 30 10:51:37 CET 2015) reference: 351879 certainty: 9 system time offset: -3348
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
I/ActivityManager( 1019): Killing 3082:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GoogleURLConnFactory( 1354): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3889 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3419:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/Auth.Api.Credentials( 1354): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm( 1251): GC_EXPLICIT freed 1460K, 45% free 9519K/17224K, paused 5ms+8ms, total 74ms
,D/MobileConnectivityChangeReceiver( 3889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3889): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3889): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3889): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm( 1354): GC_CONCURRENT freed 1656K, 32% free 11717K/17224K, paused 5ms+7ms, total 45ms
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3904 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3101:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1354): Checkin interval check for package: unspecified last checkin: 1448627417884 min interval config: 0 actual interval: 249683409
,I/CheckinService( 1354): Checking schedule, now: 1448877101309 next: 1448627447854
,I/CheckinService( 1354): active receiver: enabled
,I/CheckinService( 1354): Preparing to send checkin request
,I/EventLogService( 1354): Accumulating logs since 1448876860018
,I/CheckinRequestBuilder( 1354): Checkin reason type: 8 attempt count: 1
D/WifiService( 1019): New client listening to asynchronous messages
E/ActivityThread( 1354): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1019): GC_EXPLICIT freed 1874K, 65% free 17858K/49980K, paused 4ms+10ms, total 105ms
,V/WebViewChromiumFactoryProvider( 3904): Binding Chromium to main looper Looper (main, tid 1) {41f9a9a0}
,I/LibraryLoader( 3904): Expected native library version number "",actual native library version number ""
,I/chromium( 3904): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3904): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3904): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3904): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3904): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3904): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3904): Local Branch: 
I/Adreno-EGL( 3904): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3904): Local Patches: NONE
I/Adreno-EGL( 3904): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3904): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/DelayedSyncController( 3837): Delaying sync.
,W/GAV2    ( 3904): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3904): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1019): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3949 uid=10064 gids={50064, 3003, 1028, 1015}
,D/ActivityThread( 3949): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,W/GAV2    ( 3949): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/NSApplication( 3904): Starting up...
,D/dalvikvm( 1324): GC_CONCURRENT freed 1907K, 39% free 10649K/17224K, paused 3ms+5ms, total 45ms
,I/ImageResourceManager( 3118): ImageResourceManager: uninitalized
,I/iu.Environment( 3118): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3118): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3445:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3118): num queued entries: 0
,I/iu.UploadsManager( 3118): num updated entries: 0
,I/iu.SyncManager( 3118): NEXT; no task
,I/iu.SyncManager( 1354): SYNC; picasa accounts
,I/MMApiWSBase( 1530): doRequest(): error in response: 403
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/UdcCache:FPQuery( 1354): Bootstrapping UDC settings cache for all accounts
,I/MMApiWSBase( 1530): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1530): doRequest(): v1/ns/list/messages resp length: 75
,I/MMApiWebService( 1530): _inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1530): _inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/NetworkLogImpl( 1354): Loaded NetworkSpeedPredictor
,I/MMApiWebService( 1530): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 1530): Got request to obtain new Session .. doing so now
,D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
,I/iu.Environment( 1354): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/iu.UploadsManager( 1354): num queued entries: 0
,I/iu.UploadsManager( 1354): num updated entries: 0
,I/iu.SyncManager( 1354): NEXT; no task
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
I/openssl ( 3801): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3801): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3889): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3889): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3118): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 1354): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1354): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1354): VFY: replacing opcode 0x71 at 0x0046
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3990 uid=10007 gids={50007, 3003}
,D/dalvikvm( 1354): DexOpt: --- BEGIN 'ads386677975.jar' (bootstrap=0) ---
,D/ExtensionsFactory( 3990): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4009 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3158:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4015 uid=10008 gids={50008, 3003, 1028, 1015}
I/Gmail   ( 3949): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1019): Killing 3630:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Gmail   ( 3949): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/WifiService( 1019): Client connection lost with reason: 4
,I/Gmail   ( 3949): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3949): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/AlarmClock( 4009): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 1354): GC_CONCURRENT freed 1482K, 29% free 12272K/17224K, paused 15ms+5ms, total 95ms
,I/AlarmClock( 4009): Displaying next alarm time: ''
,V/AlarmClock( 4009): AlarmInitReceiver finished
,I/CalendarProvider2( 4015): Created com.android.providers.calendar.CalendarAlarmManager@41fb7b70(com.android.providers.calendar.CalendarProvider2@41faf728)
,I/GCM     ( 1324): GCM config loaded
I/ActivityManager( 1019): Killing 3801:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4039 uid=10098 gids={50098}
,I/Gmail   ( 3949): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11516, normalSync: true
,D/dalvikvm( 4003): DexOpt: load 24ms, verify+opt 35ms, 192820 bytes
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4055 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
D/dalvikvm( 4039): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41fa3d20, skipping init
D/TimeService( 4039): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448877102280
D/        ( 4039): TimeServiceNative: User Time to be set is 1448877102280
D/QC-time-services( 4039): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4039): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4039): Lib:time_genoff_operation: pargs->ts_val = 1448877102280
D/QC-time-services( 4039): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  454): Daemon: Connection accepted:time_genoff
D/QC-time-services(  454): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448877102280
D/QC-time-services(  454): Daemon:genoff_opr: Base = 2, val = 1448877102280, operation = 0
D/QC-time-services(  454): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/30/115 9:45:50
D/QC-time-services(  454): Daemon:Value read from RTC seconds = 1448876750000
D/QC-time-services(  454): Daemon:new time 1448877102280 
D/QC-time-services(  454): Daemon: delta 352280 genoff 352280 
D/QC-time-services(  454): Daemon:genoff_persistent_update: Writing genoff = 352280 to memory
D/QC-time-services(  454): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  454): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  454): Updating the TOD offset
D/QC-time-services(  454): Daemon:genoff_persistent_update: Writing genoff = 352280 to memory
D/QC-time-services(  454): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  454): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  454): Daemon:Update to modem bit set
D/QC-time-services(  454): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  454): Daemon: Base = 2, Value being sent to MODEM = 18446743757745103896
E/QC-time-services( 4039): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  454): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  454): Daemon: Time-services: Waiting to acceptconnection
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
D/dalvikvm( 1354): DexOpt: --- END 'ads386677975.jar' (success) ---
,D/dalvikvm( 1354): DEX prep '/data/data/com.google.android.gms/cache/ads386677975.jar': unzip in 0ms, rewrite 251ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,I/CheckinService( 1354): Checkin interval check for package: unspecified last checkin: 1448627417884 min interval config: 0 actual interval: 249684443
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,W/dalvikvm( 4055): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4055): VFY: replacing opcode 0x60 at 0x000b
,I/GCM     ( 1324): Ack for not saved message 20
,I/dalvikvm( 4055): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4055): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 4055): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4055): install
,I/MultiDex( 4055): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/MultiDex( 4055): loading existing secondary dex files
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/MultiDex( 4055): load found 3 secondary dex files
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,I/MultiDex( 4055): install done
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4074 uid=10065 gids={50065, 3003}
,D/dalvikvm( 1019): GC_EXPLICIT freed 835K, 65% free 17821K/49980K, paused 8ms+10ms, total 107ms
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/dalvikvm( 4055): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4055): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4055): VFY: replacing opcode 0x62 at 0x000a
D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
D/dalvikvm( 4055): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4055): VFY: unable to resolve instance field 46
,D/dalvikvm( 4055): VFY: replacing opcode 0x54 at 0x005f
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
D/dalvikvm( 4055): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4055): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4055): VFY: replacing opcode 0x62 at 0x0047
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm( 4055): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4055): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/IInputConnectionWrapper( 3550): showStatusIcon on inactive InputConnection
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/dalvikvm( 4055): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fa5628
,D/dalvikvm( 4055): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fa5628
D/dalvikvm( 4055): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fa5628, skipping init
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 4055): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fa5628
D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
D/dalvikvm( 4055): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fa5628
V/JNIHelp ( 4055): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,W/AbstractGoogleClient( 4074): Application name is not set. Call Builder#setApplicationName.
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,229
I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1530): GC_CONCURRENT freed 2993K, 37% free 10882K/17224K, paused 3ms+4ms, total 49ms
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{41f90aa8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/dalvikvm( 4055): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fa5628
,D/dalvikvm( 4055): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41fa5628
D/dalvikvm( 4055): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fa5628
,D/dalvikvm( 4055): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fa5628
,I/MMApiWSBase( 1530): doRequest(): error in response: 403
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1530): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1530): doRequest(): v1/us/devices/check resp length: 75
,I/MMApiWebService( 1530): _inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1530): _inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1530): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiProvisionService( 1530): Got request to obtain new Session .. doing so now
D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/ProviderInstaller( 4055): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,E/MDM     ( 1215): [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1354): Restart initialization of location
,I/dalvikvm( 4055): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 4055): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x000d
,D/AuthorizationBluetoothService( 1324): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 1324): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/AuthorizationBluetoothService( 1324): Proximity feature is not enabled.
,D/MMApiProvisionService( 1530): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1354): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/dalvikvm( 4055): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4055): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x0220
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1273): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/MMApiProvisionService( 1530): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1530): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1530): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1530): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 02 10:50:44 CET 2015
,D/MMApiProvisionService( 1530): _setMMApiCredInfo: storing credential info 
,I/dalvikvm( 4055): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4055): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,E/dalvikvm( 4055): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
,E/MMApiProvisionService( 1530): handleResponse(): no settings sent by the server:
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,W/dalvikvm( 4055): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,D/dalvikvm( 4055): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4055): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4055): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4055): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4055): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4055): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,D/MMApiWebService( 1530): MMApiWebService told us to retry waiting request since device is successfully provisioned: 2
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
D/DEBUG   ( 1530): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1530): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1530): Received shoulder tap
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/dalvikvm( 1215): GC_EXPLICIT freed 2044K, 41% free 10296K/17224K, paused 3ms+7ms, total 50ms
W/GCoreFlp( 1215): No location to return for getLastLocation()
W/FusedLocationProvider( 1324): location=null
D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41fd4380)
,D/GetNotificationsWS( 1530): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1530): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=2
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  281): App is not loaded in QSEE
E/QSEECOMAPI: (  281): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  281): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  281): App is not loaded in QSEE
E/QSEECOMAPI: (  281): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  281): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  281): App is not loaded in QSEE
,D/QSEECOMAPI: (  281): Loaded image: APP id = 3
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53b6000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53b6000
,I/dalvikvm( 4055): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 4055): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x0033
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,W/dalvikvm( 4055): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4055): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4055): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4055): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4055): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4055): VFY: replacing opcode 0x6e at 0x00bb
D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/GoogleURLConnFactory( 4055): Using platform SSLCertificateSocketFactory
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3066817017
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4055): Install completed successfully. count=13 extracted=0
,I/CalendarProvider2( 4015): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4015): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3990): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3990): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/MMApiWSBase( 1530): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1530): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/GetConfigurationSnapshotOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/dalvikvm( 1530): Jit: resizing JitTable from 4096 to 8192
,D/Checkin ( 1530): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1530): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1530): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1530): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1530): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/PhenotypeFlagCommitter( 1324): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1324): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1324): GC_CONCURRENT freed 1852K, 38% free 10728K/17224K, paused 3ms+4ms, total 31ms
,D/dalvikvm( 4055): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42345e00
D/dalvikvm( 4055): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42345e00
,D/dalvikvm( 4055): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42345e00, skipping init
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/MMApiWSBase( 1530): doRequest(): v1/us/devices/check resp length: 2314
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1530): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-520489807 for reqID:  error: None
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@42740d40 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@423cc040
,D/OtaWebService( 1530): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@427423e0 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@423cc040
,D/OtaWebService( 1530): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
I/OtaApp  ( 1530): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: dest Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU: current Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: size 12503823
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 1530): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > Next Polling is scheduled at 359 mins from now
E/OtaApp  ( 1530): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
D/PollingManager( 1530): registerApp(): cUsPollingService
D/PollingManager( 1530): registerApp(): shortest interval is 21599000
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/PollingManager( 1530): Polling alarm set to expire at: 21956955 Current Time: 357956
,D/OtaApp  ( 1530): [debug] > prevDestVersion = Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU
,W/OtaApp  ( 1530): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 1530): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1448877103897, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 1530): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1448877103923, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1530): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgrade1448877103948false
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1448877103
,I/OtaApp  ( 1530): [info] > retrieving device info from cce
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/BSUtils ( 1530): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/OtaApp  ( 1530): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update handle new version returned false
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaWebService( 1530): [info] > Received web service call for request :v1/us/devices/state
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1530): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1530): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,D/OtaApp  ( 1530): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :wait
,D/OtaWebService( 1530): [debug] > appending web service response to serviceHandler
,D/OtaWebService( 1530): [debug] > Removing request :v1/us/devices/check from queue
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1530): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1530): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1530): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1530): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1530): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1530): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1530): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
,D/CalendarSyncAdapter( 4074): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1019): Killing 3862:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WVCdm   (  281): CdmEngine::OpenSession
D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=4064552327
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4126 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1530): GC_CONCURRENT freed 1968K, 38% free 10841K/17224K, paused 4ms+3ms, total 28ms
,W/Uploader( 1324):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/ContactLocale( 4126): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4055): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 3949): GC_EXPLICIT freed 5132K, 44% free 9740K/17224K, paused 3ms+4ms, total 75ms
,I/Gmail   ( 3949): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11631, normalSync: true
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Gmail   ( 3949): lowestBackward conversation id 0
,D/dalvikvm( 4142): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4055): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4055): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 82ms
,I/Adreno-EGL( 4055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4055): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4055): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4055): Local Branch: 
I/Adreno-EGL( 4055): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4055): Local Patches: NONE
I/Adreno-EGL( 4055): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1019): Killing 3889:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ChimeraCfgMgr( 1354): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1354): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1324): GC_CONCURRENT freed 1546K, 36% free 11134K/17224K, paused 7ms+8ms, total 44ms
,I/Adreno-EGL( 4055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4055): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4055): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4055): Local Branch: 
I/Adreno-EGL( 4055): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4055): Local Patches: NONE
I/Adreno-EGL( 4055): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/GetCommittedConfigurationOperation( 1324): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/MMApiWSBase( 1530): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1530): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.1090350247 for reqID:  error: None
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@41fe2e88 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42553250
,D/OtaWebService( 1530): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@420aa990 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42553250
,D/OtaWebService( 1530): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
I/dalvikvm( 1354): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.GmsNetworkTrafficStats.setThreadStatsTag
W/dalvikvm( 1354): VFY: unable to resolve virtual method 1311: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1354): VFY: replacing opcode 0x6e at 0x0033
,D/OtaApp  ( 1530): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1530): [debug] > exec delete from status where _id=1
,I/Adreno-EGL( 4055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4055): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4055): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4055): Local Branch: 
I/Adreno-EGL( 4055): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4055): Local Patches: NONE
I/Adreno-EGL( 4055): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 1354): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
,W/dalvikvm( 1354): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 1354): VFY: replacing opcode 0x6e at 0x000d
,D/OtaApp  ( 1530): [debug] > stopTimer, cancel()
,D/OtaApp  ( 1530): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1530): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EUalready working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK1448877104999false
,V/AccountUtils( 1354): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1354): Starting sync for 3a3529a
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1448877103
,I/OtaApp  ( 1530): [info] > retrieving device info from cce
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/BSUtils ( 1530): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/GamesSyncAdapter( 1354): User is not G+ enabled. Aborting sync
,I/OtaApp  ( 1530): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
I/GamesSyncAdapter( 1354): Sync duration for 3a3529a: 15
,I/Adreno-EGL( 4055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4055): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4055): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4055): Local Branch: 
I/Adreno-EGL( 4055): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4055): Local Patches: NONE
I/Adreno-EGL( 4055): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/OtaWebService( 1530): [info] > Received web service call for request :v1/us/devices/state
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1530): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaWebService( 1530): [debug] > appending web service response to serviceHandler
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaWebService( 1530): [debug] > Removing request :v1/us/devices/state from queue
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/ChimeraCfgMgr( 1354): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1354): Module APK com.google.android.play.games already loaded
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
I/dalvikvm( 1354): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.permission.PermissionUtils.getMissingPermissionGroups
W/dalvikvm( 1354): VFY: unable to resolve virtual method 349: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 1354): VFY: replacing opcode 0x6e at 0x0036
D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1354): GC_CONCURRENT freed 2317K, 31% free 11991K/17224K, paused 4ms+5ms, total 45ms
,W/SQLiteConnectionPool( 1354): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/Settings( 4055): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 1019): GC_EXPLICIT freed 1307K, 65% free 17768K/49980K, paused 5ms+9ms, total 94ms
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,W/BaseAppContext( 1354): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1354): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1354): Module APK com.google.android.play.games already loaded
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4172 uid=10059 gids={50059, 3003, 1028, 1015}
,E/dalvikvm( 1354): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
,W/dalvikvm( 1354): VFY: unable to resolve new-instance 177 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
,D/dalvikvm( 1354): VFY: replacing opcode 0x22 at 0x0013
,D/dalvikvm( 1354): DexOpt: unable to opt direct call 0x0397 at 0x1a in Lcom/google/android/gms/games/ui/util/UiUtils;.constructButtonBackground
,I/ActivityManager( 1019): Killing 3837:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4186 uid=10100 gids={50100, 3003, 1028, 1015, 3002}
,I/CheckinTask( 1354): Sending checkin request (11841 bytes)
,W/ActiveOrDefaultContextProvider( 4172): Missing scope.enter somewhere. Returning default context
,D/MMApiWSBase( 1530): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1530): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-1700916427 for reqID:  error: None
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@42392730 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@422de838
,D/OtaWebService( 1530): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1530): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@4230f270 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@422de838
,D/OtaWebService( 1530): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaApp  ( 1530): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1530): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 1530): [debug] > stopTimer, have stoped, do nothing
,D/OtaApp  ( 1530): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,W/GAV2    ( 4172): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaWebService( 1530): [debug] > appending web service response to serviceHandler
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1530): [debug] > Removing request :v1/us/devices/state from queue
,E/ActivityThread( 4172): Failed to find provider info for com.google.android.apps.docs.editors.kix.statesyncer
D/OtaWebService( 1530): [debug] > No pending web request. shutdown webservice
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,E/ActivityThread( 4172): Failed to find provider info for com.google.android.apps.docs.editors.trix.statesyncer
I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
E/ActivityThread( 4172): Failed to find provider info for com.google.android.apps.docs.editors.punch.statesyncer
E/ActivityThread( 4172): Failed to find provider info for com.google.android.apps.docs.editors.drawings.statesyncer
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaWebService( 1530): [info] > Stopping webservice android service
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/PlayMovies( 4186): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1530): GC_CONCURRENT freed 2029K, 37% free 10883K/17224K, paused 4ms+4ms, total 44ms
,D/WifiService( 1019): acquireWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@4279fbc8}
,I/MediaRouter( 4186): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 4186): MediaRouteManager.restoreRoute:197 sessionRestore routeId: 
,D/PlayMovies( 4186): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 4186): TransferService.onCreate:52 creating transfer service
,D/PlayMovies( 4186): MediaRouteManager.onRouteAdded:138 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4186): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4186): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,I/CheckinRequestBuilder( 1354): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1354): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1324): GC_EXPLICIT freed 1066K, 37% free 10962K/17224K, paused 4ms+5ms, total 47ms
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,I/CheckinTask( 1354): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1354): Checking schedule, now: 1448877106296 next: 1449470176291
,I/CheckinService( 1354): active receiver: disabled
,D/CheckinService( 1354): Recording last checkin time for package unspecified as 1448877106315
,D/GCM     ( 1324): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/PlayMovies( 4186): SyncService.syncAllPurchases:159 Starting sync for thalitester@gmail.com
,I/GAV2    ( 3904): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3949): Thread[GAThread,5,main]: No campaign data found.
,I/PlayMovies( 4186): SyncService$3.onResponse:164 Sync completed for thalitester@gmail.com
,I/ActivityManager( 1019): Killing 3118:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4252 uid=10057 gids={50057, 3003, 1028}
,W/GAV2    ( 4172): DocsSyncAdapter-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,V/com.google.android.apps.common.multidex.Tracer( 4252): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4252): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4252): Package last updated: Jul 8, 2014 5:38:19.0
,D/WifiService( 1019): releaseWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@4279fbc8}
V/com.google.android.apps.common.multidex.Tracer( 4252): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4252): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4252): Package last updated: Jul 8, 2014 5:38:19.0
V/com.google.android.apps.common.multidex.Tracer( 4252): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fad5e0, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41fae350, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41fae6a8]
,V/com.google.android.apps.common.multidex.Tracer( 4252): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fad5e0.
I/ActivityManager( 1019): Killing 4039:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/com.google.android.apps.common.multidex.Tracer( 4252): Patching was successful.
,I/dalvikvm( 1215): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4267 uid=10057 gids={50057, 3003, 1028}
,V/com.google.android.apps.common.multidex.Tracer( 4267): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4267): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4267): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4267): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4267): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4267): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4267): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fb16d8, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41fb2448, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41fb27a0]
,V/com.google.android.apps.common.multidex.Tracer( 4267): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fb16d8.
,V/com.google.android.apps.common.multidex.Tracer( 4267): Patching was successful.
,I/GCoreUlr( 1215): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1215): Using Auth Proxy for data requests.
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1215): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x00bb
,D/dalvikvm( 1019): GC_EXPLICIT freed 1089K, 65% free 17791K/49980K, paused 4ms+10ms, total 105ms
,I/GCoreUlr( 1215): GCM ID uploaded for account#2#
,I/GCoreUlr( 1215): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1215): DispatchingService.onCreate()
,I/ActivityManager( 1019): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.offline.sync.OfflineSyncService: pid=4302 uid=10102 gids={50102, 3003, 1028, 1015}
,I/GCoreUlr( 1215): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1215): Unbound from all location providers
,I/GCoreUlr( 1215): DispatchingService.onDestroy()
,I/GCoreUlr( 1215): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1215): Unbound from all location providers
,I/GlobalDismissManager( 3990): no sender configured
,D/AlertService( 3990): Beginning updateAlertNotification
,D/AlertService( 3990): No fired or scheduled alerts
,D/AlertService( 3990): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3990): No events found starting within 1 week.
,I/ActivityManager( 1019): Killing 4009:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/YouTube ( 4302): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4302): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4302): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,D/YouTube ( 4302): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/YouTube ( 4302): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/YouTube ( 4302): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/dalvikvm( 1324): GC_EXPLICIT freed 1190K, 37% free 10930K/17224K, paused 2ms+5ms, total 33ms
,D/YouTube ( 4302): apps.youtube.core.player.Director.c:360 VideoStage: NEW
,I/MediaRouter( 4302): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 4302): apps.youtube.core.client.s.a:114 event [version=5.6.36-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 4302): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=OOR12PiaL5kcBDCoRWtvsQ&bundleid=com.google.android.youtube&appversion=5.6.36&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448877108&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/YouTube ( 4302): apps.youtube.app.offline.sync.OfflineSyncService.onCreate:21 PUDL creating sync service for the 1st time
,W/YouTube ( 4302): apps.youtube.app.offline.sync.OfflineSyncService.onBind:28 PUDL binding sync adapter
,D/YouTube ( 4302): apps.youtube.common.d.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.h
,D/YouTube ( 4302): apps.youtube.datalib.offline.h.a:34 Network change detected, dispatch offline http requests.
,D/YouTube ( 4302): apps.youtube.app.offline.sync.a.onPerformSync:60 OfflineSyncAdapter.onPerformSync() called!
,I/ActivityManager( 1019): Killing 4015:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/YouTube ( 4302): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.o with ScheduledExecutorService for repeating execution.
,I/GoogleConversionPing( 4302): Ping responded with response code 200
,I/ActivityManager( 1019): Killing 4074:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
,I/ActivityManager( 1019): Killing 3990:com.android.calendar/u0a7 (adj 15): empty #10
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1354): GC_CONCURRENT freed 1833K, 30% free 12139K/17224K, paused 4ms+5ms, total 51ms
,E/Auth.Api.Credentials( 1354): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4375 uid=10065 gids={50065, 3003}
,W/AbstractGoogleClient( 4375): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4388 uid=10008 gids={50008, 3003, 1028, 1015}
,I/CalendarProvider2( 4388): Created com.android.providers.calendar.CalendarAlarmManager@41fb7c78(com.android.providers.calendar.CalendarProvider2@41faf830)
,V/CalendarSyncAdapter( 4375): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-12-25T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,D/CalendarSyncAdapter( 4375): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1019): Killing 3949:com.google.android.gm/u0a64 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CalendarProvider2( 4388): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4388): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4417 uid=10007 gids={50007, 3003}
,I/ActivityManager( 1019): Killing 3904:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4126:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExtensionsFactory( 4417): No custom extensions.
D/AlertReceiver( 4417): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4417): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1354): Note: class Lcom/google/android/gms/games/internal/IGamesService$Stub; has 207 unimplemented (abstract) methods
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/GAV2    ( 4172): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4469 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+12ms, total 39ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/dalvikvm( 1019): GC_CONCURRENT freed 1988K, 64% free 18006K/49980K, paused 4ms+9ms, total 84ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 52ms
,I/Babel   ( 4469): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4469): MmsConfig.loadMmsSettings
I/Babel   ( 4469): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
I/Babel   ( 4469): MmsConfig.loadFromDatabase
,V/GmsNetworkLocationProvi( 1215): DISABLE
,I/GCoreNlp( 1215): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 4469): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4469): MmsConfig.loadFromResources
,E/Babel   ( 4469): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4469): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4469): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4508 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 4186:com.google.android.videos/u0a100 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4527 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4172:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2172): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4542 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4302:com.google.android.youtube/u0a102 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4508): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4558 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/PackageBroadcastService( 1354): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4576 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4267:com.google.android.apps.cloudprint/u0a57 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/PackageBroadcastService( 1354): Null package name or gms related package.  Ignoreing.
,I/ActivityManager( 1019): Killing 4252:com.google.android.apps.cloudprint:sync/u0a57 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1354): updateResources: need to parse f{com.google.android.gms}
,I/iu.UploadsManager( 4542): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 4558): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fa1ec8, skipping init
I/openssl ( 4558): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4558): Crypto mode 0 already enabled
,I/dalvikvm( 4576): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4576): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x000e
,I/iu.UploadsManager( 4542): End new media; added: 0, uploading: 0, time: 79 ms
,I/iu.Environment( 4542): update battery state; isPlugged? true*
I/iu.Environment( 4542): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 4542): Start processing all media
,I/iu.FingerprintManager( 4542): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4542): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4542): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4542): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4542): Finished generating fingerprints; 0.019 seconds
,I/iu.FingerprintManager( 4542):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/Finsky  ( 4576): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2172): UpdateCorporaTask done [took 359 ms] updated apps [took 359 ms] 
,I/dalvikvm( 4576): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4576): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4576): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4576): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4576): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/dalvikvm( 4576): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4576): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4576): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4576): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4576): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4576): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4576): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4576): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4576): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4576): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4576): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4576): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4576): Skipping gmscore version check
,D/Finsky  ( 4576): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4576): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4576): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4576): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4576): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4576): VFY: replacing opcode 0x6e at 0x0017
,D/Finsky  ( 4576): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/InternalIcingCorporaPro( 2172): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/PackageBroadcastService( 1354): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 1354): CP2 sync disabled
,I/ActivityManager( 1019): Killing 4388:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2172): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
,V/AlarmManager( 1019): sending alarm Alarm{427aabc8 type 0 com.android.vending}
,D/Finsky  ( 4576): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4576): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4576): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4576): VFY: replacing opcode 0x62 at 0x0038
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1019): GC_EXPLICIT freed 783K, 65% free 17877K/49980K, paused 3ms+8ms, total 88ms
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1324): GC_EXPLICIT freed 296K, 37% free 10932K/17224K, paused 3ms+5ms, total 35ms
,I/qtaguid ( 4576): Failed write_ctrl(u 63) res=-1 errno=22
I/qtaguid ( 4576): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4576): untagSocket(63) failed with errno -22
,D/Finsky  ( 4576): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4576): Total arena pages for JIT: 11
,I/dalvikvm( 4576): Total arena pages for JIT: 12
,I/dalvikvm( 4576): Total arena pages for JIT: 13
,I/dalvikvm( 4576): Total arena pages for JIT: 14
,I/qtaguid ( 4576): Failed write_ctrl(u 63) res=-1 errno=22
,I/qtaguid ( 4576): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4576): untagSocket(63) failed with errno -22
,D/dalvikvm( 4576): GC_CONCURRENT freed 4853K, 29% free 12302K/17224K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4576): GC_CONCURRENT freed 1294K, 25% free 13056K/17224K, paused 3ms+3ms, total 29ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 4576): GC_CONCURRENT freed 853K, 18% free 14250K/17224K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4576): GC_CONCURRENT freed 974K, 12% free 15324K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/GlobalDismissManager( 4417): no sender configured
,D/AlertService( 4417): Beginning updateAlertNotification
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4646 uid=10008 gids={50008, 3003, 1028, 1015}
,I/CalendarProvider2( 4646): Created com.android.providers.calendar.CalendarAlarmManager@41fb4f38(com.android.providers.calendar.CalendarProvider2@41facaf0)
,D/AlertService( 4417): No fired or scheduled alerts
,D/AlertService( 4417): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4417): No events found starting within 1 week.
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 4576): Failed write_ctrl(u 63) res=-1 errno=22
I/qtaguid ( 4576): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4576): untagSocket(63) failed with errno -22
,D/Finsky  ( 4576): [1] LibraryUtils.isAvailable: com.quickoffice.android available because owned, overriding [restriction=7].
,D/Finsky  ( 4576): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4576): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1019): sending alarm Alarm{4206a1d0 type 0 com.android.vending}
,D/dalvikvm( 4576): GC_CONCURRENT freed 2247K, 14% free 15126K/17468K, paused 2ms+3ms, total 57ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 4576): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/Finsky  ( 4576): [381] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1215): client connected with version: 8296000
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 4646): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4646): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4417): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/ActivityManager( 1019): Killing 4375:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AlertService( 4417): 0 Action = android.intent.action.PROVIDER_CHANGED
,V/AlarmManager( 1019): sending alarm Alarm{4259cc18 type 3 android}
,I/GlobalDismissManager( 4417): no sender configured
,D/AlertService( 4417): Beginning updateAlertNotification
,D/AlertService( 4417): No fired or scheduled alerts
,D/AlertService( 4417): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4417): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 4055:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{4257d920 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{42577068 type 0 com.android.vending}
,D/Finsky  ( 4576): [372] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4576): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43aaf3f8 type 2 android}
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 50618 ms ago
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4702 uid=10059 gids={50059, 3003, 1028, 1015}
,W/ActiveOrDefaultContextProvider( 4702): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 4702): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 4702): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1019): Killing 4469:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GAV2    ( 4702): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1019): sending alarm Alarm{420a9108 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ab29c0 type 2 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3550): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector command called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75
,I/jxcore-log( 3550): Start now : testSendData.js
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): check server
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): serverPort is 41645
I/jxcore-log( 3550): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): initialize: F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6617
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3550): initialize: My bluetooth address is F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): setState: INITIALIZED
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): verifyIdentityString: Identity string created: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6617"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3596): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): start: OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): setState: RUNNING
I/jxcore-log( 3550): StartBroadcasting started ok
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): do fake peer & start
I/jxcore-log( 3550): 
I/jxcore-log( 3550): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:40.326Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:53:40.326Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:40.327Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/jxcore-log( 3550): 2015-11-30T09:53:40.337Z SendDataTCPServer.js: TCP/IP server is bound to port: 41645
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,W/bt-l2cap( 3596): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4747 uid=10011 gids={50011, 3003, 3002, 3001}
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4406cd20:true
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c7a30:true
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4763 uid=10016 gids={50016, 3002}
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,I/ActivityManager( 1019): Killing 4558:android.process.media/u0a18 (adj 15): empty #9
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/ActivityManager( 1019): Killing 4508:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 281)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 281)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 281)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 281)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 281)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, LGE-Nexus 5_PT9919
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 53369
I/BtConnectorHelper( 3550): Request socket is using : 53369
,I/BtToRequestSocket( 3550): Now accepting connections
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothMetrics( 3596): btclass1f00
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :53369
,I/jxcore-log( 3550): 2015-11-30T09:53:42.448Z SendDataConnector.js: CLIENT connected to 53369, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:42.450Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 53369
,I/BtToRequestSocket( 3550): Set local streams
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,I/jxcore-log( 3550): 2015-11-30T09:53:42.473Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.394Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.553Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.600Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.624Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.694Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.802Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:43.850Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:44.032Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [50:2e:6c:ac:21:50]: 0, 0, 0
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 285)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 285)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 80 bytes successfully (thread ID: 285)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 285)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 285
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 285)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 285)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/jxcore-log( 3550): 2015-11-30T09:53:46.976Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 5 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 6 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 7 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 10 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3596): Index: 11 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 50:2E:6C:AC:21:50
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T09:53:47.955Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:47.965Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:47.975Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:47.999Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.017Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.026Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.052Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.089Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.105Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.115Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.127Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.138Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.170Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.179Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.190Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.198Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.231Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.242Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.276Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.283Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.308Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.329Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.344Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.404Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.429Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.461Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.479Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.490Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.498Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.508Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.568Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.601Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.641Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.717Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.750Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.792Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.830Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.850Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.871Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:53:48.910Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42829f00 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T09:54:34.032Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:34.032Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:34.041Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:34.042Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:34.044Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3550): Disconnect outgoing peer: LGE-Nexus 5_PT9919
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): invalid rfc slot id: 5
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x49
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T09:54:38.954Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T09:54:39.049Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:39.050Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=1
W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6,
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T09:54:44.052Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:44.052Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:54:44.053Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:54:44.053Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Nexus 5 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[129]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 290)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 290)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 290)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 290)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, LGE-Nexus 5_PT9919
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 290)
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 60940
I/BtConnectorHelper( 3550): Request socket is using : 60940
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :60940
,I/jxcore-log( 3550): 2015-11-30T09:54:45.891Z SendDataConnector.js: CLIENT connected to 60940, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:54:45.892Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 60940
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T09:54:45.911Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,V/AlarmManager( 1019): sending alarm Alarm{42792f30 type 3 android}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 80 bytes successfully (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 294
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 294)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T09:55:10.949Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:11.552Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:11.557Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:11.562Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T09:55:11.573Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:11.626Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:11.630Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T09:55:35.983Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:35.984Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:35.986Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:35.988Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:35.991Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: LGE-Nexus 5_PT9919
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T09:55:40.991Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:40.992Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T09:55:45.997Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:45.998Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:46.000Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:55:46.002Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Nexus 5 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[130]}
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,V/AlarmManager( 1019): sending alarm Alarm{4292e7e8 type 3 android}
,W/bt-btif ( 3596): invalid rfc slot id: 7
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x40
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T09:56:01.504Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/dalvikvm( 1215): GC_CONCURRENT freed 1776K, 40% free 10440K/17224K, paused 2ms+5ms, total 46ms
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420df698)
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,E/bt-btif ( 3596): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:10, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/jxcore-log( 3550): 2015-11-30T09:56:16.026Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:16.028Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:16.032Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,W/jxcore-log( 3550): $$jxcore_callback_10 wasn't registered
W/jxcore-log( 3550): 
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3596): invalid rfc slot id: 10
,W/bt-l2cap( 3596): l2cu_get_conn_role 0
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [50:2e:6c:ac:21:50]: 6, f, 6109
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 80 bytes successfully (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 299
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 299)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/jxcore-log( 3550): 2015-11-30T09:56:18.147Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T09:56:18.590Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:18.594Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:18.606Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:18.616Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:18.625Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T09:56:21.036Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:21.037Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T09:56:26.040Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:26.041Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:26.042Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:26.044Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Nexus 5 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[136]}
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 304)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, LGE-Nexus 5_PT9919
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 304)
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 48416
,I/BtConnectorHelper( 3550): Request socket is using : 48416
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :48416
,I/jxcore-log( 3550): 2015-11-30T09:56:28.480Z SendDataConnector.js: CLIENT connected to 48416, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:56:28.481Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 48416
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T09:56:28.495Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1019): GC_EXPLICIT freed 867K, 65% free 17946K/49968K, paused 4ms+9ms, total 97ms
,D/UdcCache:FPQuery( 1354): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1354): GC_CONCURRENT freed 1977K, 30% free 12135K/17224K, paused 3ms+5ms, total 39ms
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427f8010 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): invalid rfc slot id: 9
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T09:57:09.120Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d36c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED,
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T09:57:18.558Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:18.559Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:57:18.560Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:18.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:57:18.561Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: LGE-Nexus 5_PT9919
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T09:57:23.562Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:23.563Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T09:57:28.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:28.567Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:28.569Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:28.571Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Nexus 5 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[134]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 309)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, LGE-Nexus 5_PT9919
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3550): mHTTPPort  set to : 50591
I/BtConnectorHelper( 3550): Request socket is using : 50591
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :50591
,I/jxcore-log( 3550): 2015-11-30T09:57:29.283Z SendDataConnector.js: CLIENT connected to 50591, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:57:29.285Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 50591
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T09:57:29.301Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{422c7220 type 3 android}
,I/jxcore-log( 3550): 2015-11-30T09:58:19.367Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.368Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.370Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.401Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.401Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.401Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
I/BtConnectorHelper( 3550): Disconnect outgoing peer: 34:FC:EF:11:B1:66
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,I/jxcore-log( 3550): 2015-11-30T09:58:19.407Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): ---- round done--------
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3550): 
I/jxcore-log( 3550): do fake peer & start
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:58:19.410Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:58:19.410Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:19.411Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/jxcore-log( 3550): 2015-11-30T09:58:19.415Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[135]}
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d528 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4747): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 3677): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Tethering( 1019): InitialState.processMessage what=4
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 21
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 415404
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6124acb0 clazz=0x64f00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1324): Read error: ssl=0x6297db00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1324): SSL shutdown failed: ssl=0x6297db00: I/O error during system call, Broken pipe
,I/jxcore-log( 3550): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): The Coordinator has disconnected!
I/jxcore-log( 3550): 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,D/WifiService( 1019): setWifiEnabled: false pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): Active network info is not available
W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/wpa_supplicant( 3677): wlan0: Failed to initiate AP scan
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  277): Event received = Failed to initiate AP sc
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3677): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=DISCONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiService( 1019): setWifiEnabled: true pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1019): stopping supplicant
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): setWifiState: disabling
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1263): Active network info is not available
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiController( 1019): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 401ms
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=5038 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): handleMessage: X
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1263): Active network info is not available
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/jxcore-log( 3550): Wifi toggled for connection repairment
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
,I/wpa_supplicant( 3677): eap_proxy Deinitialzed
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 3677): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d6cc78:true
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 3677): CTRL_IFACE monitor[0]: 2 - No such file or directory
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/LocalBluetoothProfileManager( 5038): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 5038): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 5038): Adding local MAP profile
D/BluetoothMap( 5038): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5038): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 5038): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothA2dp( 5038): Proxy object connected
,D/A2dpProfile( 5038): Bluetooth service connected
,I/ActivityManager( 1019): Killing 4527:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
D/BluetoothHeadset( 5038): Proxy object connected
,D/HeadsetProfile( 5038): Bluetooth service connected
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothInputDevice( 5038): Proxy object connected
D/HidProfile( 5038): Bluetooth service connected
D/BluetoothPan( 5038): BluetoothPAN Proxy object connected
D/PanProfile( 5038): Bluetooth service connected
D/BluetoothMap( 5038): Proxy object connected
D/MapProfile( 5038): Bluetooth service connected
D/BluetoothMap( 5038): getConnectedDevices()
D/BluetoothPbap( 5038): Proxy object connected
D/PbapServerProfile( 5038): Bluetooth service connected
,D/WifiStateMachine( 1019): setWifiState: disabled
,D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/Settings( 1215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiService( 1019): New client listening to asynchronous messages
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1019): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/QsoftapCmd(  275): Got softap fwreload command we are passing on
,D/SoftapController(  275): Softap fwReload - Ok
,D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 5089): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 5089): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/Diag_Lib( 5089): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 5089): Setting internal use port to rmnet0
,E/wpa_supplicant( 5089): baseband property is set to [msm]
,E/wpa_supplicant( 5089):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5089): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5089): card_info[i].card_state: 0x2
E/wpa_supplicant( 5089): card_info[i].error_code: 0x3
E/wpa_supplicant( 5089): SIM/USIM not ready
,E/wpa_supplicant( 5089): Error while reading SIM card status
,E/wpa_supplicant( 5089): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5089): card_info[i].card_state: 0x2
E/wpa_supplicant( 5089): card_info[i].error_code: 0x3
E/wpa_supplicant( 5089): SIM/USIM not ready
,I/wpa_supplicant( 5089): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): setWifiState: enabling
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1263): Active network info is not available
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1,
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
,E/MDMCTBK (  277): Attach monitor thread
,I/wpa_supplicant( 5089): Long line in configuration file truncated
,I/wpa_supplicant( 5089): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/wpa_supplicant( 5089): COUNTRY Code Recived
,E/wpa_supplicant( 5089): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 5089): baseband property is set to [msm]
,E/wpa_supplicant( 5089):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5089): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5089): card_info[i].card_state: 0x2
E/wpa_supplicant( 5089): card_info[i].error_code: 0x3
E/wpa_supplicant( 5089): SIM/USIM not ready
,E/wpa_supplicant( 5089): Error while reading SIM card status
,E/wpa_supplicant( 5089): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5089): card_info[i].card_state: 0x2
E/wpa_supplicant( 5089): card_info[i].error_code: 0x3
E/wpa_supplicant( 5089): SIM/USIM not ready
,I/wpa_supplicant( 5089): eap_proxy: Card not ready
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
I/MDMCTBK (  277): createWifiMonitorThread: Started the wifi monitor thread -1205226456
,D/MDMCTBK (  277): wifi_wait_on_socket: Enter monitor thread
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1263): Active network info is not available
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 5089): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 5089): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 5089): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
D/MDMCTBK (  277): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set country code PL
,E/wpa_supplicant( 5089): COUNTRY Code Recived
,E/wpa_supplicant( 5089): COUNTRY Code Recived
D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring up p2p0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set frequency band 2
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-6ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnablingState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
,D/WifiP2pService( 1019): P2pEnabledState
D/MDMCTBK (  277): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 2
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-12m49s871ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-12m49s871ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5089): COUNTRY Code Recived
E/wpa_supplicant( 5089): COUNTRY Code Recived
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5113 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+11ms, total 46ms
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1530): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1530): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
W/XTWiFiOS( 1263): Active network info is not available
D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1530): [debug] > CusSM.onRadioDown
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/dalvikvm( 5113): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fa7d58, skipping init
I/openssl ( 5113): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5113): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5145 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4542:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 5145): mnc/mcc: 
V/MmsConfig( 5145): tag: bool value: enabledMMS - true
,V/MmsConfig( 5145): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5145): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5145): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5145): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5145): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 5145): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5145): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 5145): tag: int value: recipientLimit - 20
V/MmsConfig( 5145): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5145): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5145): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5145): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5145): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5145): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 5145): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5145): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5145): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5164 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4646:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5164): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 5164): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5164): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5177 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4417:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5193 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4576:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 5193): Binding Chromium to main looper Looper (main, tid 1) {41f99ab0}
,I/LibraryLoader( 5193): Expected native library version number "",actual native library version number ""
,I/chromium( 5193): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5193): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5193): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5193): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5193): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5193): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5193): Local Branch: 
I/Adreno-EGL( 5193): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5193): Local Patches: NONE
I/Adreno-EGL( 5193): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5193): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5193): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5193): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/dalvikvm( 1019): GC_EXPLICIT freed 1359K, 64% free 18017K/49968K, paused 4ms+9ms, total 94ms
,I/NSApplication( 5193): Starting up...
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5235 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4702:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5252 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/ImageResourceManager( 5235): ImageResourceManager: uninitalized
,I/iu.Environment( 5235): update battery state; isPlugged? true*
,I/iu.Environment( 5235): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 5235): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1019): Killing 4747:com.motorola.context/u0a11 (adj 15): empty #9
I/ActivityManager( 1019): Killing 4763:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #10
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1354): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1354): num queued entries: 0
,I/iu.UploadsManager( 1354): num updated entries: 0
,I/iu.SyncManager( 1354): NEXT; no task
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1530): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1530): bindWebServices(): registering our AIDL callback...
I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1530): onServiceConnected()
D/GetNotificationsWS( 1530): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 5164): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5164): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 5235): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 5235): GC_FOR_ALLOC freed 380K, 5% free 16399K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 5235): Grow heap (frag case) to 19.784MB for 1821008-byte allocation
,I/iu.UploadsManager( 5235): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 5235): GC_FOR_ALLOC freed 15K, 5% free 18184K/19004K, paused 11ms, total 11ms
,I/iu.FingerprintManager( 5235): Start processing all media
,I/iu.FingerprintManager( 5235): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5235): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 5235): End new media; added: 0, uploading: 0, time: 60 ms
,I/iu.FingerprintManager( 5235): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5235): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5235): Finished generating fingerprints; 0.013 seconds
,I/iu.FingerprintManager( 5235):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 5252): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5088): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 5088): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42112e30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@42112e30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@42112e30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/GAV2    ( 5193): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,E/bt-btif ( 3596): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:14, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 3550): 2015-11-30T09:58:49.437Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:49.439Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:49.441Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,W/jxcore-log( 3550): $$jxcore_callback_16 wasn't registered
W/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): 2015-11-30T09:58:54.472Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:54.473Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x22  CID 0x4a
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3596): invalid rfc slot id: 14
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): 2015-11-30T09:58:59.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:59.506Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:59.507Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:58:59.509Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[132]}
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1019): sending alarm Alarm{429144d0 type 3 android}
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3596): invalid rfc slot id: 15
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,I/jxcore-log( 3550): 2015-11-30T09:59:04.701Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:04.703Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:04.704Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=5296 uid=10011 gids={50011, 3003, 3002, 3001}
W/BluetoothEventManager( 5038): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5038): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4213f358:true
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=5308 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1019): Killing 5038:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
D/WifiService( 1019): Client connection lost with reason: 4
,I/ActivityManager( 1019): Killing 5252:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/bt-btif ( 3596): services_to_search = 3fffffff
E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 315
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T09:59:08.072Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 34:FC:EF:9D:93:0B
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T09:59:09.362Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.371Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.381Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.389Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.395Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.399Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.408Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.440Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.452Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.490Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.502Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.512Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.550Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.558Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.564Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.600Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.610Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.651Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.659Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.690Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.707Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.715Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.715Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:09.741Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T09:59:14.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:14.739Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:14.741Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:14.742Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[140]}
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1019): sending alarm Alarm{429145a8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d8a0 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,D/WifiService( 1019): setWifiEnabled: false pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1263): Active network info is not available
W/wpa_supplicant( 5089): wlan0: Failed to initiate AP scan
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  277): Event received = Failed to initiate AP sc
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=DISCONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): stopping supplicant
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): setWifiState: disabling
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=5357 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/wpa_supplicant( 5089): eap_proxy Deinitialzed
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiService( 1019): setWifiEnabled: true pid=3550, uid=10417
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController( 1019): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 379ms
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5089): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): Supplicant connection lost
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): Active network info is not available
I/jxcore-log( 3550): Wifi toggled for connection repairment
I/jxcore-log( 3550): 
I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420d0370:true
,D/LocalBluetoothProfileManager( 5357): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 5357): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 5357): Adding local MAP profile
D/BluetoothMap( 5357): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5357): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 5357): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothA2dp( 5357): Proxy object connected
,I/ActivityManager( 1019): Killing 5145:com.android.mms/u0a30 (adj 15): empty #9
,D/A2dpProfile( 5357): Bluetooth service connected
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothHeadset( 5357): Proxy object connected
D/HeadsetProfile( 5357): Bluetooth service connected
D/BluetoothInputDevice( 5357): Proxy object connected
D/HidProfile( 5357): Bluetooth service connected
D/BluetoothPan( 5357): BluetoothPAN Proxy object connected
D/PanProfile( 5357): Bluetooth service connected
D/BluetoothMap( 5357): Proxy object connected
D/MapProfile( 5357): Bluetooth service connected
D/BluetoothMap( 5357): getConnectedDevices()
D/BluetoothPbap( 5357): Proxy object connected
D/PbapServerProfile( 5357): Bluetooth service connected
,D/WifiStateMachine( 1019): setWifiState: disabled
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
,W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/Settings( 1215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiService( 1019): New client listening to asynchronous messages
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1019): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X,
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0,
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully,
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1019): InitialState.processMessage what=4
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/QsoftapCmd(  275): Got softap fwreload command we are passing on
,D/SoftapController(  275): Softap fwReload - Ok
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
E/MDMCTBK (  277): Unable to open cntrl connection to supplicant on "@android:wpa_wlan0": No such file or directory
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  277): wifi_close_sockets: Exit
D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 5416): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 5416): rfkill: Cannot open RFKILL control device
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/Diag_Lib( 5416): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 5416): Setting internal use port to rmnet0
,E/wpa_supplicant( 5416): baseband property is set to [msm]
,E/wpa_supplicant( 5416):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5416): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5416): card_info[i].card_state: 0x2
E/wpa_supplicant( 5416): card_info[i].error_code: 0x3
E/wpa_supplicant( 5416): SIM/USIM not ready
,E/wpa_supplicant( 5416): Error while reading SIM card status
,E/wpa_supplicant( 5416): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5416): card_info[i].card_state: 0x2
E/wpa_supplicant( 5416): card_info[i].error_code: 0x3
E/wpa_supplicant( 5416): SIM/USIM not ready
,I/wpa_supplicant( 5416): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): setWifiState: enabling
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,I/wpa_supplicant( 5416): Long line in configuration file truncated
,I/wpa_supplicant( 5416): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/wpa_supplicant( 5416): COUNTRY Code Recived
,E/wpa_supplicant( 5416): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 5416): baseband property is set to [msm]
,E/wpa_supplicant( 5416):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5416): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5416): card_info[i].card_state: 0x2
E/wpa_supplicant( 5416): card_info[i].error_code: 0x3
E/wpa_supplicant( 5416): SIM/USIM not ready
,E/wpa_supplicant( 5416): Error while reading SIM card status
E/wpa_supplicant( 5416): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5416): card_info[i].card_state: 0x2
E/wpa_supplicant( 5416): card_info[i].error_code: 0x3
E/wpa_supplicant( 5416): SIM/USIM not ready
,I/wpa_supplicant( 5416): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
,D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,W/XTWiFiOS( 1263): Active network info is not available
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 5416): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 5416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 5416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/CommandListener(  275): Setting iface cfg
D/CommandListener(  275): Trying to bring up p2p0
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 2
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set country code PL
E/wpa_supplicant( 5416): COUNTRY Code Recived
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
E/wpa_supplicant( 5416): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
,D/WifiP2pService( 1019): MCC mode enabled 0
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
,D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-17ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-17ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5416): COUNTRY Code Recived
,E/wpa_supplicant( 5416): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5415): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 5415): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43cb84a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43cb84a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@43cb84a0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,E/bt-btif ( 3596): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:17, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 3550): 2015-11-30T09:59:44.770Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T09:59:44.770Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:44.771Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,W/jxcore-log( 3550): $$jxcore_callback_22 wasn't registered
W/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3596): invalid rfc slot id: 17
,I/jxcore-log( 3550): 2015-11-30T09:59:49.786Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:49.787Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): 2015-11-30T09:59:54.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:54.804Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:54.806Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T09:59:54.807Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[141]}
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,W/bt-btif ( 3596): invalid rfc slot id: 11
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt socket
,V/AlarmManager( 1019): sending alarm Alarm{42525698 type 3 android}
,I/jxcore-log( 3550): 2015-11-30T10:00:00.019Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1019): sending alarm Alarm{42914680 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5426 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 5164:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,E/bt-btif ( 3596): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:18, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 3550): 2015-11-30T10:00:24.835Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:24.837Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:24.839Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,W/jxcore-log( 3550): $$jxcore_callback_26 wasn't registered
W/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x22  CID 0x46
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3596): invalid rfc slot id: 18
,W/bt-l2cap( 3596): l2cu_get_conn_role 0
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 321
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/jxcore-log( 3550): 2015-11-30T10:00:27.769Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 34:FC:EF:9D:93:0B
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T10:00:28.163Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:28.167Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:28.206Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:28.214Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): 2015-11-30T10:00:29.857Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:29.858Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T10:00:34.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:34.877Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:34.880Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:00:34.881Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[143]}
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,D/WifiService( 1019): setWifiEnabled: false pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): Active network info is not available
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/wpa_supplicant( 5416): wlan0: Failed to initiate AP scan
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): stopping supplicant
,D/WifiStateMachine( 1019): setWifiState: disabling
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,I/wpa_supplicant( 5416): eap_proxy Deinitialzed
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiService( 1019): setWifiEnabled: true pid=3550, uid=10417
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController( 1019): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 369ms
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/jxcore-log( 3550): Wifi toggled for connection repairment
I/jxcore-log( 3550): 
W/XTWiFiOS( 1263): Active network info is not available
W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5416): wlan0: CTRL-EVENT-TERMINATING 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/WifiStateMachine( 1019): setWifiState: disabled
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/Settings( 1215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1019): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/QsoftapCmd(  275): Got softap fwreload command we are passing on
,D/SoftapController(  275): Softap fwReload - Ok
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1019): setWifiState: enabling
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1,
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
,E/MDMCTBK (  277): Attach monitor thread
,I/wpa_supplicant( 5515): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 5515): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/Diag_Lib( 5515): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 5515): Setting internal use port to rmnet0
,E/wpa_supplicant( 5515): baseband property is set to [msm]
,E/wpa_supplicant( 5515):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): card_info[i].card_state: 0x2
E/wpa_supplicant( 5515): card_info[i].error_code: 0x3
E/wpa_supplicant( 5515): SIM/USIM not ready
,E/wpa_supplicant( 5515): Error while reading SIM card status
,E/wpa_supplicant( 5515): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): card_info[i].card_state: 0x2
E/wpa_supplicant( 5515): card_info[i].error_code: 0x3
E/wpa_supplicant( 5515): SIM/USIM not ready
,I/wpa_supplicant( 5515): eap_proxy: Card not ready
,I/wpa_supplicant( 5515): Long line in configuration file truncated
,I/wpa_supplicant( 5515): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/wpa_supplicant( 5515): COUNTRY Code Recived
E/wpa_supplicant( 5515): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 5515): baseband property is set to [msm]
,E/wpa_supplicant( 5515):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): card_info[i].card_state: 0x2
E/wpa_supplicant( 5515): card_info[i].error_code: 0x3
E/wpa_supplicant( 5515): SIM/USIM not ready
,E/wpa_supplicant( 5515): Error while reading SIM card status
E/wpa_supplicant( 5515): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5515): card_info[i].card_state: 0x2
E/wpa_supplicant( 5515): card_info[i].error_code: 0x3
E/wpa_supplicant( 5515): SIM/USIM not ready
,I/wpa_supplicant( 5515): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
I/MDMCTBK (  277): createWifiMonitorThread: Started the wifi monitor thread -1205226456
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/MDMCTBK (  277): wifi_wait_on_socket: Enter monitor thread
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState,
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 5515): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 5515): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 5515): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
D/MDMCTBK (  277): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set country code PL
,E/wpa_supplicant( 5515): COUNTRY Code Recived
E/wpa_supplicant( 5515): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set frequency band 2
D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring up p2p0
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-10ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnablingState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/MDMCTBK (  277): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-14m51s768ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-14m51s768ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5515): COUNTRY Code Recived
E/wpa_supplicant( 5515): COUNTRY Code Recived
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5514): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 5514): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@429478f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@429478f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@429478f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143366 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143366 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-4ms what=143366 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{44600808 type 3 android}
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): cancel: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,E/bt-btif ( 3596): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:20, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 3550): 2015-11-30T10:01:04.909Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.910Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.929Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.930Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ---- round done--------
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3550): 
I/jxcore-log( 3550): do fake peer & start
I/jxcore-log( 3550): 
I/jxcore-log( 3550): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:01:04.932Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:01:04.932Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.933Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 2015-11-30T10:01:04.937Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.938Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:04.939Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:2, scn:481138784
,W/bt-btif ( 3596): invalid rfc slot id: 21
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[144]}
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): shutdown
W/jxcore-log( 3550): $$jxcore_callback_32 wasn't registered
W/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 3596): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
,E/bt-btif ( 3596): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3596): invalid rfc slot id: 20
,I/jxcore-log( 3550): 2015-11-30T10:01:09.955Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:09.956Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 83 bytes successfully (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 327
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 327)
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/jxcore-log( 3550): 2015-11-30T10:01:10.728Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 7C:F9:0E:37:96:AB
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): 2015-11-30T10:01:11.460Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.467Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.474Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.485Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.492Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.497Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.507Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.541Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.551Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.584Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.592Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.594Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.629Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.646Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.682Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.691Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.722Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.733Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.770Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.780Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.787Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:11.820Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3550): 
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): 2015-11-30T10:01:14.976Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:14.976Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:14.980Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:14.982Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[148]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 332)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-N910C_PT7847
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 39861
I/BtConnectorHelper( 3550): Request socket is using : 39861
,I/BtToRequestSocket( 3550): Now accepting connections
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: E0:DB:10:14:E2:C0
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,D/BluetoothMetrics( 3596): btclass1f00
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :39861
,I/jxcore-log( 3550): 2015-11-30T10:01:17.575Z SendDataConnector.js: CLIENT connected to 39861, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:17.577Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 39861
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:01:17.594Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,I/jxcore-log( 3550): 2015-11-30T10:01:18.201Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): invalid rfc slot id: 16
,I/jxcore-log( 3550): 2015-11-30T10:01:18.280Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:01:18.310Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.364Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.409Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.500Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.579Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.638Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:18.744Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T10:01:18.822Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3550): 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 336
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/jxcore-log( 3550): 2015-11-30T10:01:30.783Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 34:FC:EF:9D:93:0B
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,W/BluetoothEventManager( 5357): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,I/CE-BTReceiver( 5296): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/BluetoothEventManager( 5357): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:31.300Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): 2015-11-30T10:01:31.314Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:31.360Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:31.364Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:31.367Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:01:31.374Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,D/WifiService( 1019): setWifiEnabled: false pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1263): Active network info is not available
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/wpa_supplicant( 5515): wlan0: Failed to initiate AP scan
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
D/MDMCTBK (  277): Event received = Failed to initiate AP sc
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=DISCONNECTED
,D/WifiService( 1019): setWifiEnabled: true pid=3550, uid=10417
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiController( 1019): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 430ms
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): Active network info is not available
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1019): stopping supplicant
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): setWifiState: disabling
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/wpa_supplicant( 5515): eap_proxy Deinitialzed
,W/XTWiFiOS( 1263): Active network info is not available
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): Wifi toggled for connection repairment
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5515): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  277): wifi_close_sockets: Exit
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/WifiStateMachine( 1019): setWifiState: disabled
,D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,W/Settings( 1215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1019): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/QsoftapCmd(  275): Got softap fwreload command we are passing on
,D/SoftapController(  275): Softap fwReload - Ok
D/CommandListener(  275): Setting iface cfg
,D/CommandListener(  275): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1019): setWifiState: enabling
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,W/XTWiFiOS( 1263): Active network info is not available
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,I/wpa_supplicant( 5648): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 5648): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,E/Diag_Lib( 5648): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 5648): Setting internal use port to rmnet0
,E/wpa_supplicant( 5648): baseband property is set to [msm]
,E/wpa_supplicant( 5648):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): card_info[i].card_state: 0x2
E/wpa_supplicant( 5648): card_info[i].error_code: 0x3
E/wpa_supplicant( 5648): SIM/USIM not ready
,E/wpa_supplicant( 5648): Error while reading SIM card status
,E/wpa_supplicant( 5648): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): card_info[i].card_state: 0x2
E/wpa_supplicant( 5648): card_info[i].error_code: 0x3
E/wpa_supplicant( 5648): SIM/USIM not ready
,I/wpa_supplicant( 5648): eap_proxy: Card not ready
,I/wpa_supplicant( 5648): Long line in configuration file truncated
,I/wpa_supplicant( 5648): rfkill: Cannot open RFKILL control device
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
E/wpa_supplicant( 5648): COUNTRY Code Recived
,E/wpa_supplicant( 5648): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 5648): baseband property is set to [msm]
,E/wpa_supplicant( 5648):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): card_info[i].card_state: 0x2
E/wpa_supplicant( 5648): card_info[i].error_code: 0x3
E/wpa_supplicant( 5648): SIM/USIM not ready
,E/wpa_supplicant( 5648): Error while reading SIM card status
E/wpa_supplicant( 5648): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5648): card_info[i].card_state: 0x2
E/wpa_supplicant( 5648): card_info[i].error_code: 0x3
E/wpa_supplicant( 5648): SIM/USIM not ready
,I/wpa_supplicant( 5648): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
,D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): Active network info is not available
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 5648): COUNTRY Code Recived -COUNTRY PL
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 5648): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 5648): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/CommandListener(  275): Setting iface cfg
D/CommandListener(  275): Trying to bring up p2p0
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiP2pService( 1019): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/WifiStateMachine( 1019): set country code PL
E/wpa_supplicant( 5648): COUNTRY Code Recived
E/wpa_supplicant( 5648): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
,D/WifiP2pService( 1019): MCC mode enabled 0
I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
E/MDMCTBK (  277): Attach monitor thread
I/MDMCTBK (  277): createWifiMonitorThread: Started the wifi monitor thread -1205226456
,D/MDMCTBK (  277): wifi_wait_on_socket: Enter monitor thread
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-25ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-25ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-26ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-26ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 5648): COUNTRY Code Recived
,E/wpa_supplicant( 5648): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-12ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-12ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1019): GC_CONCURRENT freed 2104K, 64% free 18116K/49968K, paused 5ms+9ms, total 98ms
,W/bt-btif ( 3596): dm_pm_timer expires
W/bt-btif ( 3596): dm_pm_timer expires 1
W/bt-btif ( 3596): dm_pm_timer expires
W/bt-btif ( 3596): dm_pm_timer expires 0
W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): proc dm_pm_timer expires
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5647): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 5647): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43c6acf0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@43c6acf0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@43c6acf0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143366 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143366 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-4ms what=143366 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 5648): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  277): Event received = Trying to associate with,
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,E/wpa_supplicant( 5648): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 5648): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 5648): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  499): NL - Read 312 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 192 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5648): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request,
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5648): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 5648): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205230792
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-42ms what=147462 obj=android.net.wifi.StateChangeResult@421fca30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-37ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@421fe3e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427a6590 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427a6590 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 20
,D/TCMD    (  499): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42077868
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/SBar.NetworkController( 1085): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42077868
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3550): DBG, CoordinatorConnector connect called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): Coordinator is now connected to the server!
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1530): now: 973472 ,futureTime: 21956955
,D/PollingManager( 1530): Polling alarm set to expire at: 21956955 Current Time: 973472
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1530): [debug] > CusSM.onRadioUp
D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1530): now: 973515 ,futureTime: 21956955
,D/PollingManager( 1530): Polling alarm set to expire at: 21956955 Current Time: 973515
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
I/openssl ( 5113): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 5113): Crypto mode 0 already enabled
D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5745 uid=10030 gids={50030, 3003, 1028, 1015}
D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1530): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1530): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,V/MmsConfig( 5745): mnc/mcc: 
D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
V/MmsConfig( 5745): tag: bool value: enabledMMS - true
V/MmsConfig( 5745): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5745): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5745): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5745): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5745): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 5745): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5745): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 5745): tag: int value: recipientLimit - 20
V/MmsConfig( 5745): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5745): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5745): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5745): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 5745): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5745): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 5745): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5745): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5745): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/TelephonyProvider( 1251): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5770 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 5177:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5770): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5770): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5770): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5784 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5193:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1354): Checkin interval check for package: unspecified last checkin: 1448877106315 min interval config: 0 actual interval: 613322
,I/CheckinService( 1354): Checking schedule, now: 1448877719643 next: 1448877136291
,I/CheckinService( 1354): active receiver: enabled
,I/CheckinService( 1354): Preparing to send checkin request
,I/EventLogService( 1354): Accumulating logs since 1448877101330
,I/CheckinRequestBuilder( 1354): Checkin reason type: 8 attempt count: 1
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5798 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5235:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/ActivityThread( 1354): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 5798): Binding Chromium to main looper Looper (main, tid 1) {41f98b88}
,I/LibraryLoader( 5798): Expected native library version number "",actual native library version number ""
,I/chromium( 5798): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5798): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5798): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5798): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5798): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5798): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5798): Local Branch: 
I/Adreno-EGL( 5798): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5798): Local Patches: NONE
I/Adreno-EGL( 5798): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5823 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/chromium( 5798): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 5823): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5823): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5823): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5823): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 5823): VFY: replacing opcode 0x6e at 0x00ca
,W/GAV2    ( 5798): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  264): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  264): Returning OperationFailed - no handler for errno 30
I/MultiDex( 5823): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5823): install
W/ContextImpl( 5798): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/MultiDex( 5823): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5823): loading existing secondary dex files
,I/MultiDex( 5823): load found 3 secondary dex files
,I/MultiDex( 5823): install done
,D/dalvikvm( 5823): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5823): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5823): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5823): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5823): VFY: unable to resolve instance field 46
,D/dalvikvm( 5823): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5823): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5823): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5823): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5823): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5823): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5823): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9ec70
D/dalvikvm( 5823): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9ec70
,D/dalvikvm( 5823): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9ec70, skipping init
,D/dalvikvm( 5823): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9ec70
D/dalvikvm( 5823): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9ec70
,V/JNIHelp ( 5823): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 5823): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9ec70
,D/dalvikvm( 5823): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f9ec70
D/dalvikvm( 5823): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9ec70
,D/dalvikvm( 5823): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f9ec70
,V/AlarmManager( 1019): sending alarm Alarm{427dd018 type 3 android}
,I/NSApplication( 5798): Starting up...
,I/ProviderInstaller( 5823): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5854 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 5426:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 5823): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5823): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5823): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5823): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5823): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5823): VFY: replacing opcode 0x6e at 0x0220
,I/dalvikvm( 5823): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5823): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 5823): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 5823): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 5823): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5823): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 5823): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5823): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5823): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 5823): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 5823): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/ImageResourceManager( 5854): ImageResourceManager: uninitalized
I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5877 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/iu.Environment( 5854): update battery state; isPlugged? true*
,I/iu.Environment( 5854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,I/iu.Environment( 5854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 1019): Killing 5308:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
I/ActivityManager( 1019): Killing 5296:com.motorola.context/u0a11 (adj 15): empty #10
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53b6000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53b6000
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,I/iu.Environment( 1354): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/iu.UploadsManager( 1354): num queued entries: 0
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1530): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
,D/GetNotificationsWS( 1530): bindWebServices(): registering our AIDL callback...
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=1486417872
D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1530): onServiceConnected()
,D/GetNotificationsWS( 1530): onServiceConnected(): Registered for remote service callbacks...
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
I/iu.UploadsManager( 1354): num updated entries: 0
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
,I/iu.SyncManager( 1354): NEXT; no task
I/openssl ( 5113): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5113): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 5770): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5770): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 5854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1530): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1530): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1530): onServiceConnected()
,D/GetNotificationsWS( 1530): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{41f90aa8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,E/MDM     ( 1215): [91] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/dalvikvm( 5823): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217d830
D/dalvikvm( 5823): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217d830
,D/dalvikvm( 5823): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4217d830, skipping init
,D/GCM     ( 1324): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1324): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1324): Proximity feature is not enabled.
,D/LocationInitializer( 1354): Restart initialization of location
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,V/GLSActivity( 1324): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/iu.UploadsManager( 5854): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/NativeLibraryUtils( 5823): Install completed successfully. count=13 extracted=0
,D/dalvikvm( 1019): GC_EXPLICIT freed 1360K, 64% free 18039K/49968K, paused 5ms+9ms, total 95ms
,V/GmsCoreStatsServiceLauncher( 1354): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/dalvikvm( 5854): GC_FOR_ALLOC freed 391K, 5% free 16406K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 5854): Grow heap (frag case) to 19.791MB for 1821008-byte allocation
,I/GCM     ( 1324): Ack for not saved message 20
,W/GCoreFlp( 1215): No location to return for getLastLocation()
,W/FusedLocationProvider( 1324): location=null
,I/ContactLocale( 5877): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/iu.UploadsManager( 5854): End new media; added: 0, uploading: 0, time: 177 ms
,D/dalvikvm( 5854): GC_FOR_ALLOC freed 16K, 5% free 18183K/19004K, paused 26ms, total 26ms
,I/iu.FingerprintManager( 5854): Start processing all media
,I/iu.FingerprintManager( 5854): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5854): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5854): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5854): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5854): Finished generating fingerprints; 0.023 seconds
,I/iu.FingerprintManager( 5854):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=332475694
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1085): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1085): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1085): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1273): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1273): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5823): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5920): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5823): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5823): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 93ms
,I/Adreno-EGL( 5823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5823): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5823): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5823): Local Branch: 
I/Adreno-EGL( 5823): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5823): Local Patches: NONE
I/Adreno-EGL( 5823): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5823): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5823): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5823): Local Branch: 
I/Adreno-EGL( 5823): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5823): Local Patches: NONE
I/Adreno-EGL( 5823): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5823): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5823): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5823): Local Branch: 
I/Adreno-EGL( 5823): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5823): Local Patches: NONE
I/Adreno-EGL( 5823): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5823): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5823): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5823): Local Branch: 
I/Adreno-EGL( 5823): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5823): Local Patches: NONE
I/Adreno-EGL( 5823): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5823): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,V/NativeCrypto( 1354): SSL shutdown failed: ssl=0x6a91b9e0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1354): SSL shutdown failed: ssl=0x6a8cc9d0: I/O error during system call, Connection timed out
,W/bt-btif ( 3596): invalid rfc slot id: 19
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:02:02.107Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,I/CheckinTask( 1354): Sending checkin request (11608 bytes)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/CheckinRequestBuilder( 1354): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1354): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,I/CheckinTask( 1354): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1354): Checking schedule, now: 1448877723130 next: 1449470793122
,I/CheckinService( 1354): active receiver: disabled
,D/CheckinService( 1354): Recording last checkin time for package unspecified as 1448877723144
,D/GCM     ( 1324): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x41
,I/GAV2    ( 5798): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1019): Killing 5357:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=5949 uid=10011 gids={50011, 3003, 3002, 3001}
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4201e618:true
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
I/ActivityManager( 1019): Killing 5877:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T10:02:08.822Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:08.823Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:08.830Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:08.831Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:08.833Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-N910C_PT7847
,I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5974 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/dalvikvm( 1324): GC_EXPLICIT freed 1530K, 37% free 10941K/17224K, paused 3ms+5ms, total 36ms
,V/GmsNetworkLocationProvi( 1215): DISABLE
,I/GCoreNlp( 1215): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 5974): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5974): MmsConfig.loadMmsSettings
I/Babel   ( 5974): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5974): MmsConfig.loadFromDatabase
,E/Babel   ( 5974): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5974): MmsConfig.loadFromResources
,E/Babel   ( 5974): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5974): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 5974): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6010 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/ActivityManager( 1019): Killing 5113:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6030 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5745:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2172): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1354): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6049 uid=10038 gids={50038, 3003, 1028, 1015}
,I/PackageBroadcastService( 1354): Null package name or gms related package.  Ignoreing.
,D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm( 5854): GC_FOR_ALLOC freed 48K, 3% free 20713K/21204K, paused 32ms, total 32ms
I/ActivityManager( 1019): Killing 5770:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/Icing   ( 1354): updateResources: need to parse f{com.google.android.gms}
,I/dalvikvm( 6049): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 6049): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x000e
,I/ContactLocale( 6010): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 6049): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 6049): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 6049): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x01d3
,D/dalvikvm( 1354): GC_CONCURRENT freed 1987K, 30% free 12157K/17224K, paused 4ms+4ms, total 53ms
,I/dalvikvm( 6049): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 6049): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2172): UpdateCorporaTask done [took 255 ms] updated apps [took 255 ms] 
,D/Finsky  ( 6049): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 6049): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 6049): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 6049): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6049): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 6049): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6049): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 6049): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6049): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 6049): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 6049): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x0385
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6085 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 6049): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 6049): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm( 1019): GC_EXPLICIT freed 1420K, 64% free 18087K/49968K, paused 3ms+10ms, total 90ms
,D/Ads     ( 6049): Skipping gmscore version check
,D/Finsky  ( 6049): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6049): [1] Libraries$2.run: Finished loading 1 libraries.
,D/dalvikvm( 6085): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f9d568, skipping init
I/openssl ( 6085): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 6085): Crypto mode 0 already enabled
I/dalvikvm( 6049): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 6049): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 6049): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1019): Killing 5784:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 5798:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 6049): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6049): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/jxcore-log( 3550): 2015-11-30T10:02:13.834Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:13.834Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 83 bytes successfully (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 340
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 340)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T10:02:15.828Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:16.270Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:16.277Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:16.283Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:16.288Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:16.293Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T10:02:18.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:18.840Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:18.841Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:18.843Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Note4-1 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[150]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 345)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-N910C_PT7847
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 37131
,I/BtConnectorHelper( 3550): Request socket is using : 37131
,I/BtToRequestSocket( 3550): Now accepting connections
,W/bt-btif ( 3596): invalid rfc slot id: 22
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:02:21.647Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :37131
,I/jxcore-log( 3550): 2015-11-30T10:02:21.875Z SendDataConnector.js: CLIENT connected to 37131, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:21.877Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 37131
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:02:21.891Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 22675 ms ago
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=6189 uid=10016 gids={50016, 3002}
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,I/ActivityManager( 1019): Killing 5823:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 349
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 349)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/jxcore-log( 3550): 2015-11-30T10:02:33.431Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 34:FC:EF:9D:93:0B
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,D/BluetoothMetrics( 3596): btclass5a020c
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T10:02:33.834Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:33.849Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T10:02:33.877Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:02:33.881Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3596): bta_dm_pm_btm_status  hci_status=42
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427dfbf8 type 3 android}
,W/bt-btif ( 3596): invalid rfc slot id: 24
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:03:06.621Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:03:11.964Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:11.965Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:11.967Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:11.969Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:11.971Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-N910C_PT7847
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:03:16.972Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:16.974Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 353)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 83 bytes successfully (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 353
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/jxcore-log( 3550): 2015-11-30T10:03:19.254Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T10:03:19.666Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:19.682Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:19.690Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:19.695Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:19.701Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:19.732Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T10:03:21.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:21.981Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:21.983Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:21.984Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Note4-1 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[153]}
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3596): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 358)
,W/bt-btif ( 3596): invalid rfc slot id: 25
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 3550): Close bt socket
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:03:24.653Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-N910C_PT7847
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 45248
I/BtConnectorHelper( 3550): Request socket is using : 45248
,I/BtToRequestSocket( 3550): Now accepting connections
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x4a
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :45248
,I/jxcore-log( 3550): 2015-11-30T10:03:25.038Z SendDataConnector.js: CLIENT connected to 45248, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:03:25.040Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 45248
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:03:25.053Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28d8a0 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4208f640 type 3 android}
,W/bt-btif ( 3596): invalid rfc slot id: 27
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:04:10.121Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:04:15.123Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:15.124Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:15.126Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:15.128Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:15.130Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-N910C_PT7847
,I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:04:20.131Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:20.131Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,W/bt-l2cap( 3596): l2cu_get_conn_role 1
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [7c:f9:0e:37:96:ab]: 6, f, 4106
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 83 bytes successfully (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 362
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 362)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/jxcore-log( 3550): 2015-11-30T10:04:21.097Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T10:04:21.493Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:21.500Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:21.504Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:21.511Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3550): 2015-11-30T10:04:25.136Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:25.136Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:25.138Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:25.139Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: Note4-1 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[155]}
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3596): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 367)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28dc18 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT7847 E0:DB:10:14:E2:C0]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-N910C_PT7847
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 39447
,I/BtConnectorHelper( 3550): Request socket is using : 39447
,I/BtToRequestSocket( 3550): Now accepting connections
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :39447
,I/jxcore-log( 3550): 2015-11-30T10:04:28.580Z SendDataConnector.js: CLIENT connected to 39447, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:04:28.582Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 39447
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:04:28.596Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
W/bt-btif ( 3596): dm_pm_timer expires
W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427fb3a8 type 3 android}
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): invalid rfc slot id: 28
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:05:11.548Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:05:18.657Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.658Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.661Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.680Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.680Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.681Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
I/BtConnectorHelper( 3550): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
I/BtToRequestSocket( 3550): Close server socket
,I/jxcore-log( 3550): 2015-11-30T10:05:18.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ---- round done--------
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): do fake peer & start
I/jxcore-log( 3550): 
I/jxcore-log( 3550): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:05:18.688Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:18.688Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:05:18.688Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: null 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
,I/jxcore-log( 3550): 2015-11-30T10:05:18.693Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[149]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 372)
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-G800F_PT4434
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3550): mHTTPPort  set to : 33829
,I/BtConnectorHelper( 3550): Request socket is using : 33829
,I/BtToRequestSocket( 3550): Now accepting connections
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb,
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 00:F4:6F:30:E0:6C
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass1f00
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :33829
,I/jxcore-log( 3550): 2015-11-30T10:05:21.766Z SendDataConnector.js: CLIENT connected to 33829, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:21.766Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 33829
,I/BtToRequestSocket( 3550): Set local streams
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,I/jxcore-log( 3550): 2015-11-30T10:05:21.778Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [7c:f9:0e:37:96:ab]: 7, f, 2205
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:05:22.674Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:22.953Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T10:05:23.277Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 376)
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=1
W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,D/dalvikvm( 3596): GC_EXPLICIT freed 2141K, 45% free 9556K/17224K, paused 3ms+5ms, total 46ms
,I/jxcore-log( 3550): 2015-11-30T10:05:24.017Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:24.376Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28da5c rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 83 bytes successfully (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 376
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT7897 7C:F9:0E:37:96:AB]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/jxcore-log( 3550): 2015-11-30T10:05:24.664Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T10:05:24.836Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:24.922Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.102Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.219Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.247Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.315Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.402Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.412Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.413Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:05:25.499Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3550): 
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,V/AlarmManager( 1019): sending alarm Alarm{42105328 type 3 android}
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): 2015-11-30T10:06:15.247Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:15.247Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:15.250Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:15.252Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:15.254Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): invalid rfc slot id: 30
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): Stop ReceivingThread
,I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT7897
I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:06:15.614Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x4a
,D/dalvikvm( 2139): GC_CONCURRENT freed 7151K, 43% free 9934K/17224K, paused 15ms+5ms, total 76ms
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T10:06:20.253Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:20.254Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1019): GC_EXPLICIT freed 598K, 64% free 18017K/49968K, paused 4ms+9ms, total 95ms
,I/jxcore-log( 3550): 2015-11-30T10:06:25.259Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:25.260Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:25.261Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:25.263Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-G800F_PT4434
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 55046
,I/BtConnectorHelper( 3550): Request socket is using : 55046
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :55046
,I/jxcore-log( 3550): 2015-11-30T10:06:27.434Z SendDataConnector.js: CLIENT connected to 55046, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:27.435Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 55046
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:06:27.449Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 77 bytes successfully (thread ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT7691 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 385
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7691 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7691 F8:95:C7:87:85:54]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, LGE-LG-D722_PT7691
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BTConnectedThread
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,I/jxcore-log( 3550): 2015-11-30T10:06:48.465Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T10:06:49.387Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T10:06:49.449Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.460Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.463Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.470Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.478Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.485Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.521Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.540Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.549Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.557Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.565Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.600Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.619Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.627Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.639Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.646Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.712Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.750Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.781Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.792Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.795Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.881Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.920Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.934Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.942Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:49.970Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.023Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.026Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.035Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.071Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.081Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.084Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.120Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.152Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.190Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:06:50.199Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): invalid rfc slot id: 33
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT7691
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT7691
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt socket
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:06:50.344Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,V/AlarmManager( 1019): sending alarm Alarm{427986b8 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T10:07:17.522Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:17.523Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:17.525Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:17.527Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:17.530Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service,
V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:07:22.528Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:22.528Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:27.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:27.531Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:27.532Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:27.534Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[156]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-l2cap( 3596): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 390)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 51984
,I/BtConnectorHelper( 3550): Request socket is using : 51984
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :51984
,I/jxcore-log( 3550): 2015-11-30T10:07:29.389Z SendDataConnector.js: CLIENT connected to 51984, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:07:29.391Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 51984
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:07:29.408Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427a2f88 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T10:08:19.477Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:19.477Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:19.481Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:19.482Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:19.484Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3550): 2015-11-30T10:08:24.484Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:24.485Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:08:29.489Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:29.490Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:29.492Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:29.493Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[158]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 395)
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 40464
,I/BtConnectorHelper( 3550): Request socket is using : 40464
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :40464
,I/jxcore-log( 3550): 2015-11-30T10:08:30.549Z SendDataConnector.js: CLIENT connected to 40464, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:08:30.551Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 40464
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:08:30.573Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{422975c8 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): 2015-11-30T10:09:20.632Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:20.632Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:20.634Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:20.636Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:20.638Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3550): 
,I/BtToSocketBase( 3550): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3550): Disconnect outgoing peer: samsung-SM-G800F_PT4434
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3550): 2015-11-30T10:09:25.638Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:25.639Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/jxcore-log( 3550): 2015-11-30T10:09:30.642Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:30.643Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:30.645Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:30.646Z SendDataConnector.js: do connect now
I/jxcore-log( 3550): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Trying to connect...
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3596): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3550): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[160]}
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Outgoing connection initialized (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): onBytesRead: Read 82 bytes successfully (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3550): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT4434 00:F4:6F:30:E0:6C]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : false, samsung-SM-G800F_PT4434
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3550): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 400)
,I/BtToRequestSocket( 3550): mHTTPPort  set to : 51740
I/BtConnectorHelper( 3550): Request socket is using : 51740
,I/BtToRequestSocket( 3550): Now accepting connections
,I/BtConnectorHelper( 3550): Calling ConnectionStatusUpdate with port :51740
,I/jxcore-log( 3550): 2015-11-30T10:09:31.993Z SendDataConnector.js: CLIENT connected to 51740, error: null
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:31.994Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): incoming data from: /127.0.0.1, port: 51740
,I/BtToRequestSocket( 3550): Set local streams
,I/jxcore-log( 3550): 2015-11-30T10:09:32.007Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): rin ended ---------------------------;
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,W/bt-btif ( 3596): info:x10
,D/        ( 3596): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3596): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3596): Entering PendingCommandState State
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3596): services_to_search = 3fffffff
,E/bt-btif ( 3596): ****************search UUID = 1200***********
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): services_to_search = 3ffffffe
,E/bt-btif ( 3596): ****************search UUID = 0100***********
,W/bt-btif ( 3596): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3596): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Incoming connection initialized (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Entering thread (ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesRead: Read 84 bytes successfully (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): onBytesWritten: 81 bytes successfully written (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): removeThreadFromList: Removing thread with ID 404
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Handshake thread disposed (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/BtConnectorHelper( 3550): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3550): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3550): Creating BTConnectedThread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3550): Exiting thread (ID: 404)
I/BtConnectorHelper( 3550): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3550): --DoOneRunRound started
,I/jxcore-log( 3550): 2015-11-30T10:09:41.520Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3550): 
,I/BtToRequestSocket( 3550): LocalHost address: localhost/127.0.0.1, port: 41645
,I/BtToRequestSocket( 3550): --DoOneRunRound ended
,W/bt-sdp  ( 3596): process_service_search_attr_rsp
,E/bt-btif ( 3596): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 3 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 4 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 5 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 6 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 7 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 8 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 9 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3596): Index: 10 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3596): Index: 11 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3596): Index: 12 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 3596): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3596): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3596): Failed to remove device: 80:01:84:8A:B3:68
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3596): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3596): StableState(): Entering Off State
,D/BluetoothMetrics( 3596): btclass5a020c
,D/Checkin ( 3596): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3550): 2015-11-30T10:09:42.323Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.334Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.343Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.346Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.351Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3550): 2015-11-30T10:09:42.364Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.371Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.410Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.415Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.421Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.460Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.463Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.470Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.502Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.515Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.552Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.561Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.566Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.574Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.613Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.621Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.650Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.661Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:09:42.701Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3550): 
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 1
,W/bt-btif ( 3596): proc dm_pm_timer expires
,D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,V/AlarmManager( 1019): sending alarm Alarm{420d71a0 type 3 android}
,W/bt-btif ( 3596): invalid rfc slot id: 35
,I/BtToSocketBase( 3550): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
,I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Close LocalOutputStream
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3550): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3550): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3550): Close localHostSocket
,I/BtToSocketBase( 3550): Close bt in
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt out
,I/BtToSocketBase( 3550): Close bt socket
,I/BtToSocketBase( 3550): Close bt socket
,I/jxcore-log( 3550): 2015-11-30T10:10:14.344Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3550): 
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=1
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3596): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3596): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3596): tBTM_SEC_DEV:0x5f28ddd4 rs_disc_pending=0
,W/bt-btif ( 3596): bta_dm_check_av:0
,W/bt-btif ( 3596): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,W/bt-btif ( 3596): dm_pm_timer expires
,W/bt-btif ( 3596): dm_pm_timer expires 0
,W/bt-btif ( 3596): proc dm_pm_timer expires
,I/jxcore-log( 3550): timeout now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): dun
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): done, now sending data to server
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): -- RESULT DATA {"name:":"motorola-XT1039_PT6617","time":1000099,"result":"TIMEOUT","sendList":[{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"
,I/jxcore-log( 3550): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3550): 
I/jxcore-log( 3550): Results list does not contain any items
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): sendList failed peers count : 4 [100 %]
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 3550): 
I/jxcore-log( 3550): sendList never tried peers count : 17 [80.95238095238095 %]
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): - Peer ID : 34:FC:EF:11:AE:67
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3550): 
I/jxcore-log( 3550): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:10:20.396Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:10:20.396Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): 2015-11-30T10:10:20.398Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3550): 
I/BtConnectorHelper( 3550): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
,I/BtToSocketBase( 3550): Stop ReceivingThread
I/BtToSocketBase( 3550): Stop SendingThread
I/BtToSocketBase( 3550): Close local in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3550): Close LocalOutputStream
I/BtToSocketBase( 3550): Close localHostSocket
I/BtToSocketBase( 3550): Close bt in
,I/BtToSocketBase( 3550): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3550): Close bt out
I/BtToSocketBase( 3550): Close bt socket
,I/BtToRequestSocket( 3550): Close server socket
,I/jxcore-log( 3550): 2015-11-30T10:10:20.403Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3550): 
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3596): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 3596): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5949): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3596): Ftp Service onStartCommand
,V/BluetoothFtpService( 3596): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,D/BluetoothAdapterService(1106968872)( 3596): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3596): getBondedDevices: length=1
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3550): DBG, CoordinatorConnector command called
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): stop tests now !
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): stop current!
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): testSendData stopped
I/jxcore-log( 3550): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:493)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:395)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3550): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3550): onServerStopped
,E/bt-btif ( 3596): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): setState: INITIALIZED
,I/jxcore-log( 3550): StopBroadcasting went ok
I/jxcore-log( 3550): 
I/jxcore-log( 3550): 2015-11-30T10:10:45.639Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3550): 
I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onConnectionFailed: Socket is null
W/jxcore-log( 3550): $$jxcore_callback_52 wasn't registered
W/jxcore-log( 3550): 
,W/jxcore-log( 3550): $$jxcore_callback_52 wasn't registered
W/jxcore-log( 3550): 
I/jxcore-log( 3550): DBG, CoordinatorConnector command called
I/jxcore-log( 3550): 
I/jxcore-log( 3550): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"44:80:EB:7B:5A:05\",\"tim
,I/jxcore-log( 3550): ****TEST TOOK:  ms ****
I/jxcore-log( 3550): 
I/jxcore-log( 3550): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3550): 
I/jxcore-log( 3550): stop tests now !
I/jxcore-log( 3550): 
I/jxcore-log( 3550): end, event received
I/jxcore-log( 3550): 
,I/jxcore-log( 3550): CoordinatorConnector close called
I/jxcore-log( 3550): 
I/jxcore-log( 3550): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3550): 
I/jxcore-log( 3550): The Coordinator has disconnected!
I/jxcore-log( 3550): 
I/jxcore-log( 3550): The Coordinator has closed!
I/jxcore-log( 3550): 
I/jxcore-log( 3550): stop tests now !
I/jxcore-log( 3550): 
I/jxcore-log( 3550): turning Radios off
I/jxcore-log( 3550): 
I/jxcore-log( 3550): Toggling radios to false
I/jxcore-log( 3550): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@43d16da8 mBinding = false
,D/BluetoothManagerService( 1019): Message: 2
W/Settings( 1233): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1019): Sending off request.
D/BluetoothAdapterState( 3596): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3596): Setting state to 13
I/BluetoothAdapterState( 3596): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3596): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3596): onBluetoothDisable()
I/BluetoothAdapterState( 3596): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3596): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3596): Scan Mode:21
D/BluetoothAdapterState( 3596): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3596): bta_jv_rfcomm_stop_server
D/btif_config_util( 3596): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 3596): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3596): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3596): bta_jv_rfcomm_stop_server
E/bt-btif ( 3596): bta_jv_rfcomm_stop_server
E/bt-btif ( 3596): bta_jv_rfcomm_stop_server
W/bt-btif ( 3596): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3596): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3596): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
,W/Settings( 1233): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/BluetoothMapService( 3596): onReceive
D/BluetoothMapService( 3596): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3596): MAP Service closeService in
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6593 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/WifiService( 1019): setWifiEnabled: false pid=3550, uid=10417
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 3596): stopping Accept Thread
,I/BtOppRfcommListener( 3596): BluetoothSocket listen thread finished
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
W/Settings( 1233): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/jxcore-log( 3550): Radios toggled
I/jxcore-log( 3550): 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/chromium( 3550): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onBluetoothAdapterScanModeChanged: Mode changed to 21
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 21
,D/TCMD    (  499): Listening for incoming client connection request
,W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 944986
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43da6318:true
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,D/BluetoothPbapService( 3596): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
,D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3550): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
I/SBar.NetworkController( 1085): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): Message: 30
I/bt_hwcfg( 3596): hw_epilog_process
W/bt-btif ( 3596): ag scb idx 1 not allocated
E/bt-btif ( 3596): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3596): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3596): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3596): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3596): L2CAP - PSM: 0x0017 not found for deregistration
W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/bt-l2cap( 3596): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3596): L2CAP - PSM: 0x0017 not found for deregistration
D/LocalBluetoothProfileManager( 6593): Adding local MAP profile
D/BluetoothMap( 6593): Create BluetoothMap proxy object
D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x6124acb0 clazz=0xa2500001 iface=wlan0 mask=0x3
D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 6593): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 6593): finishStartingService: stopping service
I/bt_hwcfg( 3596): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3596): bt_hc_worker_thread exiting
D/bt_userial_mct( 3596): userial_close
I/bt_userial_mct( 3596): exiting userial_read_thread
D/bt_userial_mct( 3596): Leaving userial_evt_read_thread()
,D/WifiService( 1019): New client listening to asynchronous messages
V/NativeCrypto( 1324): Read error: ssl=0x6376cf40: I/O error during system call, Connection timed out
D/CommandListener(  275): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1085): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): stopping supplicant
D/WifiStateMachine( 1019): setWifiState: disabling
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): handleMessage: X
W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1263): Active network info is not available
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1085): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
V/NativeCrypto( 1324): SSL shutdown failed: ssl=0x6376cf40: I/O error during system call, Broken pipe
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1019): Attempting to switch to mobile
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5648): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/Tethering( 1019): InitialState.processMessage what=4
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1273): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1273): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1273): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
D/BluetoothInputDevice( 6593): Proxy object connected
D/HidProfile( 6593): Bluetooth service connected
D/BluetoothPan( 6593): BluetoothPAN Proxy object connected
D/PanProfile( 6593): Bluetooth service connected
D/BluetoothMap( 6593): Proxy object connected
D/MapProfile( 6593): Bluetooth service connected
V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMap( 6593): getConnectedDevices()
D/BluetoothMap( 6593): Bluetooth is Not enabled
I/ActivityManager( 1019): Killing 5974:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AuthorizationBluetoothService( 1324): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 5648): eap_proxy Deinitialzed
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
I/wpa_supplicant( 5648): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
I/wpa_supplicant( 5648): CTRL_IFACE monitor[0]: 2 - No such file or directory
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/AndroidRuntime( 6591): 
D/AndroidRuntime( 6591): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6591): CheckJNI is OFF
,D/dalvikvm( 6591): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 6591): Added shared lib libjavacore.so 0x0
,D/BTSNOOP-DISP( 3596): btsnoop_close
I/bt_vendor( 3596): cleanup
I/bt_hwcfg( 3596): Starting hciattach daemon
,I/bt_hwcfg( 3596): try to set false
,D/dalvikvm( 6591): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6591): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6591): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/GKI_LINUX( 3596): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3596): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 3596): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3596): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3596): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1019): Proxy object disconnected
D/BluetoothHeadset( 1251): Proxy object disconnected
,D/BluetoothHeadset( 1251): Proxy object disconnected
,D/BluetoothHeadset( 1251): Proxy object disconnected
,D/A2dpService( 3596): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3596): Exit Disconnected: -1
,D/BluetoothA2dp( 1019): Proxy object disconnected
,D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 3596): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3596): Cleaning up Bluetooth Handsfree callback object
,D/HidService( 3596): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3596): Stopping profile services that were post enabled
D/HealthService( 3596): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 6593): Proxy object disconnected
,D/HidProfile( 6593): Bluetooth service disconnected
,D/PanService( 3596): Received stop request...Stopping profile...
,D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43cd9048
,D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 6593): BluetoothPAN Proxy object disconnected
,D/PanProfile( 6593): Bluetooth service disconnected
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
,D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 3596): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3596): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 3596): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BtGatt.DebugUtils( 3596): handleDebugAction() action=null
D/BtGatt.GattService( 3596): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3596): stop()
,D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 3596): Received stop request...Stopping profile...
,D/BluetoothMapService( 3596): stop()
,D/BluetoothMapService( 3596): MAP Service closeService in
,D/BluetoothMap( 6593): Proxy object disconnected
D/MapProfile( 6593): Bluetooth service disconnected
W/BluetoothHidServiceJni( 3596): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3596): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3596): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 3596): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3596): Cleaning up Bluetooth Health object
,D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3596): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3596): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3596): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3596): cleanup()
,D/BluetoothAdapterState( 3596): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3596): Setting state to 10
I/BluetoothAdapterState( 3596): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3596): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothMapService( 3596): MAP Service closeService in
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothMap( 6593): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 3596): Entering OffState
,D/BluetoothHeadset( 1251): onBluetoothStateChange: up=false
,D/BluetoothPan( 1019): onBluetoothStateChange on: false
,D/WifiStateMachine( 1019): setWifiState: disabled
,D/BluetoothHeadset( 1251): onBluetoothStateChange: up=false
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
,W/XTWiFiOS( 1263): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1085): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1263): Active network info is not available
I/SBar.NetworkController( 1085): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [WwanPosMgr] handleConnectivtyStatusChange failed
,D/dalvikvm( 6591): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/BluetoothHeadset( 1251): onBluetoothStateChange: up=false
,D/BluetoothPan( 6593): onBluetoothStateChange on: false
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
,W/Settings( 1215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothInputDevice( 6593): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
,D/BluetoothPbap( 6593): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@43d16da8 mBinding = false
,D/BluetoothManagerService( 1019): Sending unbind request.
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 3596): Cleaning up adapter native....
,D/BluetoothAdapter( 1085): 1108408312: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 3596): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3596): GKI_exit_task: GKI_exit_task 1 done
,I/GKI_LINUX( 3596): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3596): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3596): Done cleaning up adapter native....
,D/BluetoothAdapterService(1106968872)( 3596): ****onDestroy()********
D/BtGatt.GattService( 3596): cleanup()
W/bt-btif ( 3596): GATTC Module not enabled/already disabled
,W/bt-btif ( 3596): GATTS Module not enabled/already disabled
,D/BluetoothAdapter( 1215): 1111015872: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1215): 1111015872: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  619): [CSMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 6593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 6593): finishStartingService: stopping service
,D/BluetoothAdapter( 6593): 1106956896: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3596): BluetoothFtpReceiver Stop Service
,V/BluetoothFtpService( 3596): Ftp Service onDestroy
V/BluetoothFtpService( 3596): Ftp Service closeService
D/AuthorizationBluetoothService( 1324): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothFtpService:RfcommSocketAcceptThread( 3596): Shutdown
,D/Checkin ( 6189): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1019): Killing 6010:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/memtrack( 6591): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 6591): failed to load memtrack module: -2
,D/AndroidRuntime( 6591): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10417 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3550:com.test.thalitest/u0a417 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{44732600 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1019): WIN DEATH: Window{43793d90 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{4225ba30 com.example.hello/10416} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10417 user=0: pkg removed
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/GeofencerStateMachine( 1215): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6647 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm( 2139): GC_EXPLICIT freed 958K, 47% free 9285K/17224K, paused 2ms+3ms, total 33ms
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 1289): GC_EXPLICIT freed 3051K, 33% free 11632K/17224K, paused 2ms+11ms, total 97ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
D/TCMD    (  499): NL - Read 444 bytes from update socket.
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - ignore NL message, type = 17
D/TCMD    (  499): Listening for incoming client connection request
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/dalvikvm( 2172): GC_EXPLICIT freed 4780K, 42% free 10119K/17224K, paused 4ms+23ms, total 124ms
I/Launcher( 1289): Deferring update until onResume
,D/dalvikvm( 1019): GC_EXPLICIT freed 1745K, 64% free 18071K/49968K, paused 5ms+15ms, total 142ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 46ms
,D/TCMD    (  499): NL - Read 1000 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
,D/TCMD    (  499): Listening for incoming client connection request
,I/Launcher( 1289): Deferring update until onResume
,D/VoicemailCleanupService( 6647): Cleaning up data for package: com.test.thalitest
,I/InternalIcingCorporaPro( 2172): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/NetlinkEvent(  275): Unexpected netlink message. type=0x11
W/Netd    (  275): No subsystem found in netlink event
D/TCMD    (  499): NL - Read 444 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 17
,D/TCMD    (  499): Listening for incoming client connection request
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6665 uid=10059 gids={50059, 3003, 1028, 1015}
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10417 #1
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448878246
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448878246
,I/ActivityManager( 1019): Killing 5854:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1019): GC_EXPLICIT freed 322K, 64% free 18083K/49968K, paused 21ms+17ms, total 243ms
,I/InternalIcingCorporaPro( 2172): UpdateCorporaTask done [took 169 ms] updated apps [took 169 ms] 
,D/AndroidRuntime( 6591): Shutting down VM
,D/dalvikvm( 6591): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/ContactLocale( 6647): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Checkin ( 2139): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/ActiveOrDefaultContextProvider( 6665): Missing scope.enter somewhere. Returning default context
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6682 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/ActivityManager( 1019): Killing 6085:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1233): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/GAV2    ( 6665): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 6682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6698 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,E/SQLiteDatabase( 6682): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 6682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6682): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 6682): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 6682): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6682): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 6682): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6682): threadid=10: thread exiting with uncaught exception (group=0x416cbd40)
,E/AndroidRuntime( 6682): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6682): Process: com.android.keychain, PID: 6682
E/AndroidRuntime( 6682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 6682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 6682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6682): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 6682): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 6682): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6682): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 6682): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6682): Sending signal. PID: 6682 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 5 more
I/ActivityManager( 1019): Process com.android.keychain (pid 6682) has died.
W/ActivityManager( 1019): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=6717 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/PackageBroadcastService( 1354): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1354): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1354): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1354): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1354): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteDatabase( 6698): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 6698): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6698): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 6698): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6698): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6698): 	at cwo.getWritableDatabase(PG:48)
E/SQLiteDatabase( 6698): 	at cwp.a(PG:262)
E/SQLiteDatabase( 6698): 	at eec.run(PG:155)
E/SQLiteDatabase( 6698): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 1354): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 1354): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1354): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 1354): disk I/O error (code 3850)
E/DriveAsyncService( 1354): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1354): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1354): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1354): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1354): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1354): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1354): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1354): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1354): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1354): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1354): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 1324): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1324): Shutting down VM
,W/dalvikvm( 1324): threadid=1: thread exiting with uncaught exception (group=0x416cbd40)
,E/AndroidRuntime( 1324): FATAL EXCEPTION: main
E/AndroidRuntime( 1324): Process: com.google.process.gapps, PID: 1324
E/AndroidRuntime( 1324): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1324): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1324): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1324): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1324): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1324): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1324): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1324): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1324): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1324): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1324): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1324): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1324): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1324): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1324): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1324): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1324): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1324): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1324): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1324): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1324): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1324): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1324): 	... 10 more
E/SQLiteLog( 1354): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1354): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1354): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1354): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1354): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1354): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.,SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1354): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1354): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1354): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1354): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1354): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1354): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1324): Sending signal. PID: 1324 SIG: 9

```
