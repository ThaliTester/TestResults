#### Test 50650278b28a87a_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{43e637e0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3477): 
D/AndroidRuntime( 3477): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3477): CheckJNI is OFF
D/dalvikvm( 3477): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3477): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3477): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3477): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3477): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3477): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3477): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3477): failed to load memtrack module: -2
D/AndroidRuntime( 3477): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3477
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3493 uid=10452 gids={50452, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3477): Shutting down VM
D/dalvikvm( 3477): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 24ms
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WebViewChromiumFactoryProvider( 3493): Binding Chromium to main looper Looper (main, tid 1) {42071880}
I/LibraryLoader( 3493): Expected native library version number "",actual native library version number ""
I/chromium( 3493): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3493): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4479c870:true
D/BluetoothAdapter( 3493): 1107844752: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3493): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3493): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3493): Local Branch: 
I/Adreno-EGL( 3493): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3493): Local Patches: NONE
I/Adreno-EGL( 3493): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3493): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3493): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3493): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3493): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3493): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3493): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3493): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3493): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3493): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3493): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3493): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3493): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3493): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3493): Enabling debug mode 0
,W/AwContents( 3493): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3493): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,430
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +399ms (total +430ms)
,D/JsMessageQueue( 3493): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3493): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42075d30
,D/dalvikvm( 3493): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42075d30
,D/jxcore_app_log( 3493): JniHelper::setJavaVM(0x4178af78), pthread_self() = 1614789352
,D/JX-Cordova( 3493): jxcore cordova android initializing
I/dalvikvm( 3493): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3493): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0045
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3493): GC_CONCURRENT freed 2825K, 17% free 14363K/17224K, paused 2ms+1ms, total 58ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 123K, 17% free 14367K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 305K, 17% free 14432K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.264MB for 144892-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 261K, 17% free 14475K/17368K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.375MB for 217334-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 376K, 18% free 14542K/17584K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.544MB for 325996-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 572K, 19% free 14664K/17904K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.820MB for 488990-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 870K, 20% free 14841K/18384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 17.225MB for 733480-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 1291K, 21% free 15099K/19104K, paused 27ms, total 27ms
,D/dalvikvm( 3493): GC_CONCURRENT freed 1675K, 20% free 15471K/19104K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 384K, 20% free 15429K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 18.673MB for 1650320-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 1763K, 23% free 16011K/20716K, paused 1ms+4ms, total 49ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 1316K, 23% free 16073K/20716K, paused 32ms, total 35ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 20.089MB for 2475476-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 222K, 21% free 18477K/23136K, paused 5ms+14ms, total 57ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 4411K, 27% free 17061K/23136K, paused 37ms, total 37ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 22.235MB for 3713210-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 320K, 24% free 20582K/26764K, paused 9ms+5ms, total 61ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 3197K, 33% free 18012K/26764K, paused 30ms, total 31ms
,W/jxcore-log( 3493): Initializing JXcore engine
,W/jxcore-log( 3493): JXcore engine is ready
,D/dalvikvm( 3493): GC_CONCURRENT freed 370K, 23% free 20620K/26764K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 3493): Starting JXcore engine
,W/jxcore-log( 3493): Platform android
W/jxcore-log( 3493): 
,W/jxcore-log( 3493): Process ARCH arm
W/jxcore-log( 3493): 
,I/jxcore-log( 3493): JXcore Cordova bridge is ready!
I/jxcore-log( 3493): 
,W/jxcore-log( 3493): JXcore engine is started
,I/chromium( 3493): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3493): Toggling radios to true
I/jxcore-log( 3493): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1018): Message: 1
,D/BluetoothManagerService( 1018): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1255): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1265): Active network info is not available
I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3550 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1255): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=3493, uid=10452
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1255): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1018): setting operational mode to 1
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1018): processMsg: InitialState
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3493): Radios toggled
I/jxcore-log( 3493): 
W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
W/Settings( 1255): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/XTWiFiOS( 1265): Active network info is not available
,I/jxcore-log( 3493): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3493): 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3493): Perf Test app loaded loaded
I/jxcore-log( 3493): 
,I/jxcore-log( 3493): check test folder
I/jxcore-log( 3493): 
,I/jxcore-log( 3493): found test : ./testFindPeers.js
I/jxcore-log( 3493): 
,I/jxcore-log( 3493): found test : ./testSendData.js
I/jxcore-log( 3493): 
,D/AdapterServiceConfig( 3550): Adding HeadsetService
D/AdapterServiceConfig( 3550): Adding A2dpService
D/AdapterServiceConfig( 3550): Adding HidService
D/AdapterServiceConfig( 3550): Adding HealthService
D/AdapterServiceConfig( 3550): Adding PanService
D/AdapterServiceConfig( 3550): Adding GattService
,D/AdapterServiceConfig( 3550): Adding BluetoothMapService
,D/BluetoothAdapterService( 3550): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@435ed8e8:true
,D/BluetoothAdapterState( 3550): make
,I/BluetoothAdapterState( 3550): Entering OffState
,I/bluedroid( 3550): init
,I/bte_conf( 3550): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3550): get_profile_interface socket
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1018): Message: 40
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 3550): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3550): Address is:F4:F1:E1:5C:3B:E2
,I/bluedroid( 3550): config_hci_snoop_log
D/BluetoothManagerService( 1018): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothAdapterProperties( 3550): Name is: XT1039
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
,D/BluetoothAdapterState( 3550): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3550): Setting state to 11
I/BluetoothAdapterState( 3550): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3550): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3550): make
,I/BluetoothBondStateMachine( 3550): StableState(): Entering Off State
,I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3576 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1018): Proxy object connected
,D/BluetoothHeadset( 1241): Proxy object connected
D/BluetoothHeadset( 1241): Proxy object connected
,D/BluetoothHeadset( 1241): Proxy object connected
D/HeadsetService( 3550): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3550): classInitNative: succeeds
D/HeadsetStateMachine( 3550): Version 1.6
,D/HeadsetStateMachine( 3550): make
,I/BluetoothAdapterState( 3550): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3550): get_profile_interface handsfree
,D/BluetoothA2dp( 1018): Proxy object connected
,D/A2dpService( 3550): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3550): classInitNative: succeeds
V/Avrcp   ( 3550): make
,I/bluedroid( 3550): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3550): classInitNative: succeeds
,D/A2dpStateMachine( 3550): make
,I/bluedroid( 3550): get_profile_interface a2dp
I/GKI_LINUX( 3550): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3550): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3550): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3550): classInitNative: succeeds
D/HidService( 3550): Received start request. Starting profile...
,I/bluedroid( 3550): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3550): classInitNative: succeeds
,D/HealthService( 3550): Received start request. Starting profile...
,I/bluedroid( 3550): get_profile_interface health
,I/BluetoothPanServiceJni( 3550): classInitNative(L105): succeeds
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 3550): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3550): initializeNative(L110): pan
,I/bluedroid( 3550): get_profile_interface pan
D/BluetoothTethering( 1018): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothTethering( 1018): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43a3e490
,I/BtGatt.JNI( 3550): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3550): handleDebugAction() action=null
D/BtGatt.GattService( 3550): Received start request. Starting profile...
D/BtGatt.GattService( 3550): start()
,I/bluedroid( 3550): get_profile_interface gatt
,D/BluetoothMapService( 3550): Received start request. Starting profile...
,D/BluetoothMapService( 3550): start()
,D/HeadsetPhoneState( 3550): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3550): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3550): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 3550): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3550): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3550): enable
I/chromium( 3493): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/bt_hci_bdroid( 3550): init
I/bt_vendor( 3550): bt-vendor : init
I/bt_hci_bdroid( 3550): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3550): userial_init
I/bt_hwcfg( 3550): Starting hciattach daemon
I/bt_hci_bdroid( 3550): bt_hc_worker_thread started
I/bt_hwcfg( 3550): try to set false
I/bt_hwcfg( 3550): Starting hciattach daemon
,I/bt_hwcfg( 3550): try to set true
,D/dalvikvm( 1200): GC_EXPLICIT freed 1362K, 41% free 10256K/17224K, paused 33ms+15ms, total 118ms
,I/qcom-bluetooth( 3609): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  275): NetlinkHandler, interfaceAdded
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
E/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  275): , Wifi = 0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,I/MDMCTBK (  275): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,I/ActivityManager( 1018): Killing 3233:com.android.calendar/u0a7 (adj 15): empty #9
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/MDMCTBK (  275): send SAR ctrl over QMI
D/TCMD    (  446): NL - Read 1004 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): InitialState.processMessage what=4
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  275): NetlinkHandler, interfaceAdded
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
E/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  275): , Wifi = 0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/TCMD    (  446): NL - Read 1004 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
I/qcom-bluetooth( 3619): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 3621): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/DataBuffer( 1200): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422b2dc0)
D/QsoftapCmd(  271): Got softap fwreload command we are passing on
D/SoftapController(  271): Softap fwReload - Ok
,D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring down wlan0
,D/WifiService( 1018): New client listening to asynchronous messages
I/qcom-bluetooth( 3625): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiHW  ( 1018): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
I/qcom-bluetooth( 3626): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/WifiHW  ( 1018): ctrl_interface != /data/misc/wifi/sockets
I/qcom-bluetooth( 3627): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
D/WifiStateMachine( 1018): setWifiState: enabling
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1265): Active network info is not available
D/WifiStateMachine( 1018): Supplicant start successful
D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
E/Diag_Lib( 3629): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3629): Setting internal use port to rmnet0
E/Diag_Lib( 3629):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3629): Failed on DIAG init
E/Diag_Lib( 3629): linux_qmi_qmux_if_client_get_proc_name: pid=3629, proc_name=hci_qcomm_init
E/Diag_Lib( 3629): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3629): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3629): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3629): qmi_client [3629]: successfully connected to server, attempt=1
E/Diag_Lib( 3629): linux_qmi_qmux_if_client_get_client_id [3629]: qmux_client_id=13
E/Diag_Lib( 3629): qmi_client [3629] 13: qmux_client ID is initialized
E/Diag_Lib( 3629): qmi_client [3629] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3629): qmi_client [3629] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3629): qmi_client [3629] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3629): Sending signal ...... to read cmd data 
E/Diag_Lib( 3629): qmi error code.........:0
E/Diag_Lib( 3629): qmi sys error code.........:0
E/Diag_Lib( 3629): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3629): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3629): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3629): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3629): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3629): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3629): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3629): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3629): qmi_init:  Created client handle b8f54b10
E/Diag_Lib( 3629): qmi_client [3629] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3629): qmi_client [3629] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3629): Sending signal ...... to read cmd data 
E/Diag_Lib( 3629): qmi error code.........:0
E/Diag_Lib( 3629): qmi sys error code.........:0
V/BluetoothFtpReceiver( 3550): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
E/Diag_Lib( 3629): Setting the api flag to : 1
,E/Diag_Lib( 3629): qmi_client [3629] 13: sending 54 bytes on fd = 8
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3632): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3632): rfkill: Cannot open RFKILL control device
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
I/rmt_storage(  404): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7b1b1d0
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
I/rmt_storage(  404): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
I/rmt_storage(  404): wakelock acquired: 1, error no: 42
,I/rmt_storage(  404): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1213091272)
E/Diag_Lib( 3629): qmi_client [3629] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3629):  API Flag .............. 1 
,E/Diag_Lib( 3629):  Message ID ............... 92 
,E/Diag_Lib( 3629): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3629): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3629): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3629): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3629): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3629): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3629): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3629): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3629): qmi_client [3629] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3629): qmi_client [3629] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3629): Sending signal ...... to read cmd data 
E/Diag_Lib( 3629): qmi error code.........:0
E/Diag_Lib( 3629): qmi sys error code.........:0
E/Diag_Lib( 3629): qmi_release: Released client handle ff
E/Diag_Lib( 3629): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3629): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3629): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3629): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3629): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3629): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3629): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3629): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3629): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3629): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3629): qmi_client [3629] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3629): qmi_client [3629] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3629): Sending signal ...... to read cmd data 
E/Diag_Lib( 3629): qmi error code.........:0
E/Diag_Lib( 3629): qmi sys error code.........:0
E/Diag_Lib( 3629): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3629] 13
E/Diag_Lib( 3629): qmi_client [3629] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3629): qmi_client [3629] 13: failed to locate client data
E/Diag_Lib( 3629): qmi_client [3629] 13: calling release of fd=8
E/Diag_Lib( 3629): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
E/Diag_Lib( 3632): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3632): Setting internal use port to rmnet0
E/wpa_supplicant( 3632): baseband property is set to [msm]
E/wpa_supplicant( 3632):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3632): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3632): card_info[i].card_state: 0x2
E/wpa_supplicant( 3632): card_info[i].error_code: 0x3
E/wpa_supplicant( 3632): SIM/USIM not ready
E/wpa_supplicant( 3632): Error while reading SIM card status
,E/wpa_supplicant( 3632): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3632): card_info[i].card_state: 0x2
E/wpa_supplicant( 3632): card_info[i].error_code: 0x3
E/wpa_supplicant( 3632): SIM/USIM not ready
,I/wpa_supplicant( 3632): eap_proxy: Card not ready
,I/qcom-bluetooth( 3636): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
I/rmt_storage(  404): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  404): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  404): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1213091272) wakelock released: 1, error no: 0
I/rmt_storage(  404): 
,I/qcom-bluetooth( 3637): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/rmt_storage(  404): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7b1b1d0
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/bt_hwcfg( 3550): bluetooth satus is on
D/bt_userial_mct( 3550): userial_open(port:0)
I/GKI_LINUX( 3550): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3550): btu_task pending for preload complete event
,I/bt_userial_vendor( 3550): Done intiailizing UART
I/bt_userial_vendor( 3550): Done intiailizing UART
I/bt_userial_mct( 3550): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3550): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3550): Entering userial_read_thread()
,I/bt-btu  ( 3550): btu_task received preload complete event
,I/        ( 3550): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3550): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3550): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3550): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3550): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3550): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3550): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3550): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3550): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3550): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3550): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3550): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3550): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3550): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3550): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3550): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0d2049 
,E/bt-btm  ( 3550): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0d2049 
,E/bt-btif ( 3550): Calling BTA_HhEnable
E/bt-btif ( 3550): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3550): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3550): Name is: XT1039
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3550): Scan Mode:21
I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3550): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:3 len:48
I/bte_conf( 3550): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3550): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3550): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3550): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,E/bt_mct  ( 3550): hci lib postload completed
,D/BluetoothPanServiceJni( 3550): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3550): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3550): ScanMode =  21
D/BluetoothAdapterProperties( 3550): State =  11
D/BluetoothAdapterProperties( 3550): Setting state to 12
I/BluetoothAdapterState( 3550): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3550): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan( 1018): onBluetoothStateChange on: true
,D/BluetoothHeadset( 1241): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1241): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3550): Entering On State
D/BluetoothHeadset( 1018): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 11 -> 12
I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3550): Discoverable Timeout:120
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3550): onReceive
D/BluetoothManagerService( 1018): Message: 40
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3550): STATE_ON
D/BluetoothMapService( 3550): Map Service startRfcommSocketListener
,D/BluetoothMapService( 3550): Map Service initSocket
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
E/BluetoothServiceJni( 3550): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3550): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothMapService( 3550): Accepting socket connection...
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3550): Scan Mode:21
,I/qcom-bt-wlan-coex( 3650): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4355eed8:true
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
I/wpa_supplicant( 3632): Long line in configuration file truncated
,I/wpa_supplicant( 3632): rfkill: Cannot open RFKILL control device
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/LocalBluetoothProfileManager( 3576): Adding local A2DP profile
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/BluetoothPbapService( 3550): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3550): Handler(): got msg=1
D/LocalBluetoothProfileManager( 3576): Adding local HEADSET profile
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): Message: 30
W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3550): SOCK FLAG = 1 ***********************
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3576): Adding local MAP profile
D/BluetoothMap( 3576): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3576): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3576): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3576): finishStartingService: stopping service
,D/BluetoothAdapterService(1107789384)( 3550): Get Bonded Devices being called
,E/wpa_supplicant( 3632): COUNTRY Code Recived
,E/wpa_supplicant( 3632): COUNTRY Code Recived -COUNTRY PL
E/wpa_supplicant( 3632): baseband property is set to [msm]
D/BluetoothA2dp( 3576): Proxy object connected
,D/A2dpProfile( 3576): Bluetooth service connected
,D/BluetoothHeadset( 3576): Proxy object connected
,D/HeadsetProfile( 3576): Bluetooth service connected
,D/BluetoothInputDevice( 3576): Proxy object connected
,D/HidProfile( 3576): Bluetooth service connected
D/BluetoothPan( 3576): BluetoothPAN Proxy object connected
D/PanProfile( 3576): Bluetooth service connected
E/wpa_supplicant( 3632):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
D/BluetoothMap( 3576): Proxy object connected
,D/MapProfile( 3576): Bluetooth service connected
,D/BluetoothMap( 3576): getConnectedDevices()
D/BluetoothPbap( 3576): Proxy object connected
D/PbapServerProfile( 3576): Bluetooth service connected
E/wpa_supplicant( 3632): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3632): card_info[i].card_state: 0x2
E/wpa_supplicant( 3632): card_info[i].error_code: 0x3
E/wpa_supplicant( 3632): SIM/USIM not ready
,E/wpa_supplicant( 3632): Error while reading SIM card status
E/wpa_supplicant( 3632): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3632): card_info[i].card_state: 0x2
E/wpa_supplicant( 3632): card_info[i].error_code: 0x3
E/wpa_supplicant( 3632): SIM/USIM not ready
,I/wpa_supplicant( 3632): eap_proxy: Card not ready
,D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: InitialState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): deferMessage: msg=131144
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): deferMessage: msg=131085
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131149
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1018): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147457
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): Supplicant connection established
,D/WifiStateMachine( 1018): setWifiState: enabled
,I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
V/BluetoothFtpReceiver( 3550): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3550): BluetoothFtpReceiver Start Service
W/XTWiFiOS( 1265): Active network info is not available
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiConfigStore( 1018): Loading config and enabling all networks
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1354): Proximity feature is not enabled.
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/WifiConfigStore( 1018): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
E/wpa_supplicant( 3632): COUNTRY Code Recived -COUNTRY PL
E/BluetoothServiceJni( 3550): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3550): Accept thread started.
,V/BluetoothFtpService( 3550): Ftp Service onCreate
I/BluetoothFtpService( 3550): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3550): Starting FTP service
V/BluetoothFtpService( 3550): Ftp Service onStartCommand
,V/BluetoothFtpService( 3550): action: android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine( 1018): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartingState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
V/BluetoothFtpService( 3550): Handler(): got msg=1
D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartedState
V/BluetoothFtpService( 3550): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3550): Ftp Service initSocket
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine( 1018): invokeEnterMethods: DriverStartedState
,W/BluetoothAdapter( 3550): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1018): setDetailed state, old =IDLE and new state=DISCONNECTED
,E/BluetoothServiceJni( 3550): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3550): Succeed to create listening socket on channel 20
E/wpa_supplicant( 3632): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3632): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1018): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3550): Run Accept thread
,D/WifiP2pService( 1018): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine( 1018): handleMessage: X
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up p2p0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131152
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set country code PL
,D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1018): P2pEnablingState
D/WifiP2pService( 1018): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2p socket connection successful
D/WifiP2pService( 1018): P2pEnabledState
D/WifiP2pService( 1018): sending p2p connection changed broadcast
,E/wpa_supplicant( 3632): COUNTRY Code Recived
,E/wpa_supplicant( 3632): COUNTRY Code Recived
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131162
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): set frequency band 2
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131167
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=143371
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiP2pService( 1018): DeviceAddress: f4:f1:e1:5c:43:c8
,D/WifiP2pService( 1018): MCC mode enabled 0
,D/WifiP2pService( 1018): mP2pAutoConnectSupport = 0
,D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1018): InactiveState
D/WifiP2pService( 1018): InactiveState{ when=-23ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-23ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): InactiveState{ when=-24ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-25ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3632): COUNTRY Code Recived
,E/wpa_supplicant( 3632): COUNTRY Code Recived
D/WifiP2pService( 1018): InactiveState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1018): GC_EXPLICIT freed 22698K, 65% free 17835K/50140K, paused 5ms+12ms, total 166ms
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  275): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  275): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): wifi_connect_to_supplicant, current pid is = 275
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  275): wifi_close_sockets: Exit
,E/MDMCTBK (  275): Attach monitor thread
I/MDMCTBK (  275): createWifiMonitorThread: Started the wifi monitor thread -1196321704
,D/MDMCTBK (  275): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/Checkin ( 2129): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledStateupdate channel list
,D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 9e:93:4e:3e:ba:c5
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 9e:93:4e:3e:ba:c5
D/TCMD    (  446): NL - Read 56 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
I/wpa_supplicant( 3630): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3630): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 9e
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 9e,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiP2pService( 1018): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428b19c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428b19c8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@428b19c8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,I/jxcore-log( 3493): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3493): 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  446): NL - Read 56 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiP2pService( 1018): InactiveState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 3632): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/TCMD    (  446): NL - Read 56 bytes from update socket.,
,D/TCMD    (  446): NL - message type is RTM_NEWLINK,
D/TCMD    (  446): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
,E/wpa_supplicant( 3632): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 3632): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3632): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  446): NL - Read 312 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 192 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 68 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3632): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  446): NL - Read 80 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 80 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 68 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request,
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X,
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3632): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3632): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1196326040
,I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-31ms what=147462 obj=android.net.wifi.StateChangeResult@428a0848 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425fcde0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425fcde0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  446): NL - Read 56 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c2
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 c2,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 06
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 64
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fc
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 fc
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/TCMD    (  446): NL - Read 60 bytes from update socket.
D/TCMD    (  446): NL - ignore NL message, type = 20
,D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1018): WiFi NOT Tethered!
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42147578
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1287): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1287): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1287): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@42147578
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_3_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi three bars."
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1287): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1287): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1287): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=-21ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1018): Setting time of day to sec=1449671506
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,W/        ( 1018): Unable to set rtc to 1449671506: Invalid argument
,D/PollingManager( 1538): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3741 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/PollingManager( 1538): now: 385850 ,futureTime: 86439181
D/PollingManager( 1538): Polling alarm set to expire at: 86439181 Current Time: 385850
,E/ActivityThread( 1538): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1538): registerApp(): CCE
I/CCE     ( 1538): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1538): Registering with Alarm Manager to restart CCE
,D/TelephonyProvider( 1241): Column apn id key is 'apn_id'
,D/MMApiWebService( 1538): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
D/CCE     ( 1538): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1538): isRequestAllowed(): already have outstanding request ... ignoring request
,W/XTWiFiOS( 1265): No entry in secure settings for enhanced location services: false
,D/OtaApp  ( 1538): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1538): [debug] > CusSM.onRadioUp
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1538): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/TelephonyProvider( 1241): Column apn id key is 'apn_id'
D/PollingManager( 1538): now: 385910 ,futureTime: 86439181
,D/PollingManager( 1538): Polling alarm set to expire at: 86439181 Current Time: 385910
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1538): generating token using payload instead of using session token
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1538): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,E/ActivityThread( 1538): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1538): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1538): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1538): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1538): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1538): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1354): GC_EXPLICIT freed 1023K, 39% free 10598K/17224K, paused 3ms+6ms, total 41ms
,I/MMApiWSBase( 1538): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1538): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3741): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42071280, skipping init
I/openssl ( 3741): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3741): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Killing 3344:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/VacuumService( 1354): Vacuum at: now=1449671506911 tag=VacuumService
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3786 uid=10030 gids={50030, 3003, 1028, 1015}
,V/MmsConfig( 3786): mnc/mcc: 
V/MmsConfig( 3786): tag: bool value: enabledMMS - true
V/MmsConfig( 3786): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 3786): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3786): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3786): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3786): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3786): tag: int value: minMessageCountPerThread - 10
,V/MmsConfig( 3786): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3786): tag: int value: recipientLimit - 20
V/MmsConfig( 3786): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3786): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3786): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3786): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3786): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3786): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3786): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3786): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3786): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1018): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3805 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3819 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1018): Killing 3018:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1241): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1241): Column apn id key is 'apn_id'
,D/GpsLocationProvider( 1018): NTP server returned: 1449671503630 (Wed Dec 09 15:31:43 CET 2015) reference: 382835 certainty: 13 system time offset: -3439
I/dalvikvm( 1372): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1372): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1372): VFY: replacing opcode 0x6e at 0x0033
,E/LocSvc_ApiV02( 1018): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/dalvikvm( 1241): GC_EXPLICIT freed 1461K, 45% free 9517K/17224K, paused 3ms+5ms, total 48ms
,E/Auth.Api.Credentials( 1372): [CredentialSyncAdapter] Unknown sync event.
,D/MobileConnectivityChangeReceiver( 3819): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3819): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3819): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3819): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1018): Killing 3377:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1372): Checkin interval check for package: unspecified last checkin: 1449594777586 min interval config: 0 actual interval: 76729547
,I/CheckinService( 1372): Checking schedule, now: 1449671507141 next: 1449594807560
,I/CheckinService( 1372): active receiver: enabled
,I/CheckinService( 1372): Preparing to send checkin request
,I/EventLogService( 1372): Accumulating logs since 1449670424488
,D/DelayedSyncController( 3805): Delaying sync.
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3842 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3045:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DelayedSyncController( 3805): Delaying sync.
,I/dalvikvm( 1018): Jit: resizing JitTable from 8192 to 16384
,I/jxcore-log( 3493): Connected to the server!
I/jxcore-log( 3493): 
,I/chromium( 3493): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/WebViewChromiumFactoryProvider( 3842): Binding Chromium to main looper Looper (main, tid 1) {4206e340}
,I/LibraryLoader( 3842): Expected native library version number "",actual native library version number ""
,I/chromium( 3842): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3842): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3842): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3842): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3842): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3842): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3842): Local Branch: 
I/Adreno-EGL( 3842): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3842): Local Patches: NONE
I/Adreno-EGL( 3842): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1372): GC_CONCURRENT freed 1704K, 33% free 11694K/17224K, paused 5ms+7ms, total 45ms
,I/CheckinRequestBuilder( 1372): Checkin reason type: 8 attempt count: 1
D/WifiService( 1018): New client listening to asynchronous messages
E/ActivityThread( 1372): Failed to find provider info for com.google.android.wearable.settings
,W/chromium( 3842): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3842): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3842): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1018): GC_EXPLICIT freed 1810K, 65% free 17811K/50140K, paused 3ms+10ms, total 93ms
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3842): Starting up...
,I/ImageResourceManager( 3063): ImageResourceManager: uninitalized
,I/iu.Environment( 3063): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3063): SYNC; picasa accounts
I/dalvikvm( 1354): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1354): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1354): VFY: replacing opcode 0x6e at 0x0033
I/ActivityManager( 1018): Killing 3403:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3063): num queued entries: 0
,I/iu.UploadsManager( 3063): num updated entries: 0
,I/iu.SyncManager( 3063): NEXT; no task
,I/iu.SyncManager( 1372): SYNC; picasa accounts
,D/NetworkLogImpl( 1372): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1372): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1372): num queued entries: 0
,I/iu.UploadsManager( 1372): num updated entries: 0
,I/iu.SyncManager( 1372): NEXT; no task
,D/DEBUG   ( 1538): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1538): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1538): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1538): ServiceHandler.handleMessage: mWaitCount=1
I/openssl ( 3741): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3741): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3819): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3819): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3063): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/dalvikvm( 3063): GC_CONCURRENT freed 621K, 5% free 16455K/17224K, paused 4ms+2ms, total 25ms
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3905 uid=10007 gids={50007, 3003}
,D/ExtensionsFactory( 3905): No custom extensions.
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3922 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 3082:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3932 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3576:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmClock( 3922): AlarmInitReceiver android.intent.action.TIME_SET
,D/WifiService( 1018): Client connection lost with reason: 4
,I/AlarmClock( 3922): Displaying next alarm time: ''
,V/AlarmClock( 3922): AlarmInitReceiver finished
,I/ActivityManager( 1018): Killing 3741:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/CalendarProvider2( 3932): Created com.android.providers.calendar.CalendarAlarmManager@42089fd0(com.android.providers.calendar.CalendarProvider2@42081b88)
,I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3951 uid=10098 gids={50098}
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 3951): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42076090, skipping init
,D/TimeService( 3951): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671507988
D/        ( 3951): TimeServiceNative: User Time to be set is 1449671507988
D/QC-time-services( 3951): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3951): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3951): Lib:time_genoff_operation: pargs->ts_val = 1449671507988
D/QC-time-services(  392): Daemon: Connection accepted:time_genoff
D/QC-time-services(  392): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671507988
D/QC-time-services(  392): Daemon:genoff_opr: Base = 2, val = 1449671507988, operation = 0
D/QC-time-services(  392): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/9/115 14:25:53
D/QC-time-services(  392): Daemon:Value read from RTC seconds = 1449671153000
D/QC-time-services(  392): Daemon:new time 1449671507988 
D/QC-time-services(  392): Daemon: delta 354988 genoff 354988 
D/QC-time-services(  392): Daemon:genoff_persistent_update: Writing genoff = 354988 to memory
D/QC-time-services(  392): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  392): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3951): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  392): Updating the TOD offset
D/QC-time-services(  392): Daemon:genoff_persistent_update: Writing genoff = 354988 to memory
D/QC-time-services(  392): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  392): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  392): Daemon:Update to modem bit set
D/QC-time-services(  392): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  392): Daemon: Base = 2, Value being sent to MODEM = 18446743757745106604
,E/QC-time-services( 3951): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
E/QC-time-services(  392): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  392): Daemon: Time-services: Waiting to acceptconnection
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/CheckinService( 1372): Checkin interval check for package: unspecified last checkin: 1449594777586 min interval config: 0 actual interval: 76730436
,D/DEBUG   ( 1538): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1538): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1538): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1538): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1538): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1538): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1538
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1538): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1538
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1538): GC_CONCURRENT freed 3027K, 38% free 10827K/17224K, paused 4ms+11ms, total 54ms
,W/IInputConnectionWrapper( 3493): showStatusIcon on inactive InputConnection
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,123
D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{42244b88 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/GCM     ( 1354): GCM config loaded
,D/UdcCache:FPQuery( 1372): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1354): GC_CONCURRENT freed 1896K, 39% free 10649K/17224K, paused 2ms+3ms, total 27ms
,D/MMApiWSBase( 1538): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1538): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1538): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3976 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/GCM     ( 1354): Ack for not saved message 23
,D/GetConfigurationSnapshotOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/dalvikvm( 3976): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3976): VFY: replacing opcode 0x60 at 0x000b
,D/Checkin ( 1538): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1538): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1538): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/SundryService( 1538): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1538): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1538): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1538): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1538): unbindWebServices(): un-registering our AIDL callback...
I/dalvikvm( 3976): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3976): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 3976): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3976): install
,I/MultiDex( 3976): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
I/MMApiWSBase( 1538): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MultiDex( 3976): loading existing secondary dex files
,I/MultiDex( 3976): load found 3 secondary dex files
,I/MultiDex( 3976): install done
,I/PhenotypeFlagCommitter( 1354): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1354): Using platform SSLCertificateSocketFactory
D/dalvikvm( 3976): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3976): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3976): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3976): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3976): VFY: unable to resolve instance field 46
,D/dalvikvm( 3976): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3976): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3976): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3976): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3976): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3976): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3976): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4206ca90
D/dalvikvm( 3976): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4206ca90
,D/dalvikvm( 3976): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4206ca90, skipping init
,D/dalvikvm( 3976): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4206ca90
D/dalvikvm( 3976): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4206ca90
,V/JNIHelp ( 3976): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MMApiProvisionService( 1538): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
D/MMApiProvisionService( 1538): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1538): doRequest(): /v1/dp/devices.json resp length: 138
,I/dalvikvm( 1538): Jit: resizing JitTable from 4096 to 8192
,D/MMApiProvisionService( 1538): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1538): handleResponse(): Session Expiration alarm set to expire at: Fri Dec 11 15:30:50 CET 2015
D/MMApiProvisionService( 1538): _setMMApiCredInfo: storing credential info 
D/dalvikvm( 3976): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4206ca90
,D/dalvikvm( 3976): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4206ca90
D/dalvikvm( 3976): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4206ca90
,D/dalvikvm( 3976): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4206ca90
,E/MMApiProvisionService( 1538): handleResponse(): no settings sent by the server:
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/DEBUG   ( 1538): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,W/ContextImpl( 1538): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1538): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1538): onServiceConnected()
D/GetNotificationsWS( 1538): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1538): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1538): Received shoulder tap
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/WaitableIntentService( 1538): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1538): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1538): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1538): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1538): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/ProviderInstaller( 3976): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1200): callingUid 10022, callindPid: 1200
,E/MDM     ( 1200): [73] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1372): Restart initialization of location
,D/AuthorizationBluetoothService( 1354): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1354): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/AuthorizationBluetoothService( 1354): Proximity feature is not enabled.
I/dalvikvm( 3976): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 3976): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x000d
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 3976): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 3976): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x0220
,V/GmsCoreStatsServiceLauncher( 1372): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 3976): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3976): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 3976): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 3976): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 3976): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3976): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 3976): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3976): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3976): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 3976): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,W/GCoreFlp( 1200): No location to return for getLastLocation()
,W/FusedLocationProvider( 1354): location=null
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
I/CalendarProvider2( 3932): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
,W/ContentResolver( 3932): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  279): App is not loaded in QSEE
,D/AlertReceiver( 3905): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3905): 0 Action = android.intent.action.PROVIDER_CHANGED
I/dalvikvm( 3976): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 3976): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 3976): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3976): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3976): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 3976): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 3976): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 3976): VFY: replacing opcode 0x6e at 0x00bb
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5116000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5116000
,I/GoogleURLConnFactory( 3976): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=2258008694
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1287): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1287): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1287): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1287): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/NativeLibraryUtils( 3976): Install completed successfully. count=13 extracted=0
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MMApiWSBase( 1538): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1538): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1538): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1538): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1538): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1538): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1538): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1538): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1538): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1538): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1538): unbindWebServices(): un-registering our AIDL callback...
,D/MMApiWSBase( 1538): doRequest(): v1/us/devices/check resp length: 188
,D/CCE     ( 1538): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1538): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.1303749709 for reqID:  error: None
,D/OtaWebService( 1538): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@4280b1c8 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@421b2290
,D/OtaWebService( 1538): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1538): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@4280c868 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@421b2290
,D/OtaWebService( 1538): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
I/OtaApp  ( 1538): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1538): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: no upgrades found for this device at this time
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
I/OtaApp  ( 1538): [info] > Next Polling is scheduled at 1439 mins from now
D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
D/PollingManager( 1538): registerApp(): cUsPollingService
D/OtaApp  ( 1538): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,D/OtaApp  ( 1538): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1538): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1538): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1538): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1538): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1538): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1538
,D/OtaWebService( 1538): [debug] > appending web service response to serviceHandler
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaWebService( 1538): [debug] > Removing request :v1/us/devices/check from queue
D/OtaWebService( 1538): [debug] > No pending web request. shutdown webservice
I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaWebService( 1538): [info] > Stopping webservice android service
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1354): GC_CONCURRENT freed 1619K, 37% free 10966K/17224K, paused 6ms+5ms, total 39ms
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1354):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 3976): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4240cd98
D/dalvikvm( 3976): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4240cd98
,D/dalvikvm( 3976): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4240cd98, skipping init
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
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
D/WVCdm   (  279): PrepareKeyRequest: nonce=1685651324
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/GAV2    ( 3842): Thread[GAThread,5,main]: No campaign data found.
,W/Settings( 3976): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 3976): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4065): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3976): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3976): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 68ms
,I/Adreno-EGL( 3976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3976): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3976): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3976): Local Branch: 
I/Adreno-EGL( 3976): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3976): Local Patches: NONE
I/Adreno-EGL( 3976): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3976): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3976): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3976): Local Branch: 
I/Adreno-EGL( 3976): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3976): Local Patches: NONE
I/Adreno-EGL( 3976): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3976): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3976): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3976): Local Branch: 
I/Adreno-EGL( 3976): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3976): Local Patches: NONE
I/Adreno-EGL( 3976): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3976): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3976): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3976): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3976): Local Branch: 
I/Adreno-EGL( 3976): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3976): Local Patches: NONE
I/Adreno-EGL( 3976): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1372): Classify the device as Phone.
,I/CheckinTask( 1372): Sending checkin request (11835 bytes)
,I/GlobalDismissManager( 3905): no sender configured
,D/AlertService( 3905): Beginning updateAlertNotification
,D/AlertService( 3905): No fired or scheduled alerts
,D/AlertService( 3905): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3905): No events found starting within 1 week.,
I/ActivityManager( 1018): Killing 3786:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinRequestBuilder( 1372): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1372): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1018): GC_EXPLICIT freed 922K, 65% free 17763K/50140K, paused 4ms+10ms, total 96ms
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1372): Classify the device as Phone.
,I/CheckinTask( 1372): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1372): Checking schedule, now: 1449671515224 next: 1450264585210
,I/CheckinService( 1372): active receiver: disabled
,D/CheckinService( 1372): Recording last checkin time for package unspecified as 1449671515238
,D/GCM     ( 1354): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1372): GC_CONCURRENT freed 2020K, 33% free 11681K/17224K, paused 5ms+10ms, total 76ms
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1018): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4086 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1200): DISABLE
,I/GCoreNlp( 1200): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4086): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4086): MmsConfig.loadMmsSettings
I/Babel   ( 4086): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4086): MmsConfig.loadFromDatabase
,E/Babel   ( 4086): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4086): MmsConfig.loadFromResources
,E/Babel   ( 4086): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4086): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4086): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4123 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3819:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4142 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3805:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2160): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/dalvikvm( 3063): GC_FOR_ALLOC freed 47K, 5% free 16417K/17224K, paused 12ms, total 12ms
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4161 uid=10038 gids={50038, 3003, 1028, 1015}
,I/dalvikvm-heap( 3063): Grow heap (frag case) to 19.802MB for 1821008-byte allocation
I/ActivityManager( 1018): Killing 3842:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3063): GC_FOR_ALLOC freed 2K, 5% free 18196K/19004K, paused 14ms, total 15ms
,I/ContactLocale( 4123): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4161): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4161): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4161): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2160): UpdateCorporaTask done [took 228 ms] updated apps [took 228 ms] 
,I/dalvikvm( 4161): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4161): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4161): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4161): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4161): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/dalvikvm( 4161): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4161): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4161): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4161): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4161): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4161): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4161): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4161): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4161): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4161): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4196 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4161): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4161): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4161): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4161): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4161): Skipping gmscore version check
,I/dalvikvm( 4161): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4161): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1018): Killing 3932:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1372): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1372): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1372): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4196): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x420733d8, skipping init
I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4196): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Killing 3951:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4161): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4161): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1018): Killing 3922:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1018): sending alarm Alarm{43d6bc08 type 0 com.android.vending}
,D/Finsky  ( 4161): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4161): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4161): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4161): VFY: replacing opcode 0x62 at 0x0038
,I/qtaguid ( 4161): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4161): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4161): untagSocket(67) failed with errno -22
,D/Finsky  ( 4161): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/dalvikvm( 1018): GC_EXPLICIT freed 1567K, 65% free 17916K/50140K, paused 4ms+10ms, total 96ms
,I/dalvikvm( 4161): Total arena pages for JIT: 11
,I/dalvikvm( 4161): Total arena pages for JIT: 12
I/dalvikvm( 4161): Total arena pages for JIT: 13
,I/dalvikvm( 4161): Total arena pages for JIT: 14
,I/qtaguid ( 4161): Failed write_ctrl(u 67) res=-1 errno=22
I/qtaguid ( 4161): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4161): untagSocket(67) failed with errno -22
,V/AlarmManager( 1018): sending alarm Alarm{43e42c20 type 3 android}
,D/dalvikvm( 4161): GC_FOR_ALLOC freed 4539K, 29% free 12246K/17224K, paused 29ms, total 29ms
,D/dalvikvm( 4161): GC_FOR_ALLOC freed 1089K, 28% free 12464K/17224K, paused 19ms, total 20ms
,D/dalvikvm( 4161): GC_CONCURRENT freed 1142K, 23% free 13370K/17224K, paused 2ms+3ms, total 35ms
,D/dalvikvm( 4161): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4161): GC_CONCURRENT freed 1180K, 18% free 14237K/17224K, paused 3ms+3ms, total 42ms
,D/dalvikvm( 4161): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4161): GC_CONCURRENT freed 1498K, 15% free 14787K/17224K, paused 1ms+2ms, total 51ms
,D/dalvikvm( 4161): WAIT_FOR_CONCURRENT_GC blocked 26ms
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 4161): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4161): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4161): untagSocket(67) failed with errno -22
,D/Finsky  ( 4161): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.android.chrome to true
,D/Finsky  ( 4161): [1] LibraryUtils.isAvailable: com.quickoffice.android available because owned, overriding [restriction=7].
,I/dalvikvm( 4161): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 4161): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4161): VFY: replacing opcode 0x6e at 0x0013
,D/Finsky  ( 4161): [1] InstallerImpl.requestInstall: Request install of com.google.android.gms v=8489036 pri=2 for auto_update
,D/Finsky  ( 4161): [1] InstallerImpl.kick: Installer kick - starting com.google.android.gms
,D/Finsky  ( 4161): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4161): [1] DailyHygiene.access$600: Logging device features
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{42330990 type 0 com.android.vending}
,D/DeviceConnectionService( 1200): client connected with version: 8296000
,D/Finsky  ( 4161): [349] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 4161): GC_CONCURRENT freed 1551K, 12% free 15237K/17224K, paused 3ms+3ms, total 63ms
,I/qtaguid ( 4161): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4161): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4161): untagSocket(67) failed with errno -22
,D/Finsky  ( 4161): [1] DownloadImpl.setState: Duplicate state set for 'com.google.android.gms' (0). Already in that state
,D/Finsky  ( 4161): [1] DownloadQueueImpl.add: Download com.google.android.gms added to DownloadQueue
,D/Finsky  ( 4161): [1] DownloadImpl.setState: com.google.android.gms from 0 to 1.
,I/installd(  280): free_cache(21130562) avail 4760592384
,D/Finsky  ( 4161): [1] StartNextDownloadRunnable.run: Download com.google.android.gms starting
,I/openssl ( 4196): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4196): Crypto mode 0 already enabled
D/Finsky  ( 4161): [330] DownloadQueueImpl$7.run: Enqueued com.google.android.gms as content://downloads/my_downloads/257
D/Finsky  ( 4161): [1] DownloadImpl.setState: com.google.android.gms from 1 to 2.
D/Finsky  ( 4161): [1] DownloadQueueImpl.onStart: com.google.android.gms: onStart
,D/Finsky  ( 4161): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 0/-1 Status: 190.
,D/Finsky  ( 4161): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 0/-1 Status: 192.
,I/DownloadManager( 4196): Download 257 starting
,W/ActivityThread( 4196): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/AlarmManager( 1018): sending alarm Alarm{43e42cf8 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{448330f8 type 0 com.android.vending}
,D/Finsky  ( 4161): [340] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4161): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{428d1790 u0 com.android.providers.downloads/.DownloadService}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1018): GC_EXPLICIT freed 1399K, 65% free 17869K/50140K, paused 5ms+12ms, total 107ms
,V/AlarmManager( 1018): sending alarm Alarm{448553a0 type 3 android}
,D/dalvikvm( 4196): GC_EXPLICIT freed 1806K, 44% free 9698K/17224K, paused 2ms+6ms, total 62ms
,D/Checkin ( 4196): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4196): Download 257 finished with status SUCCESS
,D/Finsky  ( 4161): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
,D/Finsky  ( 4161): [1] DownloadQueueImpl.notifyProgress: com.google.android.gms: onProgress 21130562/21130562 Status: 200.
,D/Finsky  ( 4161): [1] DownloadImpl.setState: com.google.android.gms from 2 to 3.
,D/Finsky  ( 4161): [1] DownloadQueueImpl.onComplete: com.google.android.gms: onComplete
,D/Finsky  ( 4161): [1] DownloadQueueImpl.remove: Download com.google.android.gms removed from DownloadQueue
,I/installd(  280): free_cache(0) avail 4739424256
,D/Finsky  ( 4161): [1] InstallerTask.advanceState: Prepare to patch com.google.android.gms (com.google.android.gms) from content://downloads/my_downloads/257 format 2
,V/Herrevad( 1372): NQAS connected
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/Finsky  ( 4161): [342] InstallerTask$8.doInBackground$1a3e6397: Patch apply task for com.google.android.gms (com.google.android.gms) (format 2) completed in -4550 ms
,D/Finsky  ( 4161): [1] InstallerTask$8.onPostExecute: Successfully applied patch to update com.google.android.gms (com.google.android.gms)
,D/Finsky  ( 4161): [1] InstallerTask.advanceState: Begin install of com.google.android.gms
,I/LaunchCheckinHandler( 1018): cleanup(): cleared. Last call was 75703 ms ago
,I/ActivityManager( 1018): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4353 uid=10013 gids={50013, 1028, 1015, 1023, 2001, 1035}
,W/ActivityManager( 1018): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/copies/com.google.android.gms-1515495223.apk
,D/Finsky  ( 4161): [1] PackageVerificationReceiver.onReceive: Skipping verification because own installation
,D/Finsky  ( 4161): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,W/ActivityManager( 1018): No content provider found for permission revoke: file:///data/data/com.android.vending/cache/copies/com.google.android.gms-1515495223.apk
,I/PackageManager( 1018): Copying native libraries to /data/app-lib/vmdl-1515495223
,W/Resources( 1018): Converting to boolean: TypedValue{t=0x3/d=0x21cc "false" a=2 r=0x7f120ac5}
,W/ResourceType( 1018): Failure getting entry for 0x7f1303bb (t=18 e=955) in package 0 (error -75)
,D/dalvikvm( 1018): GC_CONCURRENT freed 1027K, 62% free 19053K/50140K, paused 11ms+7ms, total 90ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 1607K, 61% free 19966K/50140K, paused 4ms+8ms, total 82ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 67ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 1492K, 58% free 21221K/50140K, paused 4ms+7ms, total 92ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 77ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3149K, 58% free 21130K/50140K, paused 4ms+7ms, total 94ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3008K, 58% free 21160K/50140K, paused 3ms+8ms, total 100ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 91ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3040K, 58% free 21165K/50140K, paused 4ms+8ms, total 93ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 84ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3017K, 58% free 21196K/50140K, paused 5ms+7ms, total 94ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3019K, 58% free 21225K/50140K, paused 4ms+8ms, total 95ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 84ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3038K, 58% free 21249K/50140K, paused 5ms+8ms, total 96ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 83ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3040K, 58% free 21274K/50140K, paused 3ms+8ms, total 98ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 89ms
,D/dalvikvm( 1018): GC_CONCURRENT freed 3057K, 58% free 21290K/50140K, paused 3ms+8ms, total 99ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 89ms
,I/ActivityManager( 1018): Force stopping com.google.android.gms appid=10022 user=-1: replace sys pkg
,I/ActivityManager( 1018): Killing 1200:com.google.android.gms.persistent/u0a22 (adj 1): stop com.google.android.gms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 1000ms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 10999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 20999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 30999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 40998ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 50998ms
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 60998ms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 70998ms
,I/ActivityManager( 1018): Killing 3976:com.google.android.gms.unstable/u0a22 (adj 13): stop com.google.android.gms
,I/ActivityManager( 1018): Killing 1372:com.google.android.gms/u0a22 (adj 8): stop com.google.android.gms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 80994ms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 90994ms
,I/ActivityManager( 1018): Killing 1354:com.google.process.gapps/u0a22 (adj 0): stop com.google.android.gms
,W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 100989ms
I/ActivityManager( 1018):   Force stopping service ServiceRecord{43ebf498 u0 com.google.android.gms/com.google.android.location.geocode.GeocodeService}
,I/ActivityManager( 1018):   Force stopping service ServiceRecord{42150f40 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{42246ae8 u0 com.google.android.gms/.analytics.service.AnalyticsService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{447b1278 u0 com.google.android.gms/com.google.android.location.fused.service.FusedProviderService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{4325bdb0 u0 com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{4257caa8 u0 com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{43ecbb58 u0 com.google.android.gms/com.google.android.location.network.NetworkLocationService}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{42216bb0 u0 com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService}
,I/ActivityManager( 1018):   Force stopping service ServiceRecord{420a94e8 u0 com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker}
I/ActivityManager( 1018):   Force stopping service ServiceRecord{4287e3c0 u0 com.google.android.gms/.common.stats.GmsCoreStatsService}
,I/ActivityManager( 1018):   Force stopping service ServiceRecord{42358418 u0 com.google.android.gms/.icing.service.IndexService}
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1018): Client connection lost with reason: 4
,D/WifiService( 1018): Client connection lost with reason: 4
,D/WifiService( 1018): Client connection lost with reason: 4
,W/PackageManager( 1018): Package com.google.android.gms desires unavailable shared library com.google.android.ble; ignoring!
W/PackageManager( 1018): Trying to update system app code path from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1018): Running dexopt on: com.google.android.gms
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,D/dalvikvm( 4397): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,D/dalvikvm( 4397): DexOpt: load 181ms, verify+opt 1074ms, 3080604 bytes
,W/PackageManager( 1018): Package com.google.android.gms declares lib com.google.android.gms that is not declared on system image; skipping
,I/ActivityManager( 1018): Force stopping com.google.android.gms appid=10022 user=-1: update pkg
,W/PackageManager( 1018): Code path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
,W/PackageManager( 1018): Resource path for pkg : com.google.android.gms changing from /data/app/com.google.android.gms-2.apk to /data/app/com.google.android.gms-1.apk
,W/PackageSettings( 1018): Skipping PackageSetting{4232ca48 com.example.hello/10442} due to missing metadata
,W/PackageManager( 1018): Unknown permission com.motorola.permission.AAB_LAUNCH_BROADCAST_PERMISSION in package com.android.contacts
,W/PackageManager( 1018): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
,W/PackageManager( 1018): Unknown permission com.motorola.permission.BROADCAST_MIP_ERROR in package com.android.phone
,W/PackageManager( 1018): Unknown permission android.permission.SYSTEM_ERROR_WINDOW in package com.motorola.demomode
W/PackageManager( 1018): Unknown permission android.permission.SYSTEM_OVERLAY_WINDOW in package com.motorola.demomode
W/PackageManager( 1018): Unknown permission android.permission.WRITE_SDCARD in package com.motorola.demomode
,W/PackageManager( 1018): Unknown permission com.motorola.android.permission.PORTALAPP_LOCAL in package com.motorola.demomode
W/PackageManager( 1018): Unknown permission com.motorola.audiomonitor.permission.RETAILMODE in package com.motorola.demomode
,W/PackageManager( 1018): Unknown permission com.motorola.audiomonitor.permission.STATE_CONTROL in package com.motorola.demomode
,W/PackageManager( 1018): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
,W/PackageManager( 1018): Not granting permission android.permission.READ_LOGS to package com.motorola.mesh (protectionLevel=50 flags=0x88be45)
,W/PackageManager( 1018): Unknown permission com.motorola.simulplay.logging in package com.motorola.mesh
,W/PackageManager( 1018): Unknown permission com.motorola.messaging.permission.MESSAGE_SETTINGS_PROVIDER in package com.motorola.programmenu
W/PackageManager( 1018): Unknown permission com.motorola.phoneaddons.permission.USE_PHONEADDON in package com.motorola.programmenu
W/PackageManager( 1018): Unknown permission android.permission.ACCESS_USB in package com.motorola.programmenu
,W/PackageManager( 1018): Unknown permission com.motorola.permission.ENTITLEMENT in package com.motorola.programmenu
,W/PackageManager( 1018): Unknown permission android.permission.INSTALL_DRM in package com.android.mms
,W/PackageManager( 1018): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.android.mms (protectionLevel=2 flags=0x4088be65)
W/PackageManager( 1018): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0xc9be45)
,W/PackageManager( 1018): Unknown permission com.google.android.gallery3d.permission.PICASA_STORE in package com.android.dreams.phototable
W/PackageManager( 1018): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager( 1018): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager( 1018): Not granting permission android.permission.DEVICE_POWER to package com.motorola.deviceauthenticator (protectionLevel=2 flags=0x40883e45)
,W/PackageManager( 1018): Unknown permission com.motorola.fingerprintsensor.permission.FINGERPRINT_SENSOR in package com.android.settings
,W/PackageManager( 1018): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager( 1018): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager( 1018): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager( 1018): Unknown permission com.google.android.ears.permission.WRITE in package com.google.android.googlequicksearchbox
W/PackageManager( 1018): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
,W/PackageManager( 1018): Unknown permission com.google.android.launcher.permission.CONTENT_REDIRECT in package com.google.android.googlequicksearchbox
W/PackageManager( 1018): Unknown permission com.motorola.permission.ACCESS_WIFI_AUTONOMOUS in package com.motorola.context
,W/PackageManager( 1018): Unknown permission com.motorola.slpc.permission.BIND_SERVICE in package com.motorola.context
,W/PackageManager( 1018): Unknown permission com.motorola.audiomonitor.permission.LOCAL in package com.motorola.contextual.smartrules2
,W/PackageManager( 1018): Unknown permission com.cequint.ecid.CALLER_ID_LOOKUP in package com.android.dialer
,W/PackageManager( 1018): Unknown permission com.motorola.driveactivator.ACCESS_CIDBLOCK in package com.motorola.ccc.ota
,W/PackageManager( 1018): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
,W/PackageManager( 1018): Unknown permission com.motorola.permission.ACCESS_ADAM in package com.motorola.bach.modemstats
,W/PackageManager( 1018): Unknown permission com.motorola.permission.MODIFY_ADAM in package com.motorola.bach.modemstats
,W/PackageManager( 1018): Not granting permission android.permission.BIND_DEVICE_ADMIN to package com.motorola.ccc.devicemanagement (protectionLevel=2 flags=0x4088be45)
,W/PackageManager( 1018): Unknown permission com.motorola.permission.ACCESS_WIFI_AUTONOMOUS in package com.motorola.motocit
W/PackageManager( 1018): Unknown permission com.motorola.driveactivator.ACCESS_CIDBLOCK in package com.motorola.motocit
,W/PackageManager( 1018): Unknown permission android.permission.BODY_SENSORS in package com.motorola.motocit
W/PackageManager( 1018): Unknown permission com.motorola.permission.SET_NAVBAR_BACKGROUNDCOLOR in package com.motorola.MotGallery2
,W/PackageManager( 1018): Unknown permission com.motorola.blast.permission.TRIGGER_BLAST_ACTION in package com.motorola.MotGallery2
,W/PackageManager( 1018): Unknown permission com.motorola.permission.CONNMO_SETTINGS in package com.motorola.android.dm.service
W/PackageManager( 1018): Unknown permission com.motorola.permission.SET_NAVBAR_BACKGROUNDCOLOR in package com.motorola.camera
W/PackageManager( 1018): Unknown permission android.permission.MMS_PUSH in package org.codeaurora.bluetooth
,W/PackageManager( 1018): Unknown permission com.motorola.blur.service.email.Permissions.ACTION_SEND in package com.motorola.setup
W/PackageManager( 1018): Unknown permission com.motorola.blur.contacts.permission.SOCIAL_CONTACT_WRITE in package com.motorola.setup
W/PackageManager( 1018): Unknown permission com.motorola.blur.contacts.permission.SOCIAL_CONTACT_READ in package com.motorola.setup
W/PackageManager( 1018): Unknown permission android.permission.READ_OWNER_DATA in package com.motorola.setup
W/PackageManager( 1018): Unknown permission android.permission.WRITE_OWNER_DATA in package com.motorola.setup
,W/PackageManager( 1018): Unknown permission com.motorola.blur.service.email.Permissions.INTERACT in package com.motorola.setup
W/PackageManager( 1018): Unknown permission com.motorola.digitalpersonalization.permission.READ_CREDENTIALS in package com.motorola.setup
W/PackageManager( 1018): Unknown permission com.motorola.setupwizard.controller.permission.UPDATE_CONTROLLER in package com.motorola.setup
,W/PackageManager( 1018): Unknown permission com.motorola.setup.permission.REPORT_BUA_SYNC_STATUS in package com.motorola.setup
W/PackageManager( 1018): Unknown permission com.qualcomm.permission.ACCESS_LOCATION_API in package com.qualcomm.location
,W/PackageManager( 1018): Not granting permission android.permission.INTERACT_ACROSS_USERS_FULL to package com.motorola.onetimeinitializer (protectionLevel=2 flags=0x4088be45)
,W/PackageManager( 1018): Not granting permission com.android.gallery3d.filtershow.permission.READ to package com.google.android.apps.plus (protectionLevel=2 flags=0x98be45)
W/PackageManager( 1018): Not granting permission com.android.gallery3d.filtershow.permission.WRITE to package com.google.android.apps.plus (protectionLevel=2 flags=0x98be45)
W/PackageManager( 1018): Unknown permission com.google.android.gallery3d.permission.PICASA_STORE in package com.google.android.apps.plus
W/PackageManager( 1018): Unknown permission android.permission.REAL_GET_TASKS in package com.android.vending
,W/PackageManager( 1018): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x40cabec5)
W/PackageManager( 1018): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
,W/PackageManager( 1018): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager( 1018): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
,W/PackageManager( 1018): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=18 flags=0x40cabec5)
,W/PackageManager( 1018): Not granting permission android.permission.FORCE_STOP_PACKAGES to package com.android.vending (protectionLevel=18 flags=0x40cabec5)
,W/PackageManager( 1018): Unknown permission com.motorola.digitalpersonalization.permission.READ_CREDENTIALS in package com.motorola.ccc.cce
,W/PackageManager( 1018): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0x98be45)
W/PackageManager( 1018): Not granting permission android.permission.DEVICE_POWER to package com.android.deskclock (protectionLevel=2 flags=0x40c8be45)
,W/PackageManager( 1018): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
,W/PackageManager( 1018): Unknown permission motorola.sprint.permission.READ_OMADM_RUNTIME_DATA in package com.android.keyguard
W/PackageManager( 1018): Unknown permission motorola.sprint.permission.WRITE_OMADM_RUNTIME_DATA in package com.android.keyguard
W/PackageManager( 1018): Unknown permission com.motorola.fingerprintsensor.permission.FINGERPRINT_SENSOR in package com.android.keyguard
W/PackageManager( 1018): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
,W/PackageManager( 1018): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
,W/PackageManager( 1018): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.RECOVERY in package com.google.android.gms
W/PackageManager( 1018): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40483ec5)
W/PackageManager( 1018): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
,W/PackageManager( 1018): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
,W/PackageManager( 1018): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40483ec5)
W/PackageManager( 1018): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
,W/PackageManager( 1018): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
,W/PackageManager( 1018): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager( 1018): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
,W/PackageManager( 1018): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
,W/PackageManager( 1018): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
,W/PackageSettings( 1018): Skipping PackageSetting{4232ca48 com.example.hello/10442} due to missing metadata
,I/ActivityManager( 1018): Force stopping com.google.android.gms appid=10022 user=0: pkg removed
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/dalvikvm( 1299): GC_EXPLICIT freed 2891K, 33% free 11592K/17224K, paused 2ms+12ms, total 91ms
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/dalvikvm( 2160): GC_EXPLICIT freed 2672K, 44% free 9777K/17224K, paused 4ms+4ms, total 113ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
W/Babel   ( 4086): Gms package replaced. Will trigger a restart of babel
I/Launcher( 1299): Deferring update until onResume
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1018):   Scheme: "sms"
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/ActivityManager( 1018): Start proc com.google.android.gms.persistent for service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker: pid=4410 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,E/MC_Service( 2129): java.lang.IllegalArgumentException: PackageInfoTrigger has invalid state data (8.4.89 (2428711-036)). State keys and values cannot contain the following characters: space, =, ", ', \
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10022 #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1018):   Scheme: "sms"
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4423 uid=10059 gids={50059, 3003, 1028, 1015}
,V/BackupManagerService( 1018): addPackageParticipantsLocked: #1
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
W/dalvikvm( 4410): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 4410): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4410): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4410): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x00cd
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/MultiDex( 4410): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4410): install
,I/MultiDex( 4410): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/MultiDex( 4410): Detected that extraction must be performed.
,I/Launcher( 1299): Deferring update until onResume
,I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes1930325867.zip of size 1659457
,I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes1930325867.zip
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-1235589675.zip of size 258077
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-1235589675.zip
,I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip of size 2442399
,I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-2086212682.zip of size 1187840
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes-2086212682.zip
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip of size 2874084
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.dex of size 6208584
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.dex
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.dex of size 8190232
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.dex
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip of size 2912239
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip
I/MultiDex( 4410): Trying to delete old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.dex of size 7647216
I/MultiDex( 4410): Deleted old file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.dex
,D/dalvikvm( 1018): GC_EXPLICIT freed 3312K, 59% free 21058K/50140K, paused 5ms+29ms, total 171ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 60ms
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/Finsky  ( 4161): [320] PackageManagerHelper$OnCompleteListenerNotifier$1.packageInstalled: Package install status for com.google.android.gms is 1
,I/MultiDex( 4410): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4410): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-344736367.zip
,D/Finsky  ( 4161): [1] InstallerTask$3.installSucceeded: Successful install of com.google.android.gms
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4161): Failed to ensure directory: /storage/sdcard1/Android/data/com.android.vending/files
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/ActiveOrDefaultContextProvider( 4423): Missing scope.enter somewhere. Returning default context
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ActivityManager( 1018): Start proc com.google.android.gms for service com.google.android.gms/.people.sync.metadata.ContactMetadataSyncService: pid=4440 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/GAV2    ( 4423): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4458 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/dalvikvm(  277): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,W/dalvikvm( 4440): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4440): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4440): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4440): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x00cd
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
I/MultiDex( 4440): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4440): install
,I/MultiDex( 4440): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4440): Detected that extraction must be performed.
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
W/ContextImpl( 4458): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ActivityManager( 1018): Killing 3905:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MultiDex( 4440): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4440): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes1085468526.zip
,W/GAV2    ( 4423): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1018): Killing 4196:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1786): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:517 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/MultiDex( 4440): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4440): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip: 2898044
I/MultiDex( 4440): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4440): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1515495223.zip
,I/MultiDex( 4410): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip
,I/MultiDex( 4410): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip: 2898044
,I/MultiDex( 4410): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4410): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes1085468526.zip
,I/GAV2    ( 4423): Thread[GAThread,5,main]: No campaign data found.
,I/MultiDex( 4440): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
,I/MultiDex( 4440): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip: 3409737
I/MultiDex( 4440): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4440): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-137889796.zip
,I/MultiDex( 4410): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip
I/MultiDex( 4410): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip: 3409737
,I/MultiDex( 4410): Extraction is needed for file /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4410): Extracting /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes-1515495223.zip
,I/MultiDex( 4440): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4440): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip: 2767034
,I/MultiDex( 4440): load found 3 secondary dex files
,D/dalvikvm( 4440): DexOpt: --- BEGIN 'com.google.android.gms-1.apk.classes2.zip' (bootstrap=0) ---
,I/MultiDex( 4410): Renaming to /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip
,I/MultiDex( 4410): Extraction success - length /data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip: 2767034
,I/MultiDex( 4410): load found 3 secondary dex files
,D/dalvikvm( 4410): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.dex)
,D/dalvikvm( 4514): GC_FOR_ALLOC freed 671K, 33% free 1376K/2048K, paused 5ms, total 5ms
,D/dalvikvm( 4514): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,D/dalvikvm( 4514): DexOpt: load 300ms, verify+opt 751ms, 5344452 bytes
,D/dalvikvm( 4440): DexOpt: --- END 'com.google.android.gms-1.apk.classes2.zip' (success) ---
,D/dalvikvm( 4440): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip': unzip in 198ms, rewrite 1629ms
,D/dalvikvm( 4410): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.dex)
,D/dalvikvm( 4440): DexOpt: --- BEGIN 'com.google.android.gms-1.apk.classes3.zip' (bootstrap=0) ---
,D/dalvikvm( 4517): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
,D/dalvikvm( 4517): GC_FOR_ALLOC freed 728K, 36% free 1319K/2048K, paused 5ms, total 5ms
,D/dalvikvm( 4517): DexOpt: load 277ms, verify+opt 1099ms, 5204164 bytes
,D/dalvikvm( 4440): DexOpt: --- END 'com.google.android.gms-1.apk.classes3.zip' (success) ---
,D/dalvikvm( 4440): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip': unzip in 217ms, rewrite 2182ms
,D/dalvikvm( 4410): DexOpt: sleeping on flock(/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.dex)
,D/dalvikvm( 4440): DexOpt: --- BEGIN 'com.google.android.gms-1.apk.classes4.zip' (bootstrap=0) ---
,D/dalvikvm( 4518): DexOpt: load 235ms, verify+opt 852ms, 4624716 bytes
,D/dalvikvm( 4440): DexOpt: --- END 'com.google.android.gms-1.apk.classes4.zip' (success) ---
,D/dalvikvm( 4440): DEX prep '/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip': unzip in 177ms, rewrite 1784ms
,I/MultiDex( 4440): install done
,I/MultiDex( 4410): install done
,I/ActivityManager( 1018): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4520 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,V/AlarmManager( 1018): sending alarm Alarm{43e9aec0 type 0 com.android.vending}
,I/GservicesProvider( 4520): Gservices pushing to system: true; secure/global: true
,D/dalvikvm( 4161): GC_CONCURRENT freed 1547K, 10% free 15755K/17352K, paused 3ms+6ms, total 56ms
,D/dalvikvm( 4161): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4440): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4410): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4410): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4410): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4410): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4410): VFY: unable to resolve instance field 36
,D/dalvikvm( 4410): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4440): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4440): VFY: unable to resolve instance field 36
D/dalvikvm( 4440): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4410): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4410): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4410): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
D/dalvikvm( 4410): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 4410): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
W/dalvikvm( 4440): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4440): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4440): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4410): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42075770
,D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42081bf8
D/dalvikvm( 4410): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42075770
,D/dalvikvm( 4410): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42075770, skipping init
D/dalvikvm( 4440): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42081bf8
D/dalvikvm( 4440): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42081bf8, skipping init
,D/dalvikvm( 4410): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42075770
D/dalvikvm( 4410): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42075770
D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42081bf8
V/JNIHelp ( 4410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 4440): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42081bf8
,V/JNIHelp ( 4440): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42081bf8
,D/dalvikvm( 4440): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42081bf8
D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42081bf8
,D/dalvikvm( 4440): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42081bf8
,D/dalvikvm( 4410): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42075770
,D/dalvikvm( 4410): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42075770
D/dalvikvm( 4410): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42075770
,D/dalvikvm( 4410): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42075770
,W/dalvikvm( 4520): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4520): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 4520): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4520): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4520): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4520): install
,I/MultiDex( 4520): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4520): loading existing secondary dex files
,I/ProviderInstaller( 4440): Installed default security provider GmsCore_OpenSSL
,I/MultiDex( 4520): load found 3 secondary dex files
,I/MultiDex( 4520): install done
,D/dalvikvm( 4520): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4520): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4520): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4520): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4520): VFY: unable to resolve instance field 36
,D/dalvikvm( 4520): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4520): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4520): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4520): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4520): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4520): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4520): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42074e50
,D/dalvikvm( 4520): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42074e50
D/dalvikvm( 4520): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42074e50, skipping init
,D/dalvikvm( 4520): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42074e50
D/dalvikvm( 4520): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42074e50
,V/JNIHelp ( 4520): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm( 4440): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4440): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4440): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x000d
,I/ProviderInstaller( 4410): Installed default security provider GmsCore_OpenSSL
,D/NativeLibraryUtils( 4410): Installer failed to acquire lock.
D/NativeLibraryUtils( 4410): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4410): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 4410): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:177)
D/NativeLibraryUtils( 4410): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:587)
D/NativeLibraryUtils( 4410): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 4410): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 4410): Caused by: libcore.io.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4410): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 4410): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:54)
D/NativeLibraryUtils( 4410): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 4410): 	... 4 more
,E/ActivityThread( 4440): Failed to find provider info for com.android.contacts.metadata
,I/GAv4-SVC( 4440): Google Analytics 8.4.89 is starting up.
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 498497, reason: ServiceChanged
,D/dalvikvm( 4520): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42074e50
,D/dalvikvm( 4520): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42074e50
D/dalvikvm( 4520): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42074e50
,D/dalvikvm( 4520): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42074e50
,I/dalvikvm( 4410): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4410): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4410): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4410): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4410): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4410): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4410): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4410): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/dalvikvm( 4410): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4410): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4410): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x000d
,D/DeviceConnectionService( 4410): client connected with version: 8296000
,I/dalvikvm( 4410): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method com.google.android.location.util.ao.c
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1379: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x000c
,I/ProviderInstaller( 4520): Installed default security provider GmsCore_OpenSSL
,I/GCoreNlp( 4410): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/dalvikvm( 4520): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x001c
,D/NativeLibraryUtils( 4520): Installer failed to acquire lock.
D/NativeLibraryUtils( 4520): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4520): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 4520): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:177)
D/NativeLibraryUtils( 4520): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:587)
D/NativeLibraryUtils( 4520): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 4520): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 4520): Caused by: libcore.io.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 4520): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 4520): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:54)
D/NativeLibraryUtils( 4520): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 4520): 	... 4 more
,D/NativeLibraryUtils( 4440): Install completed successfully. count=14 extracted=0
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4520): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 4520): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x000d
,D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.gms
,D/ChimeraCfgMgr( 4440): Reading stored module config
,I/PackageBroadcastService( 4440): Null package name or gms related package.  Ignoreing.
,W/ChimeraCfgMgr( 4440): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/ChimeraCfgMgr( 4440): Reading stored module config
,W/ChimeraCfgMgr( 4440): Stored Chimera config has different version (current=2,stored=1), ignoring
I/dalvikvm( 4520): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x001f
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 4440): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 4440): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 4440): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4440): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4440): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 4440): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 4440): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 4440): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 4440): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,I/dalvikvm( 4520): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.e.b.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x000e
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 4520): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4520): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4520): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4520): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x00bb
,I/dalvikvm( 4520): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4520): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4520): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0041
,I/dalvikvm( 4520): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 4520): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0046
,I/dalvikvm( 4410): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x003e
,D/WearableService( 4410): callingUid 10022, callindPid: 4410
E/dalvikvm( 4410): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4410): VFY: unable to resolve check-cast 516 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4410): VFY: replacing opcode 0x1f at 0x0054
W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
,D/ChimeraCfgMgr( 4440): Reading stored module config
,E/GmsWearableNodeHelper( 4410): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ChimeraCfgMgr( 4440): Stored Chimera config has different version (current=2,stored=1), ignoring
,D/ChimeraModuleApk( 4440): Loading chimera manifest from InstalledApk(com.google.android.play.games)
,D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 4440): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
,D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.maps,v8301000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk)
,D/ChimeraModuleApk( 4440): Loading chimera manifest from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 4440): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
,D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 4440): Beginning module config resolution
D/ChimeraCfgRslvr( 4440): module(built-in,v0) has no external dependencies, accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.cast,v1) accepted
,D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.games,v34120000) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.maps,v8301000) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.piccard,v1) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 4440): Module config resolution complete
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Loading module APK com.google.android.play.games
,I/dalvikvm( 4440): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 4440): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 4440): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 4440): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 4440): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 4440): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,I/dalvikvm( 4440): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 4440): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x002b
,D/GCM     ( 4520): COMPAT: Multi user not supported
,D/dalvikvm( 4520): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 4520): VFY: unable to resolve instance field 161
,D/dalvikvm( 4520): VFY: replacing opcode 0x52 at 0x0006
,D/dalvikvm( 4440): Trying to load lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42081bf8
,I/dalvikvm( 4520): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 4520): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 4440): Added shared lib /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42081bf8
,D/dalvikvm( 4440): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libAppDataSearch.so 0x42081bf8, skipping init
,I/dalvikvm( 4520): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0010
,I/dalvikvm( 4440): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
,W/dalvikvm( 4440): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0010
,E/NetworkScheduler.SchedulerReceiver( 4520): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 4520): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/Babel   ( 4086): Gms package replaced. Will trigger a restart of babel
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4589 uid=10025 gids={50025, 3003}
,I/Icing   ( 4440): Storage manager: low false usage 1.99MB avail 4.41GB capacity 5.52GB
,I/InternalIcingCorporaPro( 2160): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/dalvikvm( 4440): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4440): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4440): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4440): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4440): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4440): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4440): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4440): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/dalvikvm( 4440): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0029
I/ActivityManager( 1018): Killing 4353:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4161): [1] GmsCoreHelper$GMSCoreNotifier$1.run: Set autoupdate of com.google.android.gms to 1 (install/update)
,W/Babel   ( 4086): Gms package replaced. Will trigger a restart of babel
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=4615 uid=10076 gids={50076, 3003, 1028, 1015}
,W/IcingInternalCorpora( 4440): getNumBytesRead when not calculated.
,V/WebViewChromiumFactoryProvider( 4615): Binding Chromium to main looper Looper (main, tid 1) {42069cd0}
,I/LibraryLoader( 4615): Expected native library version number "",actual native library version number ""
,I/chromium( 4615): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4615): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4615): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4615): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4615): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4615): Local Branch: 
I/Adreno-EGL( 4615): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4615): Local Patches: NONE
I/Adreno-EGL( 4615): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
I/qtaguid ( 4161): Failed write_ctrl(u 67) res=-1 errno=22
I/qtaguid ( 4161): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4161): untagSocket(67) failed with errno -22
,D/Finsky  ( 4161): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
,D/Finsky  ( 4161): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1018): Killing 4458:com.android.keychain/1000 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/chromium( 4615): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4615): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4615): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm( 4440): Total arena pages for JIT: 11
,I/dalvikvm( 4440): Total arena pages for JIT: 12
I/dalvikvm( 4440): Total arena pages for JIT: 13
,I/dalvikvm( 4440): Total arena pages for JIT: 14
,I/NSApplication( 4615): Starting up...
,I/ActivityManager( 1018): Killing 4589:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.gms
,I/Icing   ( 4440): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1018): GC_EXPLICIT freed 4519K, 65% free 17917K/50128K, paused 5ms+9ms, total 104ms
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
D/ChimeraCfgMgr( 4440): Module APKs unchanged, check complete
,I/PackageBroadcastService( 4440): Null package name or gms related package.  Ignoreing.
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4440): Submit a task: k
I/dalvikvm( 4440): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 4440): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 4440): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 4520): GC_EXPLICIT freed 1734K, 42% free 10115K/17224K, paused 2ms+4ms, total 31ms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4440): Processing package: com.google.android.gms
,D/d       ( 4440): Database will be upgraded from 1 to 2
,D/d       ( 4440): Database upgraded to 2
,D/b       ( 4440): Look up (com.google.android.gms:8489036) returned no result
,D/k       ( 4440): Starting Hash for package com.google.android.gms:8.4.89 (2428711-036)
,D/FileApkUtils( 4440): Spent 85ms computing apk sha1.
,D/dalvikvm( 4440): GC_EXPLICIT freed 4488K, 32% free 11845K/17224K, paused 4ms+16ms, total 82ms
,I/Icing   ( 4440): Removing corpus key 35B2C5A8CE535741260EC99169D5C2AD9821FC7E for package com.google.android.gms
,W/InstanceID/Rpc( 4440): Found 10022
,D/FileApkUtils( 4440): Spent 106ms copying apk.
,D/FileApkUtils( 4440): Copied dynamite bytes to /data/data/com.google.android.gms/app_chimera/chimera-module-root/scratch-module-dir/MapsModule.apk
,E/NetworkScheduler.SchedulerReceiver( 4520): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 4520): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/FileApkUtils( 4440): Spent 17ms extracting native libraries.
,W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DexOptUtils( 4440): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 4440): Pre-lollipop platform, odex will live alongside the dex.
D/DexOptUtils( 4440): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 4440): Primary ABI of odexing process is armeabi-v7a
,W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4410): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 4410): Using platform SSLCertificateSocketFactory
,W/InstanceID/Rpc( 4520): Found 10022
,I/dalvikvm( 4410): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.tapandpay.j.f.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1401: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0037
,I/PhenotypeConfigurator( 4410): Scheduling Phenotype for one-off execution 6888 seconds from now (1449671620999)
,W/InstanceID/Rpc( 4410): Found 10022
,D/dalvikvm( 4440): DexOpt: --- BEGIN 'MapsModule.apk' (bootstrap=0) ---
,D/dalvikvm( 4520): GC_EXPLICIT freed 323K, 42% free 10104K/17224K, paused 2ms+4ms, total 27ms
,D/WifiService( 1018): New client listening to asynchronous messages
,E/DynamiteModule( 4440): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4440): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 4440): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4440): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 4440): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 4440): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4440): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4440): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4440): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4440): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4440): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:72)
E/DynamiteModule( 4440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DynamiteModule( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4440): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 4440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DynamiteModule( 4440): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4440): Selected local version of com.google.android.gms.flags
I/dalvikvm( 4440): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.stats.PlatformStatsCollectorService.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1512: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0070
,I/PlatformStatsCollectorService( 4440): Start Settingsstats in 1633 seconds.
,I/PlatformStatsCollectorService( 4440): Start Dropbox in 12983 seconds.
,I/PlatformStatsCollectorService( 4440): Start Graphicsstats in 62505 seconds.
,I/PlatformStatsCollectorService( 4440): Start Fingerprintstats in 16436 seconds.
,I/PlatformStatsCollectorService( 4440): Start Procstats in 70648 seconds.
,I/PlatformStatsCollectorService( 4440): Start Diskstats in 13574 seconds.
,I/PlatformStatsCollectorService( 4440): Start Notificationstats in 47261 seconds.
,D/dalvikvm( 4440): GC_CONCURRENT freed 3122K, 38% free 10779K/17224K, paused 3ms+6ms, total 47ms
,I/PlatformStatsCollectorService( 4440): Start Netstats in 65865 seconds.
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PerfProfileCollectorService( 4440): Scheduling Perf Profile Collection every 86400 seconds
,I/StatsUploadService( 4440): Turn off alarms uploading
,I/StatsUploadService( 4440): Turn off networkusage uploading
,I/StatsUploadService( 4440): Turn off wakelocks uploading
,I/StatsUploadService( 4440): Turn off internal_service_connections uploading
,I/dalvikvm( 4440): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1203: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x003e
,E/MDM     ( 4410): [349] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 4520): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/dalvikvm( 4520): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x002f
,E/AuthorizationBluetoothService( 4520): Proximity feature is not enabled.
,I/dalvikvm( 4410): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0010
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Scheduler( 4440): Use legacy PeriodicScheduler
,I/Icing   ( 4440): Internal init done: storage state 0
,D/WifiService( 1018): New client listening to asynchronous messages
,D/dalvikvm( 4440): GC_CONCURRENT freed 2017K, 38% free 10809K/17224K, paused 6ms+4ms, total 34ms
D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
,D/FileApkUtils( 4440): Ignoring module currently being optimized: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
,D/ChimeraCfgMgr( 4440): Module APKs unchanged, check complete
,E/dalvikvm( 4440): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 4440): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 4440): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 4440): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 4440): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 4440): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 4440): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 4440): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4440): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 4440): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/dalvikvm( 4520): GC_EXPLICIT freed 233K, 42% free 10106K/17224K, paused 2ms+7ms, total 33ms
,I/Icing   ( 4440): Post-init done
,I/Icing   ( 4440): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Auth    ( 4520): [Change,LoginAccountsChangedIntentService] LoginAccountsChangedIntentService received unknown action: com.google.android.gms.auth.change.REFRESH
,V/AuthZen ( 4440): Handling intent: com.google.android.gms.GMS_UPDATED
,D/GCM     ( 4440): COMPAT: Multi user not supported
,D/WifiService( 1018): New client listening to asynchronous messages
,D/AuthZenEventHandler( 4440): Handling event: com.google.android.gms.GMS_UPDATED
,I/dalvikvm( 4520): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 4520): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0059
,I/dalvikvm( 4520): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 4520): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x0022
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/PeopleDatabaseHelper( 4440): Upgrading from version 700 to 1405
I/dalvikvm( 4440): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x00bb
,E/BaseAppContext( 4440): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/GCM     ( 4520): GcmService start Intent { act=com.google.android.gms.GMS_UPDATED cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.GMS_UPDATED
E/dalvikvm( 4410): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 4410): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 4410): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 4410): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 4410): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 4410): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm( 4410): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 4410): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 4410): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,D/GCM     ( 4520): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/dalvikvm( 4440): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
,W/dalvikvm( 4440): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x002f
,I/GCM     ( 4520): GCM config loaded
,I/AuthZen ( 4440): Fetching signing key...
,I/DatabaseHelper( 4410): Upgrade database: oldVersion=3 newVersion=4
,I/DatabaseHelper( 4410): Indexing LogEvents by PlayLoggerContext id
,D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4219f480:true
,I/AuthZen ( 4440): Signing key fetched successfully!
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 4440): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 4440): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 4440): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 4440): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 4440): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 4440): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 4440): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 4440): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 4440): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0006
E/MDM     ( 4410): [362] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/dalvikvm( 4440): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 4440): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0006
,D/AuthorizationBluetoothService( 4520): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4520): Proximity feature is not enabled.
,I/PeopleDatabaseHelper( 4440): cleanUpNonGplusAccounts done.
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LocationInitializer( 4440): Initializing location.
,D/LocationInitializer( 4440): Location services disabled.
,I/PeopleSync( 4440): requestContactSyncCleanup [5005f081]
,D/dalvikvm( 4410): GC_EXPLICIT freed 3008K, 38% free 10785K/17224K, paused 6ms+7ms, total 52ms
,E/MDM     ( 4410): [363] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Scheduler( 4410): Use legacy PeriodicScheduler
,D/AuthorizationBluetoothService( 4520): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4520): Proximity feature is not enabled.
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
,D/FileApkUtils( 4440): Ignoring module currently being optimized: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
,D/SystemEventReceiver( 4440): Received GMS_UPDATE broadcast
,D/ChimeraCfgMgr( 4440): Module APKs unchanged, check complete
,I/GCM     ( 4520): Ack for not saved message 23
,I/OcrUtils( 4440): Updating ocr activity enabled=false
,V/GMPM-SVC( 4440): Update service enabled state to: 1
,I/dalvikvm( 4410): Total arena pages for JIT: 11
,I/dalvikvm( 4410): Total arena pages for JIT: 12
I/dalvikvm( 4410): Total arena pages for JIT: 13
,I/dalvikvm( 4410): Total arena pages for JIT: 14
,D/dalvikvm( 4440): GC_CONCURRENT freed 1731K, 36% free 11131K/17224K, paused 4ms+6ms, total 46ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/k       ( 4440): Package com.google.android.gms's hash: a05ba025b6e6b4a49692d64a578be94965f04b9c510b10e0363a9fa4f9300b4e
,D/b       ( 4440): Look up (com.google.android.gms:8489036) returned no result
,I/PlatformStatsCollectorService( 4440): Start Settingsstats in 50049 seconds.
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlatformStatsCollectorService( 4440): Start Dropbox in 56925 seconds.
,D/k       ( 4440): Saved the app info in cache for package:com.google.android.gms.
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PlatformStatsCollectorService( 4440): Start Graphicsstats in 52949 seconds.
,I/dalvikvm( 4440): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x003d
E/dalvikvm( 4440): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 4440): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 4440): VFY: replacing opcode 0x1f at 0x000e
,I/PlatformStatsCollectorService( 4440): Start Fingerprintstats in 80436 seconds.
,I/PlatformStatsCollectorService( 4440): Start Procstats in 64351 seconds.
,I/PeopleSync( 4440): onPerformSync() [5005f081]
,I/PlatformStatsCollectorService( 4440): Start Diskstats in 76327 seconds.
,I/PlatformStatsCollectorService( 4440): Start Notificationstats in 28642 seconds.
,I/PlatformStatsCollectorService( 4440): Start Netstats in 16792 seconds.
,D/dalvikvm( 4520): GC_EXPLICIT freed 1053K, 41% free 10286K/17224K, paused 2ms+4ms, total 29ms
,D/c       ( 4440): Creating table: affiliation
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 4440): Will schedule periodic tasks:com.google.android.gms.GMS_UPDATED.
D/BootCompletedReceiver( 4440): Got a GmsCore update event.
,D/BootCompletedReceiver( 4440): Will NOT schedule AdAttestation signal task because it's disabled.
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gms.GMS_UPDATED pkg=com.google.android.gms } U=0: not found
,I/MDM     ( 4440): [413] SitrepService.onHandleIntent: sending sitrep: [6, 0, [DN43wt_LF108D2Xi6YQLizUZFb8], null]
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,D/dalvikvm( 4440): GC_CONCURRENT freed 1939K, 35% free 11242K/17224K, paused 3ms+10ms, total 44ms
,I/PhenotypeConfigurator( 4410): Scheduling Phenotype for one-off execution 3487 seconds from now (1449671622700)
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/OcrModelManager( 4440): Updating downloaded model state (gcore updated)
,D/AuthorizationBluetoothService( 4520): Received GmsCore event: Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 4520): Proximity feature is not enabled.
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 4440): [413] a.<init>: mAccountName set to: thalitester@gmail.com
,I/PerfProfileCollectorService( 4440): Scheduling Perf Profile Collection every 86400 seconds
,W/ActivityManager( 1018): Unable to start service Intent { act=INITIALIZE_SUBSCRIPTIONS cmp=com.google.android.gms/.nearby.sharing.NearbySharingIntentService } U=0: not found
I/dalvikvm( 4440): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 4440): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0053
,D/dalvikvm( 1018): GC_EXPLICIT freed 1576K, 64% free 18048K/50128K, paused 4ms+12ms, total 140ms
,W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.google.android.gms.GMS_UPDATED flg=0x10 pkg=com.google.android.gms } from com.android.vending (pid=4161, uid=10038) is not exported from uid 10022 due to receiver com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
I/PeopleSync( 4440): Setting subscription: result=true [5005f081]
I/PeopleSync( 4440): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,I/PhenotypeConfigurator( 4440): Scheduling Phenotype for one-off execution 3197 seconds from now (1449671622833)
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1287): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1287): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1287): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WearInitializer( 4440): Running WearInitializer
D/WearInitializer( 4440): enabled .WearableService
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,W/BaseAppContext( 4440): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 4440): CP2 sync start [5005f081]
,W/IcingInternalCorpora( 4440): getNumBytesRead when not calculated.
,D/LocationInitializer( 4440): Restart initialization of location
,E/dalvikvm( 4440): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
W/dalvikvm( 4440): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/dalvikvm( 4440): VFY: replacing opcode 0x1f at 0x0035
,W/dalvikvm( 4520): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 4520): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 4520): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 4520): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 4520): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4520): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4520): VFY: replacing opcode 0x6e at 0x003d
,D/LocationInitializer( 4440): Restart initialization of location
,D/LocationInitializer( 4440): Restart initialization of location
,D/dalvikvm( 4440): GC_CONCURRENT freed 1764K, 33% free 11552K/17224K, paused 5ms+7ms, total 60ms
,W/IcingInternalCorpora( 4440): getNumBytesRead when not calculated.
,I/dalvikvm( 4410): Failed resolving Lcom/google/android/gms/common/util/bo; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
E/dalvikvm( 4410): Could not find class 'com.google.android.gms.common.util.bo', referenced from method com.google.android.gms.common.util.bm.a
W/dalvikvm( 4410): VFY: unable to resolve new-instance 2494 (Lcom/google/android/gms/common/util/bo;) in Lcom/google/android/gms/common/util/bm;
,D/dalvikvm( 4410): VFY: replacing opcode 0x22 at 0x0010
I/dalvikvm( 4410): Failed resolving Lcom/google/android/gms/common/util/bo; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4410): Link of class 'Lcom/google/android/gms/common/util/bo;' failed
,D/dalvikvm( 4410): DexOpt: unable to opt direct call 0x3205 at 0x16 in Lcom/google/android/gms/common/util/bm;.a
,E/dalvikvm( 4410): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm( 4410): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 4410): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 4410): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 4410): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 4674): DexOpt: load 128ms, verify+opt 1816ms, 1991636 bytes
,I/PeopleContactsSync( 4440): CP2 cleanup done, kept= duration=287 ms
,D/dalvikvm( 4520): null clazz in OP_INSTANCE_OF, single-stepping
,E/dalvikvm( 4410): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.gms.lockbox.LockboxService.a
W/dalvikvm( 4410): VFY: unable to resolve check-cast 61 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/gms/lockbox/LockboxService;
,D/dalvikvm( 4410): VFY: replacing opcode 0x1f at 0x0035
,D/dalvikvm( 4440): DexOpt: --- END 'MapsModule.apk' (success) ---
,D/dalvikvm( 4440): DEX prep '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': unzip in 99ms, rewrite 2308ms
D/DexOptUtils( 4440): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.dex
D/DexOptUtils( 4440): Set odex to world readable.
,D/DexOptUtils( 4440): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.odex
D/FileApkUtils( 4440): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/FileApkUtils( 4440): Deleting stale module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,I/PeopleContactsSync( 4440):   updateBabelActionMimeType
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
,D/ChimeraModuleApk( 4440): Loading chimera manifest from InstalledApk(com.google.android.play.games)
,D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.games,v34120000) from InstalledApk(com.google.android.play.games)
,D/ChimeraFileApk( 4440): Loading chimera manifest from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
,D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.maps,v8489000) from FileApk(/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk)
D/ChimeraModuleApk( 4440): Loading chimera manifest from ContainerApk(com.google.android.gms)
I/dalvikvm( 4410): Could not find method android.accounts.AccountManager.getPreviousName, referenced from method com.google.android.location.util.c.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 11: Landroid/accounts/AccountManager;.getPreviousName (Landroid/accounts/Account;)Ljava/lang/String;
D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x000a
D/ChimeraCfgMgr( 4440): Considering module(built-in,v0) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.cast,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.games,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.gass,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.kids,v3) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.piccard,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgMgr( 4440): Considering module(com.google.android.gms.vision,v1) from ContainerApk(com.google.android.gms)
D/ChimeraCfgRslvr( 4440): Beginning module config resolution
,D/ChimeraCfgRslvr( 4440): module(built-in,v0) has no external dependencies, accepted
,D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.cast,v1) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.games,v34120000) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.gass,v1) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.kids,v3) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.maps,v8489000) accepted
D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.piccard,v1) accepted
,D/ChimeraCfgRslvr( 4440): module(com.google.android.gms.vision,v1) accepted
,D/ChimeraCfgRslvr( 4440): Module config resolution complete
,I/PeopleContactsSync( 4440): Updated babel action mime type
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 4440): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/GeofencerStateMachine( 4410): Creating GeofencerStateMachine
,I/PeopleContactsSync( 4440): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/FileApkUtils( 4440): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 4440): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4440): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/GmsModuleFndr( 4440): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 4440): Beginning module configuration check
,D/ChimeraCfgMgr( 4440): Module APKs unchanged, check complete
,D/dalvikvm( 4520): GC_EXPLICIT freed 1076K, 40% free 10372K/17224K, paused 2ms+13ms, total 147ms
,W/InstanceID/Rpc( 4440): Found 10022
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,I/PeopleContactsSync( 4440): CP2 cleanup done, kept= duration=101 ms
,D/dalvikvm( 4410): GC_CONCURRENT freed 2156K, 39% free 10586K/17224K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 4440): GC_CONCURRENT freed 1888K, 32% free 11712K/17224K, paused 4ms+6ms, total 69ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/PeopleContactsSync( 4440): ===CP2 sync finished, success=true, time=746,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/dalvikvm( 4440): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.GmsNetworkTrafficStats.setThreadStatsTag
,W/dalvikvm( 4440): VFY: unable to resolve virtual method 1311: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 4410): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.location.util.k.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1377: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x000a
,I/dalvikvm( 4440): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
W/dalvikvm( 4440): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x000d
,V/AccountUtils( 4440): 0 accounts found with uca feature
,I/GamesSyncAdapter( 4440): Starting sync for 3a3529a
,V/GeofencerHelper( 4410): Initializing geofence's system cache.
,D/GeofenceStateCache( 4410): Recovered 0 geofences.
,I/PeopleSync( 4440): ***Sync finished***, duration: 1255 [5005f081]
,I/GeofencerStateMachine( 4410): Network location disabled.
,W/GamesSyncAdapter( 4440): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 4440): Sync duration for 3a3529a: 46
,I/dalvikvm( 4410): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.location.internal.server.o.f
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1398: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x00ab
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4811 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,I/dalvikvm( 4440): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.permission.PermissionUtils.getMissingPermissionGroups
W/dalvikvm( 4440): VFY: unable to resolve virtual method 349: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4440): VFY: replacing opcode 0x6e at 0x0036
,W/GCoreFlp( 4410): No location to return for getLastLocation()
,W/FusedLocationProvider( 4410): location=null
,D/dalvikvm( 4811): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x42071440, skipping init
I/openssl ( 4811): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4811): Crypto mode 0 already enabled
,W/GeofencerStateMachine( 4410): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 1018): GC_EXPLICIT freed 1557K, 65% free 18012K/50128K, paused 4ms+11ms, total 104ms
,W/GCoreFlp( 4410): No location to return for getLastLocation()
,W/FusedLocationProvider( 4410): location=null
,E/dalvikvm( 4440): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
W/dalvikvm( 4440): VFY: unable to resolve new-instance 177 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
,D/dalvikvm( 4440): VFY: replacing opcode 0x22 at 0x0013
,W/GCoreFlp( 4410): No location to return for getLastLocation()
,W/FusedLocationProvider( 4410): location=null
,D/dalvikvm( 4440): DexOpt: unable to opt direct call 0x0397 at 0x1a in Lcom/google/android/gms/games/ui/util/UiUtils;.constructButtonBackground
,E/ctxmgr  ( 4410): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/dalvikvm( 4440): GC_CONCURRENT freed 1942K, 32% free 11771K/17224K, paused 3ms+5ms, total 57ms
,W/dalvikvm( 4410): VFY: unable to find class referenced in signature (Lcom/android/location/provider/ActivityChangedEvent;)
I/dalvikvm( 4410): Could not find method com.android.location.provider.ActivityChangedEvent.getActivityRecognitionEvents, referenced from method com.google.android.location.a.j.a
W/dalvikvm( 4410): VFY: unable to resolve virtual method 3610: Lcom/android/location/provider/ActivityChangedEvent;.getActivityRecognitionEvents ()Ljava/lang/Iterable;
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x0009
,W/ctxmgr  ( 4410): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10022, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 4410): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/Icing   ( 4440): Loaded CLD2 Version V2.0 - 20141016
,W/Settings( 4410): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/MDM     ( 4440): [413] SitrepService.onHandleIntent: Sitrep successful
,D/dalvikvm( 4440): GC_CONCURRENT freed 1934K, 32% free 11884K/17224K, paused 3ms+5ms, total 44ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 4440): Processed handlePeopleChanged at 503901
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,W/DataBroker( 4440): No player ID found and calling context is not the dest app
,D/dalvikvm( 4440): GC_CONCURRENT freed 1967K, 31% free 11964K/17224K, paused 4ms+4ms, total 35ms
,D/dalvikvm( 4440): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Icing   ( 4440): Indexing 23C8A109C525F678B1D097C356E5EF5427DDCB32 from com.google.android.gms
,I/Icing   ( 4440): Indexing done 23C8A109C525F678B1D097C356E5EF5427DDCB32
,I/Icing   ( 4440): Indexing 33C9823592F9224FDF8CF2C4F816D891F132C8CC from com.google.android.gms
,I/Icing   ( 4440): Indexing done 33C9823592F9224FDF8CF2C4F816D891F132C8CC
,I/Icing   ( 4440): Indexing DE699A2D80A17286FE9401866B0ED7BCAD7AAAE8 from com.google.android.gms
,I/Icing   ( 4440): Indexing done DE699A2D80A17286FE9401866B0ED7BCAD7AAAE8
,I/Icing   ( 4440): Indexing BE36BA817A97D732EF2D4AB6C1C6F8CE86E56F6D from com.google.android.gms
,I/Icing   ( 4440): Indexing done BE36BA817A97D732EF2D4AB6C1C6F8CE86E56F6D
,I/Icing   ( 4440): updateResources: need to parse f{com.google.android.gms}
,I/GAV2    ( 4615): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 4440): GC_CONCURRENT freed 1882K, 30% free 12090K/17224K, paused 4ms+4ms, total 38ms
,I/Icing   ( 4440): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/InternalIcingCorporaPro( 2160): UpdateCorporaTask done [took 5516 ms] updated apps [took 5516 ms] 
,I/Icing   ( 4440): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 4440): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/Icing   ( 4440): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 4440): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449671626
,D/dalvikvm( 4440): Note: class Lcom/google/android/gms/games/internal/IGamesService$Stub; has 207 unimplemented (abstract) methods
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO",
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2160): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4440): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 4440): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 4410): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2160): UpdateCorporaTask done [took 337 ms] updated apps [took 337 ms] 
,I/Icing   ( 4440): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 4440): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449671632
,V/AlarmManager( 1018): sending alarm Alarm{421a5d10 type 2 com.google.android.talk}
,V/AlarmManager( 1018): sending alarm Alarm{421a1ba8 type 2 com.google.android.talk}
,V/AlarmManager( 1018): sending alarm Alarm{421a1768 type 2 com.google.android.talk}
,V/AlarmManager( 1018): sending alarm Alarm{4219f968 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{44862118 type 0 com.android.vending}
,D/Finsky  ( 4161): [340] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4161): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1018): sending alarm Alarm{448621f0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4362cfc8 type 2 android}
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/ActivityThread( 4440): Failed to find provider info for com.android.contacts.metadata
D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, latestRunTime 543258, reason: ServiceChanged
,V/AccountUtils( 4440): 0 accounts found with uca feature
,I/GamesSyncAdapter( 4440): Starting sync for 3a3529a
,I/GamesSyncAdapter( 4440): Sync duration for 3a3529a: 2
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4440): GC_CONCURRENT freed 2169K, 31% free 11893K/17224K, paused 8ms+5ms, total 53ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7,
,V/AlarmManager( 1018): sending alarm Alarm{448622c8 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{43a3deb8 type 2 android}
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1018): GC_CONCURRENT freed 2069K, 64% free 18098K/50128K, paused 6ms+8ms, total 108ms
,V/AlarmManager( 1018): sending alarm Alarm{42862128 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42896ef0 type 2 com.google.android.gms}
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4953 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4953): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4953): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4953): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4953): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 4953): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4953): install
,I/MultiDex( 4953): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4953): loading existing secondary dex files
,I/MultiDex( 4953): load found 3 secondary dex files
,I/MultiDex( 4953): install done
,D/dalvikvm( 4953): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4953): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4953): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4953): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4953): VFY: unable to resolve instance field 36
,D/dalvikvm( 4953): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4953): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4953): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4953): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4953): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4953): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4953): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42070cd0
,D/dalvikvm( 4953): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42070cd0
D/dalvikvm( 4953): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42070cd0, skipping init
,D/dalvikvm( 4953): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42070cd0
D/dalvikvm( 4953): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42070cd0
,V/JNIHelp ( 4953): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4953): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42070cd0
,D/dalvikvm( 4953): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42070cd0
D/dalvikvm( 4953): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42070cd0
,D/dalvikvm( 4953): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42070cd0
,D/dalvikvm( 4410): GC_EXPLICIT freed 1314K, 36% free 11142K/17224K, paused 3ms+8ms, total 49ms
,I/ProviderInstaller( 4953): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 4410): callingUid 10022, callindPid: 4410
,D/AuthorizationBluetoothService( 4520): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 4520): Proximity feature is not enabled.
,D/GetConfigurationSnapshotOperation( 4410): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/LocationInitializer( 4440): Restart initialization of location
,E/MDM     ( 4410): [403] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 4410): No location to return for getLastLocation()
,W/FusedLocationProvider( 4410): location=null
,I/dalvikvm( 4953): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4953): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4953): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4953): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4953): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4953): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4953): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4953): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4953): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4953): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4953): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 4953): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4953): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4953): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/PhenotypeFlagCommitter( 4410): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4410): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 4520): GC_EXPLICIT freed 1859K, 40% free 10416K/17224K, paused 2ms+5ms, total 36ms
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  279): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5116000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5116000
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
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,I/dalvikvm( 4953): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4953): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x003d
D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,W/dalvikvm( 4953): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3809944678
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/dalvikvm( 4953): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/dalvikvm( 4953): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4953): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4953): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4953): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 4953): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 4440): disconnect managed GoogleApiClient
,D/NativeLibraryUtils( 4953): Install completed successfully. count=14 extracted=0
,I/dalvikvm( 4410): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 4410): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4410): VFY: replacing opcode 0x6e at 0x003d
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4953): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42398ca0
D/dalvikvm( 4953): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42398ca0
,D/dalvikvm( 4953): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42398ca0, skipping init
,D/dalvikvm( 4953): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4996): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4953): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4953): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 70ms
,I/Adreno-EGL( 4953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4953): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4953): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4953): Local Branch: 
I/Adreno-EGL( 4953): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4953): Local Patches: NONE
I/Adreno-EGL( 4953): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 4953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4953): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4953): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4953): Local Branch: 
I/Adreno-EGL( 4953): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4953): Local Patches: NONE
I/Adreno-EGL( 4953): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/dalvikvm( 4520): Total arena pages for JIT: 11
,I/dalvikvm( 4520): Total arena pages for JIT: 12
I/dalvikvm( 4520): Total arena pages for JIT: 13
,I/dalvikvm( 4520): Total arena pages for JIT: 14
,I/ActivityManager( 1018): Killing 4423:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1018): sending alarm Alarm{4228cc90 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4323c780 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match,
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42537c18 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4520): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{42284708 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/AlarmManager( 1018): sending alarm Alarm{4293fe20 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open '',
,V/AlarmManager( 1018): sending alarm Alarm{43d0c768 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4394ea20 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{435adeb0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42512560 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42956670 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4227dad8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42283f30 type 0 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{42283be0 type 1 com.android.deskclock}
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5052 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 4615:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/EventLogService( 4440): Aggregate from 1449671507343 (log), 1449670424488 (data)
,I/dalvikvm( 4440): Jit: resizing JitTable from 4096 to 8192
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{435ec528 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42f18428 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4335d5b0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43a40948 type 2 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{43a40a20 type 2 android}
,D/dalvikvm( 4410): GC_CONCURRENT freed 1674K, 34% free 11391K/17224K, paused 3ms+6ms, total 36ms
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1287): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1287): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1287): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43b1d3d0 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{4223a748 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43b4b5f8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4223a820 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/AlarmManager( 1018): sending alarm Alarm{433753f0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{433c5230 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42968730 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{433eb260 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43179628 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{433e7348 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 19ms
,I/ProcessStatsService( 1018): Prepared write state in 22ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-46-33.bin
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43d74ed8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{446e06d8 type 3 android}
,D/dalvikvm( 1018): GC_CONCURRENT freed 2110K, 64% free 18141K/50128K, paused 5ms+8ms, total 94ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43d49150 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{447b0b38 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4223a8f8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{423cdb48 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{423cdb98 type 1 com.android.deskclock}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{4473ad68 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5136): 
D/AndroidRuntime( 5136): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5136): CheckJNI is OFF
D/dalvikvm( 5136): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5136): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5136): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5136): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5136): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5136): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5136): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5136): failed to load memtrack module: -2
D/AndroidRuntime( 5136): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10452 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3493:com.test.thalitest/u0a452 (adj 9): stop com.test.thalitest
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{4470ff28 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1018): WIN DEATH: Window{4477bc88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1018): Client connection lost with reason: 4
W/PackageSettings( 1018): Skipping PackageSetting{4232ca48 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10452 user=0: pkg removed
D/dalvikvm( 2129): GC_EXPLICIT freed 6527K, 44% free 9742K/17224K, paused 2ms+6ms, total 40ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449673273
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1299): GC_EXPLICIT freed 390K, 33% free 11541K/17224K, paused 2ms+4ms, total 103ms
D/dalvikvm( 2160): GC_EXPLICIT freed 589K, 44% free 9750K/17224K, paused 2ms+5ms, total 132ms
I/Launcher( 1299): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
W/GeofencerStateMachine( 4410): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
D/dalvikvm( 4440): GC_EXPLICIT freed 999K, 31% free 12016K/17224K, paused 4ms+7ms, total 175ms
D/dalvikvm( 1018): GC_EXPLICIT freed 1048K, 65% free 18026K/50128K, paused 5ms+12ms, total 148ms
I/Launcher( 1299): Deferring update until onResume
D/VoicemailCleanupService( 4123): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2160): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5169 uid=10059 gids={50059, 3003, 1028, 1015}
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449673273
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10452 #1
D/dalvikvm( 1018): GC_EXPLICIT freed 389K, 64% free 18103K/50128K, paused 4ms+17ms, total 163ms
I/InternalIcingCorporaPro( 2160): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
D/AndroidRuntime( 5136): Shutting down VM
D/dalvikvm( 5136): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 5169): Missing scope.enter somewhere. Returning default context
W/GAV2    ( 5169): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5190 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 5190): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 4440): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4440): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4440): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 4440): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 4520): Invalid parameter app
D/gH_CompatibleDatabase( 4440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4440): (3850) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
E/NetworkScheduler.SchedulerReceiver( 4520): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 4440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 4440): threadid=32: thread exiting with uncaught exception (group=0x4179cd40)
E/AndroidRuntime( 4440): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4440): Process: com.google.android.gms, PID: 4440
E/AndroidRuntime( 4440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 4440): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4440): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4440): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 3063): GC_FOR_ALLOC freed 204K, 4% free 20643K/21288K, paused 70ms, total 70ms
I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5222 uid=10058 gids={50058}
I/Process ( 4440): Sending signal. PID: 4440 SIG: 9
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
E/SQLiteDatabase( 5190): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5190): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5190): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5190): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5190): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5190): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5190): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5190): threadid=10: thread exiting with uncaught exception (group=0x4179cd40)
E/AndroidRuntime( 5190): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5190): Process: com.android.keychain, PID: 5190
E/AndroidRuntime( 5190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5190): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5190): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5190): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5190): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5190): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5190): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1018): Process com.google.android.gms (pid 4440) has died.
D/WifiService( 1018): Client connection lost with reason: 4
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10998ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10998ms
I/Process ( 5190): Sending signal. PID: 5190 SIG: 9
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
I/ActivityManager( 1018): Process com.android.keychain (pid 5190) has died.
W/ActivityManager( 1018): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20989ms
D/Documents( 5222): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5222): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5222): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 5222): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 5222): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 5222): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 5222): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5222): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5222): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 5222): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5222): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 5222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 5222): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 5222): Shutting down VM
W/dalvikvm( 5222): threadid=1: thread exiting with uncaught exception (group=0x4179cd40)
D/Documents( 5222): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 5222): FATAL EXCEPTION: main
E/AndroidRuntime( 5222): Process: com.android.documentsui, PID: 5222
E/AndroidRuntime( 5222): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 5222): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5222): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 5222): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5222): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 5222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 5222): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5222): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5222): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5222): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5222): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5222): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 5222): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 5222): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 5222): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 5222): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 5222): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 5222): 	... 10 more

```
