#### Test 506502784dae475_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1018): sending alarm Alarm{4315cf10 type 2 com.motorola.ccc.cce}
--------- beginning of /dev/log/main
I/PollingManager( 1535): alarm fired!
D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
D/AndroidRuntime( 3562): 
D/AndroidRuntime( 3562): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3562): CheckJNI is OFF
D/dalvikvm( 3562): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3562): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3562): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3562): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3562): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3562): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3562): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3562): failed to load memtrack module: -2
D/AndroidRuntime( 3562): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3562
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3578 uid=10459 gids={50459, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3562): Shutting down VM
D/dalvikvm( 3562): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3578): Binding Chromium to main looper Looper (main, tid 1) {41f88760}
I/LibraryLoader( 3578): Expected native library version number "",actual native library version number ""
I/chromium( 3578): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3578): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d6ff40:true
D/BluetoothAdapter( 3578): 1106892256: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3578): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3578): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3578): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3578): Local Branch: 
I/Adreno-EGL( 3578): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3578): Local Patches: NONE
I/Adreno-EGL( 3578): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3578): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3578): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3578): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3578): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3578): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3578): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3578): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3578): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3578): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3578): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3578): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3578): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3578): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3578): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3578): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3578): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3578): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3578): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3578): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3578): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3578): Enabling debug mode 0
,W/AwContents( 3578): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,398
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +372ms (total +398ms)
W/AwContents( 3578): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3578): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3578): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3578): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8cc10
,D/dalvikvm( 3578): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8cc10
,D/jxcore_app_log( 3578): JniHelper::setJavaVM(0x415defa8), pthread_self() = 1615108224
,D/JX-Cordova( 3578): jxcore cordova android initializing
,I/dalvikvm( 3578): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3578): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3578): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3578): GC_CONCURRENT freed 2783K, 17% free 14385K/17224K, paused 3ms+2ms, total 62ms
,D/dalvikvm( 3578): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 131K, 17% free 14366K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 303K, 17% free 14431K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 16.263MB for 143930-byte allocation
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 266K, 17% free 14468K/17368K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 368K, 18% free 14541K/17580K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 567K, 19% free 14662K/17900K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 16.815MB for 485740-byte allocation
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 865K, 20% free 14837K/18376K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 1283K, 21% free 15094K/19088K, paused 28ms, total 28ms
,D/dalvikvm( 3578): GC_CONCURRENT freed 1677K, 19% free 15464K/19088K, paused 1ms+3ms, total 38ms
,D/dalvikvm( 3578): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3578): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 367K, 20% free 15423K/19088K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 18.658MB for 1639352-byte allocation
,D/dalvikvm( 3578): GC_CONCURRENT freed 1644K, 23% free 16036K/20692K, paused 3ms+7ms, total 45ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 1411K, 23% free 16070K/20692K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 20.071MB for 2459024-byte allocation
,D/dalvikvm( 3578): GC_CONCURRENT freed 264K, 21% free 18430K/23096K, paused 5ms+5ms, total 52ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 4363K, 27% free 17032K/23096K, paused 37ms, total 38ms
,I/dalvikvm-heap( 3578): Grow heap (frag case) to 22.183MB for 3688532-byte allocation
,D/dalvikvm( 3578): GC_CONCURRENT freed 336K, 24% free 20409K/26700K, paused 4ms+5ms, total 48ms
,D/dalvikvm( 3578): GC_FOR_ALLOC freed 3194K, 33% free 17996K/26700K, paused 28ms, total 28ms
,W/jxcore-log( 3578): Initializing JXcore engine
,W/jxcore-log( 3578): JXcore engine is ready
,D/dalvikvm( 3578): GC_CONCURRENT freed 377K, 23% free 20595K/26700K, paused 1ms+2ms, total 33ms
,D/dalvikvm( 3578): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 3578): Starting JXcore engine
,W/jxcore-log( 3578): Platform android
W/jxcore-log( 3578): 
,W/jxcore-log( 3578): Process ARCH arm
W/jxcore-log( 3578): 
,I/jxcore-log( 3578): JXcore Cordova bridge is ready!
I/jxcore-log( 3578): 
,W/jxcore-log( 3578): JXcore engine is started
,I/chromium( 3578): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3578): Toggling radios to true
I/jxcore-log( 3578): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1018): Message: 1
,D/BluetoothManagerService( 1018): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1249): No entry in secure settings for enhanced location services: false
,W/Settings( 1239): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1249): Active network info is not available
I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3632 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1018): setWifiEnabled: true pid=3578, uid=10459
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService( 1018): New client listening to asynchronous messages
,W/Settings( 1239): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1239): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1018): setting operational mode to 1
D/WifiStateMachine( 1018): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1018): processMsg: InitialState
,W/XTWiFiOS( 1249): No entry in secure settings for enhanced location services: false
,I/jxcore-log( 3578): Radios toggled
I/jxcore-log( 3578): 
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1249): Active network info is not available
,W/Settings( 1239): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3632): Adding HeadsetService,
D/AdapterServiceConfig( 3632): Adding A2dpService
D/AdapterServiceConfig( 3632): Adding HidService
D/AdapterServiceConfig( 3632): Adding HealthService
D/AdapterServiceConfig( 3632): Adding PanService
D/AdapterServiceConfig( 3632): Adding GattService
,D/AdapterServiceConfig( 3632): Adding BluetoothMapService
,D/BluetoothAdapterService( 3632): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService( 1018): Message: 20
D/BluetoothAdapterState( 3632): make
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43cfcaa0:true
,I/bluedroid( 3632): init
,I/BluetoothAdapterState( 3632): Entering OffState
,I/bte_conf( 3632): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3632): get_profile_interface socket
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3632): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:2 len:6
,I/bluedroid( 3632): config_hci_snoop_log
D/BluetoothAdapterProperties( 3632): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1018): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3632): Name is: XT1039
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
,D/BluetoothAdapterState( 3632): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3632): Setting state to 11
I/BluetoothAdapterState( 3632): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3632): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3632): make
,I/BluetoothBondStateMachine( 3632): StableState(): Entering Off State
,I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3662 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1018): Proxy object connected
D/BluetoothHeadset( 1232): Proxy object connected
D/BluetoothHeadset( 1232): Proxy object connected
D/BluetoothHeadset( 1232): Proxy object connected
D/HeadsetService( 3632): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3632): classInitNative: succeeds
,D/HeadsetStateMachine( 3632): Version 1.6
,D/HeadsetStateMachine( 3632): make
,I/BluetoothAdapterState( 3632): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3632): get_profile_interface handsfree
,D/BluetoothA2dp( 1018): Proxy object connected
D/A2dpService( 3632): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3632): classInitNative: succeeds
,V/Avrcp   ( 3632): make
,I/bluedroid( 3632): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3632): classInitNative: succeeds
,D/A2dpStateMachine( 3632): make
,I/bluedroid( 3632): get_profile_interface a2dp
,I/GKI_LINUX( 3632): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3632): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3632): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3632): classInitNative: succeeds
D/HidService( 3632): Received start request. Starting profile...
,I/bluedroid( 3632): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3632): classInitNative: succeeds
,D/HealthService( 3632): Received start request. Starting profile...
,I/bluedroid( 3632): get_profile_interface health
,I/BluetoothPanServiceJni( 3632): classInitNative(L105): succeeds
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 3632): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3632): initializeNative(L110): pan
,I/bluedroid( 3632): get_profile_interface pan
,D/BluetoothTethering( 1018): got CMD_CHANNEL_HALF_CONNECTED
,I/BtGatt.JNI( 3632): classInitNative(L684): classInitNative: Success!
,D/BluetoothTethering( 1018): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43cdb6b0
,D/BtGatt.DebugUtils( 3632): handleDebugAction() action=null
D/BtGatt.GattService( 3632): Received start request. Starting profile...
D/BtGatt.GattService( 3632): start()
,I/bluedroid( 3632): get_profile_interface gatt
,D/BluetoothMapService( 3632): Received start request. Starting profile...
,D/BluetoothMapService( 3632): start()
,D/HeadsetPhoneState( 3632): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3632): onSignalStrengthsChanged..for signal  prevSignal=0
,D/HeadsetPhoneState( 3632): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3632): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3632): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3632): enable
,I/bt_hci_bdroid( 3632): init
I/bt_vendor( 3632): bt-vendor : init
I/bt_hci_bdroid( 3632): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3632): userial_init
I/bt_hwcfg( 3632): Starting hciattach daemon
,I/bt_hwcfg( 3632): try to set false
I/bt_hwcfg( 3632): Starting hciattach daemon
,I/bt_hwcfg( 3632): try to set true
,I/bt_hci_bdroid( 3632): bt_hc_worker_thread started
,I/qcom-bluetooth( 3695): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1018): Killing 3289:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/qcom-bluetooth( 3701): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3702): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiService( 1018): New client listening to asynchronous messages
I/MDMCTBK (  272): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  272): NetlinkHandler, interfaceAdded
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
E/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  272): , Wifi = 0
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
I/qcom-bluetooth( 3705): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/TCMD    (  504): NL - Read 1004 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
D/Tethering( 1018): InitialState.processMessage what=4
D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  272): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  272): NetlinkHandler, interfaceAdded
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
E/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  272): , Wifi = 0
I/MDMCTBK (  272): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/qcom-bluetooth( 3706): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/TCMD    (  504): NL - Read 1004 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Lis,tening for incoming client connection request
I/qcom-bluetooth( 3709): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
D/QsoftapCmd(  270): Got softap fwreload command we are passing on
D/SoftapController(  270): Softap fwReload - Ok
,E/Diag_Lib( 3711): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3711): Setting internal use port to rmnet0
E/Diag_Lib( 3711):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3711): Failed on DIAG init
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_proc_name: pid=3711, proc_name=hci_qcomm_init
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3711): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3711): qmi_client [3711]: successfully connected to server, attempt=1
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_client_id [3711]: qmux_client_id=13
E/Diag_Lib( 3711): qmi_client [3711] 13: qmux_client ID is initialized
E/Diag_Lib( 3711): qmi_client [3711] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3711): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3711): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3711): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3711): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3711): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3711): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3711): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3711): qmi_init:  Created client handle b8788788
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
,E/Diag_Lib( 3711): qmi sys error code.........:0
D/CommandListener(  270): Setting iface cfg
D/CommandListener(  270): Trying to bring down wlan0
E/Diag_Lib( 3711): Setting the api flag to : 1
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 54 bytes on fd = 8
,V/BluetoothFtpReceiver( 3632): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/rmt_storage(  429): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7fd21d0
I/rmt_storage(  429): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  429): wakelock acquired: 1, error no: 42
,I/rmt_storage(  429): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1208148248)
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3711):  API Flag .............. 1 
,E/Diag_Lib( 3711):  Message ID ............... 92 
,E/WifiHW  ( 1018): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1018): ctrl_interface != /data/misc/wifi/sockets
,E/Diag_Lib( 3711): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3711): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3711): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3711): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3711): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_release: Released client handle ff
E/Diag_Lib( 3711): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3711): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3711): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3711): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3711): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3711): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3711): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3711): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3711): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3711] 13
E/Diag_Lib( 3711): qmi_client [3711] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3711): qmi_client [3711] 13: failed to locate client data
E/Diag_Lib( 3711): qmi_client [3711] 13: calling release of fd=8
,E/Diag_Lib( 3711): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  429): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  429): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  429): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1208148248) wakelock released: 1, error no: 0
I/rmt_storage(  429): 
,I/rmt_storage(  429): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7fd21d0
,I/qcom-bluetooth( 3716): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,D/WifiStateMachine( 1018): setWifiState: enabling
,D/WifiStateMachine( 1018): Supplicant start successful
I/qcom-bluetooth( 3717): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
I/wpa_supplicant( 3715): Successfully initialized wpa_supplicant
W/XTWiFiOS( 1249): No entry in secure settings for enhanced location services: false
I/wpa_supplicant( 3715): rfkill: Cannot open RFKILL control device
D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
,W/XTWiFiOS( 1249): Active network info is not available
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/bt_hwcfg( 3632): bluetooth satus is on
I/GKI_LINUX( 3632): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3632): btu_task pending for preload complete event
,D/bt_userial_mct( 3632): userial_open(port:0)
,I/bt_userial_vendor( 3632): Done intiailizing UART
I/bt_userial_vendor( 3632): Done intiailizing UART
,I/bt_userial_mct( 3632): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3632): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3632): Entering userial_read_thread()
,I/bt-btu  ( 3632): btu_task received preload complete event
I/        ( 3632): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3632): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3632): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3632): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3632): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3632): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3632): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3632): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3632): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3632): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3632): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3632): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3632): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3632): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3632): BTE_InitTraceLevels -- TRC_BTIF
,E/Diag_Lib( 3715): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3715): Setting internal use port to rmnet0
,E/wpa_supplicant( 3715): baseband property is set to [msm]
,E/wpa_supplicant( 3715):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): card_info[i].card_state: 0x2
E/wpa_supplicant( 3715): card_info[i].error_code: 0x3
E/wpa_supplicant( 3715): SIM/USIM not ready
,E/wpa_supplicant( 3715): Error while reading SIM card status
E/bt-btm  ( 3632): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f11f049 
,E/bt-btm  ( 3632): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f11f049 
,E/bt-btif ( 3632): Calling BTA_HhEnable
E/bt-btif ( 3632): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3632): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3632): Name is: XT1039
,I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3632): Scan Mode:21
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3632): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3632): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3632): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
,I/bte_conf( 3632): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3632): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,E/bt_mct  ( 3632): hci lib postload completed
D/BluetoothPanServiceJni( 3632): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3632): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3632): ScanMode =  21
D/BluetoothAdapterProperties( 3632): State =  11
,D/BluetoothAdapterProperties( 3632): Setting state to 12
I/BluetoothAdapterState( 3632): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3632): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1232): onBluetoothStateChange: up=true
,D/BluetoothPan( 1018): onBluetoothStateChange on: true
D/BluetoothHeadset( 1232): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3632): Entering On State
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3632): Discoverable Timeout:120
,D/BluetoothHeadset( 1232): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1018): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106879960)( 3632): Get Bonded Devices being called
,D/BluetoothAdapterService(1106879960)( 3632): Get Bonded Devices being called
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
E/wpa_supplicant( 3715): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): card_info[i].card_state: 0x2
E/wpa_supplicant( 3715): card_info[i].error_code: 0x3
E/wpa_supplicant( 3715): SIM/USIM not ready
,I/wpa_supplicant( 3715): eap_proxy: Card not ready
,D/BluetoothAdapterService(1106879960)( 3632): Get Bonded Devices being called
,D/BluetoothManagerService( 1018): Message: 40
D/BluetoothMapService( 3632): onReceive
,D/BluetoothMapService( 3632): STATE_ON
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3632): Map Service startRfcommSocketListener
W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a711d8:true
,I/qcom-bt-wlan-coex( 3732): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/LocalBluetoothProfileManager( 3662): Adding local A2DP profile
,D/BluetoothManagerService( 1018): Message: 30
,D/BluetoothMapService( 3632): Map Service initSocket
,D/BluetoothPbapService( 3632): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3632): Handler(): got msg=1
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3662): Adding local HEADSET profile
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/BluetoothManagerService( 1018): Message: 30
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3632): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3632): SOCK FLAG = 1 ***********************
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/BluetoothAdapterProperties( 3632): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothMapService( 3632): Accepting socket connection...
W/BluetoothAdapter( 3632): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapterProperties( 3632): Scan Mode:21
E/BluetoothServiceJni( 3632): SOCK FLAG = 1 ***********************
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3662): Adding local MAP profile
D/BluetoothMap( 3662): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3662): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3662): finishStartingService: stopping service
,D/BluetoothAdapterService(1106879960)( 3632): Get Bonded Devices being called
,D/BluetoothA2dp( 3662): Proxy object connected
,D/A2dpProfile( 3662): Bluetooth service connected
,D/BluetoothHeadset( 3662): Proxy object connected
,D/HeadsetProfile( 3662): Bluetooth service connected
,D/BluetoothInputDevice( 3662): Proxy object connected
,I/wpa_supplicant( 3715): Long line in configuration file truncated
I/wpa_supplicant( 3715): rfkill: Cannot open RFKILL control device
D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
,D/HidProfile( 3662): Bluetooth service connected
,D/BluetoothPan( 3662): BluetoothPAN Proxy object connected
,D/PanProfile( 3662): Bluetooth service connected
D/BluetoothMap( 3662): Proxy object connected
D/MapProfile( 3662): Bluetooth service connected
,D/BluetoothMap( 3662): getConnectedDevices()
,D/BluetoothPbap( 3662): Proxy object connected
,D/PbapServerProfile( 3662): Bluetooth service connected
,E/wpa_supplicant( 3715): COUNTRY Code Recived
,E/wpa_supplicant( 3715): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3715): baseband property is set to [msm]
,E/wpa_supplicant( 3715):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): card_info[i].card_state: 0x2
E/wpa_supplicant( 3715): card_info[i].error_code: 0x3
E/wpa_supplicant( 3715): SIM/USIM not ready
,E/wpa_supplicant( 3715): Error while reading SIM card status
E/wpa_supplicant( 3715): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3715): card_info[i].card_state: 0x2
E/wpa_supplicant( 3715): card_info[i].error_code: 0x3
E/wpa_supplicant( 3715): SIM/USIM not ready
,I/wpa_supplicant( 3715): eap_proxy: Card not ready
,D/dalvikvm( 1018): GC_EXPLICIT freed 22467K, 65% free 17816K/50280K, paused 4ms+10ms, total 156ms
D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: InitialState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): deferMessage: msg=131144
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): deferMessage: msg=131085
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131149
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1018): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
,D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147457
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): Supplicant connection established
,D/WifiStateMachine( 1018): setWifiState: enabled
,W/XTWiFiOS( 1249): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1080): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1249): Active network info is not available
V/BluetoothFtpReceiver( 3632): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3632): BluetoothFtpReceiver Start Service
,D/WifiConfigStore( 1018): Loading config and enabling all networks
,I/SBar.NetworkController( 1080): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1080): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2013): Proximity feature is not enabled.
,E/WifiConfigStore( 1018): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3715): COUNTRY Code Recived -COUNTRY PL
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine( 1018): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=1
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
W/BluetoothAdapter( 3632): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1018): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1018): setDetailed state, old =IDLE and new state=DISCONNECTED
,E/BluetoothServiceJni( 3632): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3632): Accept thread started.
E/wpa_supplicant( 3715): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3715): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1018): Attempting to reconnect to wifi network ..
V/BluetoothFtpService( 3632): Ftp Service onCreate
I/BluetoothFtpService( 3632): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3632): Starting FTP service
,V/BluetoothFtpService( 3632): Ftp Service onStartCommand
,V/BluetoothFtpService( 3632): action: android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
,V/BluetoothFtpService( 3632): Handler(): got msg=1
V/BluetoothFtpService( 3632): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3632): Ftp Service initSocket
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3632): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
,D/WifiP2pService( 1018): P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/BluetoothServiceJni( 3632): SOCK FLAG = 3 ***********************
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=3
V/BluetoothFtpService( 3632): Succeed to create listening socket on channel 20
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
V/BluetoothFtpService:RfcommSocketAcceptThread( 3632): Run Accept thread
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up p2p0
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131152
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): set country code PL
,D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1018): P2pEnablingState
D/WifiP2pService( 1018): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2p socket connection successful
D/WifiP2pService( 1018): P2pEnabledState
D/WifiP2pService( 1018): sending p2p connection changed broadcast
,E/wpa_supplicant( 3715): COUNTRY Code Recived
,E/wpa_supplicant( 3715): COUNTRY Code Recived
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131162
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): set frequency band 2
,W/wpa_supplicant( 3715): wlan0: Failed to initiate AP scan
D/WifiStateMachine( 1018): handleMessage: X
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
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=143371
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1018): DeviceAddress: f4:f1:e1:5c:43:c8
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
D/WifiP2pService( 1018): MCC mode enabled 0
D/WifiP2pService( 1018): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1018): InactiveState
D/WifiP2pService( 1018): InactiveState{ when=-32ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-33ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-33ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-34ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3715): COUNTRY Code Recived
,E/wpa_supplicant( 3715): COUNTRY Code Recived
D/WifiP2pService( 1018): InactiveState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  272): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  272): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
,I/MDMCTBK (  272): wifi_connect_to_supplicant, current pid is = 272
D/MDMCTBK (  272): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  272): wifi_close_sockets: Exit
E/MDMCTBK (  272): Attach monitor thread
,I/MDMCTBK (  272): createWifiMonitorThread: Started the wifi monitor thread -1204780096
,D/MDMCTBK (  272): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2152): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3715): wlan0: Failed to initiate AP scan
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  272): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3715): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 38:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 3 38:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 9e:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 5 9e:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 64:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 6 64:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 fc:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 7 fc:
D/MDMCTBK (  272): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 10:
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-ADDED 8 10:
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  272): Event received = WPS-AP-AVAILABLE-AUTH 
I/wpa_supplicant( 3714): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3714): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  272): Event received = Trying to associate with
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 3715): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  504): NL - Read 312 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
D/TCMD    (  504): NL - Read 192 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
D/TCMD    (  504): NL - Read 68 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
I/wpa_supplicant( 3715): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  504): Listening for incoming client connection request
,I/wpa_supplicant( 3715): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3715): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  272): Event received = Associated with c0:ff:d4
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  504): NL - Read 80 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
D/TCMD    (  504): NL - Read 80 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
D/TCMD    (  504): NL - Read 68 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
,D/TCMD    (  504): Listening for incoming client connection request
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3715): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3715): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  272): Event received = WPA: Key negotiation com
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  272): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  272):  STA Connected !!
D/TCMD    (  504): NL - Read 1000 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
E/MDMCTBK (  272): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  272): get_freq !!, resp=0
I/MDMCTBK (  272): get_freq !!, Strip data
I/MDMCTBK (  272): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  272): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  272): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
I/MDMCTBK (  272): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  272): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  272): get_freq !!, resp=0
I/MDMCTBK (  272): get_freq !!, Strip data
I/MDMCTBK (  272): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  272): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  272): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): get_property_value, Enter
I/MDMCTBK (  272): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  272): get_property_value, Exit
I/MDMCTBK (  272): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1204784432
I/MDMCTBK (  272): return from set_get_from_wpa_supplicant
I/MDMCTBK (  272): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  272): set_property_value, Enter
I/MDMCTBK (  272): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  272): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  272): set_property_value, Exit
E/MDMCTBK (  272): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  272): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  272): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/MDMCTBK (  272): wifi_set_tx_pwr: SETTXPOWER = 19
I/SBar.NetworkController( 1080): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/MDMCTBK (  272): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  272): , reply_len: 3, ret: 0
E/MDMCTBK (  272): MdmCutbackHndler, resp=OK
E/MDMCTBK (  272): 
,D/MDMCTBK (  272): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,I/SBar.NetworkController( 1080): updateTelephonySignalStrength:  No service
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-43ms what=147462 obj=android.net.wifi.StateChangeResult@4215b010 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4277c218 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424b89d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424b89d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X

```
