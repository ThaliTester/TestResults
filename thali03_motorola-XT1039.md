#### Test 51074821f72e61a_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1015): sending alarm Alarm{43cc7900 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3590): 
D/AndroidRuntime( 3590): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3590): CheckJNI is OFF
D/dalvikvm( 3590): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3590): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3590): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3590): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3590): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3590): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3590): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3590): failed to load memtrack module: -2
D/AndroidRuntime( 3590): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3590
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3606 uid=10383 gids={50383, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3590): Shutting down VM
D/dalvikvm( 3590): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
D/dalvikvm(  274): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 21ms
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+6ms, total 22ms
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
V/WebViewChromiumFactoryProvider( 3606): Binding Chromium to main looper Looper (main, tid 1) {41f868e0}
I/LibraryLoader( 3606): Expected native library version number "",actual native library version number ""
I/chromium( 3606): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3606): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ca6ea8:true
D/BluetoothAdapter( 3606): 1106882288: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3606): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3606): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3606): Local Branch: 
I/Adreno-EGL( 3606): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3606): Local Patches: NONE
I/Adreno-EGL( 3606): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3606): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3606): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3606): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3606): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3606): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3606): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3606): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3606): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3606): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3606): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3606): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3606): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3606): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3606): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3606): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3606): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3606): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3606): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3606): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3606): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3606): Enabling debug mode 0
,W/AwContents( 3606): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3606): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1015): Displayed com.test.thalitest/.MainActivity,cp,ca,398
I/ActivityManager( 1015): Displayed com.test.thalitest/.MainActivity: +365ms (total +398ms)
,D/JsMessageQueue( 3606): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3606): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8ad90
,D/dalvikvm( 3606): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8ad90
D/jxcore_app_log( 3606): JniHelper::setJavaVM(0x415daf78), pthread_self() = 1614953080
,D/JX-Cordova( 3606): jxcore cordova android initializing
,I/dalvikvm( 3606): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3606): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3606): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3606): GC_CONCURRENT freed 2779K, 17% free 14334K/17224K, paused 2ms+2ms, total 47ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 237K, 17% free 14363K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 191K, 17% free 14387K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 16.222MB for 146998-byte allocation
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 256K, 17% free 14436K/17368K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 16.340MB for 220492-byte allocation
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 374K, 18% free 14512K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 16.519MB for 330734-byte allocation
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 580K, 19% free 14636K/17908K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 16.798MB for 496096-byte allocation
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 879K, 20% free 14814K/18396K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 17.209MB for 744140-byte allocation
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 1301K, 22% free 15075K/19124K, paused 27ms, total 28ms
,D/dalvikvm( 3606): GC_CONCURRENT freed 1672K, 20% free 15451K/19124K, paused 1ms+3ms, total 30ms
,D/dalvikvm( 3606): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 407K, 20% free 15415K/19124K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 18.683MB for 1674304-byte allocation
,D/dalvikvm( 3606): GC_CONCURRENT freed 1690K, 24% free 15984K/20760K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 1411K, 23% free 16078K/20760K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 20.128MB for 2511452-byte allocation
,D/dalvikvm( 3606): GC_CONCURRENT freed 399K, 21% free 18401K/23216K, paused 5ms+4ms, total 56ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 4280K, 27% free 17044K/23216K, paused 34ms, total 39ms
,I/dalvikvm-heap( 3606): Grow heap (frag case) to 22.270MB for 3767174-byte allocation
,D/dalvikvm( 3606): GC_CONCURRENT freed 304K, 24% free 20702K/26896K, paused 5ms+4ms, total 54ms
,D/dalvikvm( 3606): GC_FOR_ALLOC freed 3031K, 34% free 18002K/26896K, paused 28ms, total 28ms
,W/jxcore-log( 3606): Initializing JXcore engine
,W/jxcore-log( 3606): JXcore engine is ready
,W/jxcore-log( 3606): Starting JXcore engine
,D/dalvikvm( 3606): GC_CONCURRENT freed 323K, 24% free 20664K/26896K, paused 2ms+2ms, total 36ms
,W/jxcore-log( 3606): Platform android
W/jxcore-log( 3606): 
,W/jxcore-log( 3606): Process ARCH arm
W/jxcore-log( 3606): 
,I/jxcore-log( 3606): JXcore Cordova bridge is ready!
I/jxcore-log( 3606): 
,W/jxcore-log( 3606): JXcore engine is started
,I/chromium( 3606): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3606): Turning radios to true
I/jxcore-log( 3606): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1015): Message: 1
,D/BluetoothManagerService( 1015): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1213): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1241): Active network info is not available
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3662 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1015): New client listening to asynchronous messages
,W/Settings( 1213): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1015): setWifiEnabled: true pid=3606, uid=10383
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1015): setting operational mode to 1
D/WifiStateMachine( 1015): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1015): processMsg: InitialState
,W/Settings( 1213): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1241): Active network info is not available
,W/Settings( 1213): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3662): Adding HeadsetService
D/AdapterServiceConfig( 3662): Adding A2dpService
D/AdapterServiceConfig( 3662): Adding HidService
D/AdapterServiceConfig( 3662): Adding HealthService
D/AdapterServiceConfig( 3662): Adding PanService
D/AdapterServiceConfig( 3662): Adding GattService
,D/AdapterServiceConfig( 3662): Adding BluetoothMapService
,D/BluetoothAdapterService( 3662): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothAdapterState( 3662): make
,D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4334ad48:true
,I/bluedroid( 3662): init
,I/BluetoothAdapterState( 3662): Entering OffState
,I/bte_conf( 3662): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3662): get_profile_interface socket
,D/BluetoothManagerService( 1015): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1015): Message: 40
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3662): config_hci_snoop_log
D/BluetoothManagerService( 1015): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 8 receivers.
I/GKI_LINUX( 3662): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3662): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3662): Name is: XT1039
D/BluetoothManagerService( 1015): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1015): Stored Bluetooth name: XT1039
D/BluetoothAdapterState( 3662): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3662): Setting state to 11
I/BluetoothAdapterState( 3662): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3662): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1015): Message: 60
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3662): make
,I/BluetoothBondStateMachine( 3662): StableState(): Entering Off State
,I/ActivityManager( 1015): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3689 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1015): Proxy object connected
D/BluetoothHeadset( 1230): Proxy object connected
D/BluetoothHeadset( 1230): Proxy object connected
D/BluetoothHeadset( 1230): Proxy object connected
D/HeadsetService( 3662): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3662): classInitNative: succeeds
D/HeadsetStateMachine( 3662): Version 1.6
D/HeadsetStateMachine( 3662): make
I/BluetoothAdapterState( 3662): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3662): get_profile_interface handsfree
,D/BluetoothA2dp( 1015): Proxy object connected
,D/A2dpService( 3662): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3662): classInitNative: succeeds
,V/Avrcp   ( 3662): make
,I/bluedroid( 3662): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3662): classInitNative: succeeds
,D/A2dpStateMachine( 3662): make
,I/bluedroid( 3662): get_profile_interface a2dp
,I/GKI_LINUX( 3662): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3662): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3662): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3662): classInitNative: succeeds
D/HidService( 3662): Received start request. Starting profile...
,I/bluedroid( 3662): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3662): classInitNative: succeeds
,D/HealthService( 3662): Received start request. Starting profile...
,I/bluedroid( 3662): get_profile_interface health
,I/BluetoothPanServiceJni( 3662): classInitNative(L105): succeeds
,D/BluetoothPan( 1015): BluetoothPAN Proxy object connected
D/PanService( 3662): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3662): initializeNative(L110): pan
,I/bluedroid( 3662): get_profile_interface pan
,D/BluetoothTethering( 1015): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1015): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4319eea8
,I/BtGatt.JNI( 3662): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3662): handleDebugAction() action=null
D/BtGatt.GattService( 3662): Received start request. Starting profile...
D/BtGatt.GattService( 3662): start()
,I/bluedroid( 3662): get_profile_interface gatt
,D/BluetoothMapService( 3662): Received start request. Starting profile...
,D/BluetoothMapService( 3662): start()
,D/HeadsetPhoneState( 3662): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3662): onSignalStrengthsChanged..for signal  prevSignal=0
,D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3662): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3662): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3662): enable
,I/bt_hci_bdroid( 3662): init
I/bt_vendor( 3662): bt-vendor : init
I/bt_hci_bdroid( 3662): ro.qualcomm.hci_transport set to smd
,D/bt_userial_mct( 3662): userial_init
I/bt_hwcfg( 3662): Starting hciattach daemon
I/bt_hci_bdroid( 3662): bt_hc_worker_thread started
,I/bt_hwcfg( 3662): try to set false
I/bt_hwcfg( 3662): Starting hciattach daemon
,I/bt_hwcfg( 3662): try to set true
,I/ActivityManager( 1015): Killing 3419:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/qcom-bluetooth( 3723): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/MDMCTBK (  271): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  271): NetlinkHandler, interfaceAdded
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
E/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  271): , Wifi = 0
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
,E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  456): NL - Read 1004 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,I/MDMCTBK (  271): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  271): NetlinkHandler, interfaceAdded
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
E/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  271): , Wifi = 0
I/MDMCTBK (  271): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1015): InitialState.processMessage what=4
D/TCMD    (  456): NL - Read 1004 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,I/qcom-bluetooth( 3732): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,I/qcom-bluetooth( 3733): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QsoftapCmd(  269): Got softap fwreload command we are passing on
,D/SoftapController(  269): Softap fwReload - Ok
,D/CommandListener(  269): Setting iface cfg
D/CommandListener(  269): Trying to bring down wlan0
,I/qcom-bluetooth( 3736): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3737): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3738): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiHW  ( 1015): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1015): ctrl_interface != /data/misc/wifi/sockets
,E/Diag_Lib( 3740): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3740): Setting internal use port to rmnet0
E/Diag_Lib( 3740):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3740): Failed on DIAG init
,E/Diag_Lib( 3740): linux_qmi_qmux_if_client_get_proc_name: pid=3740, proc_name=hci_qcomm_init
E/Diag_Lib( 3740): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3740): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
,E/Diag_Lib( 3740): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3740): qmi_client [3740]: successfully connected to server, attempt=1
E/Diag_Lib( 3740): linux_qmi_qmux_if_client_get_client_id [3740]: qmux_client_id=13
E/Diag_Lib( 3740): qmi_client [3740] 13: qmux_client ID is initialized
,E/Diag_Lib( 3740): qmi_client [3740] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3740): qmi_client [3740] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3740): qmi_client [3740] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3740): Sending signal ...... to read cmd data 
E/Diag_Lib( 3740): qmi error code.........:0
E/Diag_Lib( 3740): qmi sys error code.........:0
E/Diag_Lib( 3740): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3740): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3740): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3740): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3740): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3740): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3740): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3740): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3740): qmi_init:  Created client handle b876d788
,E/Diag_Lib( 3740): qmi_client [3740] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3740): qmi_client [3740] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3740): Sending signal ...... to read cmd data 
E/Diag_Lib( 3740): qmi error code.........:0
,E/Diag_Lib( 3740): qmi sys error code.........:0
E/Diag_Lib( 3740): Setting the api flag to : 1
,E/Diag_Lib( 3740): qmi_client [3740] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3742): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3742): rfkill: Cannot open RFKILL control device
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,D/WifiStateMachine( 1015): setWifiState: enabling
,D/WifiStateMachine( 1015): Supplicant start successful
,D/WifiMonitor( 1015): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1241): Active network info is not available
,E/Diag_Lib( 3742): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3742): Setting internal use port to rmnet0
,E/wpa_supplicant( 3742): baseband property is set to [msm]
I/rmt_storage(  442): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb894a1d0
I/rmt_storage(  442): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  442): wakelock acquired: 1, error no: 42
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198218696)
E/Diag_Lib( 3740): qmi_client [3740] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3740):  API Flag .............. 1 
,E/Diag_Lib( 3740):  Message ID ............... 92 
,E/wpa_supplicant( 3742):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
E/wpa_supplicant( 3742): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3742): card_info[i].card_state: 0x2
E/wpa_supplicant( 3742): card_info[i].error_code: 0x3
E/wpa_supplicant( 3742): SIM/USIM not ready
,E/wpa_supplicant( 3742): Error while reading SIM card status
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/wpa_supplicant( 3742): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3742): card_info[i].card_state: 0x2
E/wpa_supplicant( 3742): card_info[i].error_code: 0x3
E/wpa_supplicant( 3742): SIM/USIM not ready
,I/wpa_supplicant( 3742): eap_proxy: Card not ready
,D/dalvikvm( 1015): GC_EXPLICIT freed 22402K, 65% free 17909K/50348K, paused 3ms+10ms, total 215ms
E/Diag_Lib( 3740): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3740): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3740): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3740): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3740): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3740): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3740): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3740): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3740): qmi_client [3740] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3740): qmi_client [3740] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3740): Sending signal ...... to read cmd data 
E/Diag_Lib( 3740): qmi error code.........:0
E/Diag_Lib( 3740): qmi sys error code.........:0
E/Diag_Lib( 3740): qmi_release: Released client handle ff
E/Diag_Lib( 3740): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3740): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3740): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3740): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3740): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3740): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3740): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3740): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3740): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3740): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3740): qmi_client [3740] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3740): qmi_client [3740] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3740): Sending signal ...... to read cmd data 
E/Diag_Lib( 3740): qmi error code.........:0
E/Diag_Lib( 3740): qmi sys error code.........:0
E/Diag_Lib( 3740): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3740] 13
E/Diag_Lib( 3740): qmi_client [3740] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3740): qmi_client [3740] 13: failed to locate client data
E/Diag_Lib( 3740): qmi_client [3740] 13: calling release of fd=8
,E/Diag_Lib( 3740): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/WifiService( 1015): New client listening to asynchronous messages
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198218696) wakelock released: 1, error no: 0
I/rmt_storage(  442): 
,I/rmt_storage(  442): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb894a1d0
,I/wpa_supplicant( 3742): Long line in configuration file truncated
,I/wpa_supplicant( 3742): rfkill: Cannot open RFKILL control device
,V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,D/AuthorizationBluetoothService( 1368): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 3747): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3748): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3742): COUNTRY Code Recived
,E/wpa_supplicant( 3742): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3742): baseband property is set to [msm]
,I/bt_hwcfg( 3662): bluetooth satus is on
,D/bt_userial_mct( 3662): userial_open(port:0)
,I/bt_userial_vendor( 3662): Done intiailizing UART
I/bt_userial_vendor( 3662): Done intiailizing UART
I/bt_userial_mct( 3662): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3662): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3662): Entering userial_read_thread()
I/GKI_LINUX( 3662): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3662): btu_task pending for preload complete event
,I/bt-btu  ( 3662): btu_task received preload complete event
,E/wpa_supplicant( 3742):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3742): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3742): card_info[i].card_state: 0x2
E/wpa_supplicant( 3742): card_info[i].error_code: 0x3
E/wpa_supplicant( 3742): SIM/USIM not ready
,E/wpa_supplicant( 3742): Error while reading SIM card status
,I/        ( 3662): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3662): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3662): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3662): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 3662): BTE_InitTraceLevels -- TRC_AVRC
E/wpa_supplicant( 3742): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3742): card_info[i].card_state: 0x2
E/wpa_supplicant( 3742): card_info[i].error_code: 0x3
E/wpa_supplicant( 3742): SIM/USIM not ready
I/wpa_supplicant( 3742): eap_proxy: Card not ready
I/        ( 3662): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3662): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 3662): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3662): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3662): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3662): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3662): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3662): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3662): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3662): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiStateMachine( 1015): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: InitialState
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): deferMessage: msg=131144
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131085
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1015): deferMessage: msg=131085
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131149
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1015): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147457
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): Supplicant connection established
,D/WifiStateMachine( 1015): setWifiState: enabled
I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1241): Active network info is not available
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiConfigStore( 1015): Loading config and enabling all networks
E/WifiConfigStore( 1015): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3742): COUNTRY Code Recived -COUNTRY PL
,E/bt-btm  ( 3662): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0a5049 
,E/bt-btm  ( 3662): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0a5049 
D/WifiStateMachine( 1015): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStartingState
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1015): invokeEnterMethods: DriverStartedState
,E/bt-btif ( 3662): Calling BTA_HhEnable
,E/bt-btif ( 3662): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3662): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3662): Name is: XT1039
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1015): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3662): Scan Mode:21
I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3662): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:8 len:6
,D/BluetoothManagerService( 1015): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3662): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3662): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/WifiStateMachine( 1015): setDetailed state, old =IDLE and new state=DISCONNECTED
,I/bte_conf( 3662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3662): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
,I/bte_conf( 3662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3662): hci lib postload completed
,I/bte_conf( 3662): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
E/wpa_supplicant( 3742): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3742): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/BluetoothAdapterProperties( 3662): ScanMode =  21
D/WifiStateMachine( 1015): Attempting to reconnect to wifi network ..
,D/BluetoothAdapterProperties( 3662): State =  11
,D/BluetoothAdapterProperties( 3662): Setting state to 12
,I/BluetoothAdapterState( 3662): Bluetooth adapter state changed: 11-> 12
D/WifiStateMachine( 1015): transitionTo: destState=DisconnectedState
,D/BluetoothAdapterService( 3662): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1015): Message: 60
,D/WifiP2pService( 1015): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1015): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3662): Entering On State
D/BluetoothPan( 1015): onBluetoothStateChange on: true
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
D/BluetoothHeadset( 1015): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1015): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1015): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3662): onReceive
D/BluetoothMapService( 3662): STATE_ON
D/BluetoothMapService( 3662): Map Service startRfcommSocketListener
D/BluetoothMapService( 3662): Map Service initSocket
D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
D/BluetoothManagerService( 1015): Message: 40
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/CommandListener(  269): Setting iface cfg
D/CommandListener(  269): Trying to bring up p2p0
D/BluetoothPanServiceJni( 3662): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3662): Discoverable Timeout:120
D/WifiStateMachine( 1015): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1015): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiMonitor( 1015): startMonitoring(p2p0) with mConnected = true
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiP2pService( 1015): P2pEnablingState
D/WifiP2pService( 1015): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2p socket connection successful
D/WifiP2pService( 1015): P2pEnabledState
,D/WifiP2pService( 1015): sending p2p connection changed broadcast
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectedState
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131144
W/BluetoothAdapter( 3662): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131085
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131152
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): set country code PL
E/BluetoothServiceJni( 3662): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3662): Scan Mode:21
I/qcom-bt-wlan-coex( 3764): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapService( 3662): Accepting socket connection...
E/wpa_supplicant( 3742): COUNTRY Code Recived
E/wpa_supplicant( 3742): COUNTRY Code Recived
,D/WifiStateMachine( 1015): handleMessage: X
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1015): handleMessage: E msg.what=131162
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): set frequency band 2
D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
W/wpa_supplicant( 3742): wlan0: Failed to initiate AP scan
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiP2pService( 1015): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131167
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=143371
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/BluetoothPbapService( 3662): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3662): Handler(): got msg=1
,D/WifiP2pService( 1015): MCC mode enabled 0
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3662): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService( 1015): mP2pAutoConnectSupport = 0
,E/BluetoothServiceJni( 3662): SOCK FLAG = 1 ***********************
D/WifiP2pService( 1015): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1015): InactiveState
D/WifiP2pService( 1015): InactiveState{ when=-24ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-24ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): InactiveState{ when=-25ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-25ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3742): COUNTRY Code Recived
,E/wpa_supplicant( 3742): COUNTRY Code Recived
D/WifiP2pService( 1015): InactiveState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-10ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422ea138:true
D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
D/LocalBluetoothProfileManager( 3689): Adding local A2DP profile
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3689): Adding local HEADSET profile
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3689): Adding local MAP profile
D/BluetoothMap( 3689): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3689): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3689): finishStartingService: stopping service
,D/BluetoothAdapterService(1106826840)( 3662): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3662): getBondedDevices: length=1
,D/BluetoothA2dp( 3689): Proxy object connected
,D/A2dpProfile( 3689): Bluetooth service connected
,D/BluetoothHeadset( 3689): Proxy object connected
,D/HeadsetProfile( 3689): Bluetooth service connected
,D/BluetoothInputDevice( 3689): Proxy object connected
,D/HidProfile( 3689): Bluetooth service connected
,D/BluetoothPan( 3689): BluetoothPAN Proxy object connected
D/PanProfile( 3689): Bluetooth service connected
,D/BluetoothMap( 3689): Proxy object connected
D/MapProfile( 3689): Bluetooth service connected
,D/BluetoothMap( 3689): getConnectedDevices()
,D/BluetoothPbap( 3689): Proxy object connected
,D/PbapServerProfile( 3689): Bluetooth service connected
,V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1368): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1368): Proximity feature is not enabled.
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3662): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3662): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3662): Accept thread started.
,V/BluetoothFtpService( 3662): Ftp Service onCreate
I/BluetoothFtpService( 3662): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3662): Starting FTP service
V/BluetoothFtpService( 3662): Ftp Service onStartCommand
,V/BluetoothFtpService( 3662): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3662): Handler(): got msg=1
V/BluetoothFtpService( 3662): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3662): Ftp Service initSocket
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3662): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3662): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3662): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3662): Run Accept thread
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  271): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  271): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): wifi_connect_to_supplicant, current pid is = 271
D/MDMCTBK (  271): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  271): wifi_close_sockets: Exit
E/MDMCTBK (  271): Attach monitor thread
,I/MDMCTBK (  271): createWifiMonitorThread: Started the wifi monitor thread -1218882616
,D/MDMCTBK (  271): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3742): wlan0: Failed to initiate AP scan
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  271): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1015): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledStateupdate channel list
,D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 2 64:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 06:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 5 06:
D/MDMCTBK (  271): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 34:
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 6 34:
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 3742): wlan0: Trying to associate with SSID 'NG700'
D/TCMD    (  456): NL - Read 56 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
I/wpa_supplicant( 3741): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3741): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  271): Event received = Trying to associate with
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 3742): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  456): NL - Read 312 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 192 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
I/wpa_supplicant( 3742): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3742): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,I/wpa_supplicant( 3742): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  271): Event received = Associated with c0:ff:d4
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  456): NL - Read 80 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 80 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3742): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3742): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  271): Event received = WPA: Key negotiation com
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  271):  STA Connected !!
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
,D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  271): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/WifiStateMachine( 1015): handleMessage: X
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
,I/MDMCTBK (  271): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  271): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  271): get_freq !!, resp=0
I/MDMCTBK (  271): get_freq !!, Strip data
I/MDMCTBK (  271): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  271): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  271): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1218886952
I/MDMCTBK (  271): return from set_get_from_wpa_supplicant
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
,I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): wifi_set_tx_pwr: SETTXPOWER = 19
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147459
E/MDMCTBK (  271): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  271): , reply_len: 3, ret: 0
E/MDMCTBK (  271): MdmCutbackHndler, resp=OK
E/MDMCTBK (  271): 
,D/MDMCTBK (  271): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): Network connection established
,D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1015): invokeExitMethods: DisconnectedState
,D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1015): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1015): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=-46ms what=147462 obj=android.net.wifi.StateChangeResult@42881990 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=-23ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43220578 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-1ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c1518 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420c1518 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: X
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 8
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 7 8
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 8e
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 5 8e
D/TCMD    (  456): NL - Read 56 bytes from update socket.
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 06
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 6 06
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 34
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-ADDED 7 34
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  271): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiP2pService( 1015): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiP2pService( 1015): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427f06b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiP2pService( 1015): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@427f06b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@427f06b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): handleMessage: X
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,D/TCMD    (  456): NL - Read 60 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 20
,D/TCMD    (  456): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
,D/WifiStateMachine( 1015): ObtainingIpState{ when=-3ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196613
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): DHCP successful
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1015): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1015): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1015): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState enter
D/WifiStateMachine( 1015): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=151572
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=135190
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1015): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1015): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState enter
,D/WifiStateMachine( 1015): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1015): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1015): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/WifiStateMachine( 1015): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1015): WiFi NOT Tethered!
,E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220b9d0
,I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1079): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1252): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1015): WiFi NOT Tethered!
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220b9d0
,D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1252): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=0
,D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1522): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/        ( 1015): Unable to set rtc to 1447852693: Invalid argument
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,D/        ( 1015): Setting time of day to sec=1447852693
,D/PollingManager( 1522): now: 320672 ,futureTime: 72202684
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1522): Polling alarm set to expire at: 72202684 Current Time: 320679
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1522): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1522): registerApp(): CCE
I/CCE     ( 1522): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1522): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1522): Registering with Alarm Manager to restart CCE
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
I/openssl ( 3004): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3004): Crypto mode 0 already enabled
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,D/PollingManager( 1522): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1522): now: 320755 ,futureTime: 72202684
,D/PollingManager( 1522): Polling alarm set to expire at: 72202684 Current Time: 320755
,E/ActivityThread( 1522): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1522): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1522): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1522): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1522): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1522): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1522): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1522): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1522): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1522): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MMApiWebService( 1522): generating token using payload instead of using session token
,D/OtaApp  ( 1522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1522): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1522): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1522): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 1522): GC_CONCURRENT freed 2983K, 38% free 10713K/17224K, paused 3ms+3ms, total 41ms
,I/MMApiWSBase( 1522): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1522): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1522): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1522): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager( 1015): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3868 uid=10056 gids={50056, 3003, 1028, 1015}
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3888 uid=10030 gids={50030, 3003, 1028, 1015}
I/dalvikvm( 1353): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1353): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1353): VFY: replacing opcode 0x6e at 0x0033
,D/GpsLocationProvider( 1015): NTP server returned: 1447852690193 (Wed Nov 18 14:18:10 CET 2015) reference: 317739 certainty: 11 system time offset: -3259
I/dalvikvm( 1198): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1198): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1198): VFY: replacing opcode 0x6e at 0x0033
,I/VacuumService( 1368): Vacuum at: now=1447852693457 tag=VacuumService
,E/LocSvc_ApiV02( 1015): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,V/MmsConfig( 3888): mnc/mcc: 
V/MmsConfig( 3888): tag: bool value: enabledMMS - true
V/MmsConfig( 3888): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 3888): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3888): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3888): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3888): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3888): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3888): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 3888): tag: int value: recipientLimit - 20
,V/MmsConfig( 3888): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3888): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 3888): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 3888): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3888): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3888): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 3888): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3888): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3888): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm( 1198): GC_EXPLICIT freed 1460K, 41% free 10322K/17224K, paused 3ms+32ms, total 74ms
,D/DelayedSyncController( 3868): Delaying sync.
,I/ActivityManager( 1015): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3915 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1015): Killing 3451:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/DataBuffer( 1198): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42204c18)
,I/ActivityManager( 1015): Killing 3075:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1230): GC_EXPLICIT freed 1387K, 45% free 9517K/17224K, paused 8ms+8ms, total 98ms
,D/MobileConnectivityChangeReceiver( 3915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3915): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3915): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3915): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3928 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3479:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1353): Checkin interval check for package: unspecified last checkin: 1447848618790 min interval config: 0 actual interval: 4074893
,I/CheckinService( 1353): Checking schedule, now: 1447852693698 next: 1447848648770
,I/CheckinService( 1353): active receiver: enabled
,I/CheckinService( 1353): Preparing to send checkin request
,I/EventLogService( 1353): Accumulating logs since 1447851950591
,D/dalvikvm( 1015): GC_EXPLICIT freed 1643K, 65% free 17943K/50348K, paused 4ms+10ms, total 101ms
,V/WebViewChromiumFactoryProvider( 3928): Binding Chromium to main looper Looper (main, tid 1) {41f819c0}
,I/LibraryLoader( 3928): Expected native library version number "",actual native library version number ""
,I/chromium( 3928): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3928): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3928): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3928): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3928): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3928): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3928): Local Branch: 
I/Adreno-EGL( 3928): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3928): Local Patches: NONE
I/Adreno-EGL( 3928): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3928): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3928): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3928): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/CheckinRequestBuilder( 1353): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1015): New client listening to asynchronous messages
,E/ActivityThread( 1353): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1353): GC_CONCURRENT freed 1670K, 32% free 11719K/17224K, paused 3ms+5ms, total 40ms
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3928): Starting up...
,I/ImageResourceManager( 3508): ImageResourceManager: uninitalized
,I/iu.Environment( 3508): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3508): SYNC; picasa accounts
I/ActivityManager( 1015): Killing 3055:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MMApiWSBase( 1522): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1522): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1522): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/iu.UploadsManager( 3508): num queued entries: 0
,I/iu.UploadsManager( 3508): num updated entries: 0
,I/iu.SyncManager( 3508): NEXT; no task
,I/iu.SyncManager( 1353): SYNC; picasa accounts
,D/NetworkLogImpl( 1353): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1353): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/Checkin ( 1522): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1522): handleGetNotificationsResponse(): got 0; more=false
,I/iu.UploadsManager( 1353): num queued entries: 0
,I/iu.UploadsManager( 1353): num updated entries: 0
,I/iu.SyncManager( 1353): NEXT; no task
,I/openssl ( 3004): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3004): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3915): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3508): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1522): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=1
,D/dalvikvm( 3508): GC_CONCURRENT freed 623K, 5% free 16449K/17224K, paused 3ms+2ms, total 32ms
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3983 uid=10007 gids={50007, 3003}
,D/MMApiProvisionService( 1522): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"158282","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1522): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1522): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1522): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1522): handleResponse(): Session Expiration alarm set to expire at: Fri Nov 20 10:16:16 CET 2015
,D/MMApiProvisionService( 1522): _setMMApiCredInfo: storing credential info 
,D/ExtensionsFactory( 3983): No custom extensions.
,E/MMApiProvisionService( 1522): handleResponse(): no settings sent by the server:
,D/Checkin ( 1522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1522): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/ActivityManager( 1015): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4000 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1015): Killing 3112:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4011 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3689:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1015): Client connection lost with reason: 4
I/GCM     ( 1368): GCM config loaded
,V/AlarmClock( 4000): AlarmInitReceiver android.intent.action.TIME_SET
,I/AlarmClock( 4000): Displaying next alarm time: ''
,V/AlarmClock( 4000): AlarmInitReceiver finished
,I/CalendarProvider2( 4011): Created com.android.providers.calendar.CalendarAlarmManager@41f9dfb0(com.android.providers.calendar.CalendarProvider2@41f95b68)
I/ActivityManager( 1015): Killing 3004:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/UdcCache:FPQuery( 1353): Bootstrapping UDC settings cache for all accounts
,I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4035 uid=10098 gids={50098}
,D/dalvikvm( 4035): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f8a078, skipping init
,D/TimeService( 4035): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1447852694620
D/        ( 4035): TimeServiceNative: User Time to be set is 1447852694620
D/QC-time-services( 4035): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4035): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 4035): Lib:time_genoff_operation: pargs->ts_val = 1447852694620
D/QC-time-services( 4035): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  431): Daemon: Connection accepted:time_genoff
D/QC-time-services(  431): Daemon:Received base = 2, unit = 1, operation = 0,value = 1447852694620
D/QC-time-services(  431): Daemon:genoff_opr: Base = 2, val = 1447852694620, operation = 0
D/QC-time-services(  431): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/18/115 13:12:25
,D/QC-time-services(  431): Daemon:Value read from RTC seconds = 1447852345000
D/QC-time-services(  431): Daemon:new time 1447852694620 
D/QC-time-services(  431): Daemon: delta 349620 genoff 349620 
D/QC-time-services(  431): Daemon:genoff_persistent_update: Writing genoff = 349620 to memory
D/QC-time-services(  431): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  431): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  431): Updating the TOD offset
D/QC-time-services(  431): Daemon:genoff_persistent_update: Writing genoff = 349620 to memory
D/QC-time-services(  431): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  431): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  431): Daemon:Update to modem bit set
D/QC-time-services(  431): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  431): Daemon: Base = 2, Value being sent to MODEM = 18446743757745101236
,E/QC-time-services( 4035): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  431): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  431): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1353): Checkin interval check for package: unspecified last checkin: 1447848618790 min interval config: 0 actual interval: 4075867
,D/DEBUG   ( 1522): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1522): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1522): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1522
,I/OtaApp  ( 1522): [info] > Updatetime from metadata: 10
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > cancelling the previous pending intent set for install later
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1522): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1522): [info] > Updatetime from metadata: 10
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1522): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1522): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1522
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1522): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1522): [info] > Updatetime from metadata: 10
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1522): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1522): [info] > Updatetime from metadata: 10
,D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1522): [debug] > cancelling the previous pending intent set for install later
,I/LaunchCheckinHandler( 1015): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,125
I/OtaApp  ( 1522): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1522): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1522): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DEBUG   ( 1522): Received intent : com.motorola.ccc.notification.action.NOTIFY
D/OtaApp  ( 1522): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DEBUG   ( 1522): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1522): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1522): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1522): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager( 1015): Activity reported stop, but no longer stopping: ActivityRecord{42179760 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/SundryService( 1522): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1522): Received shoulder tap
,D/WaitableIntentService( 1522): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1522): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1522): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1522): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/dalvikvm( 1368): GC_CONCURRENT freed 1921K, 39% free 10624K/17224K, paused 7ms+7ms, total 85ms
,I/MMApiWSBase( 1522): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1522): publish the event [tag = MOT_CCE event name = LOG]
,D/GetConfigurationSnapshotOperation( 1368): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4053 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,W/dalvikvm( 4053): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4053): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,I/PhenotypeFlagCommitter( 1368): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/dalvikvm( 4053): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4053): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x00ca
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1252): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1079): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1252): Inetcondition changed, white->blue
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/MultiDex( 4053): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4053): install
I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=100
,I/MultiDex( 4053): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
I/MultiDex( 4053): loading existing secondary dex files
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/MultiDex( 4053): load found 3 secondary dex files
,I/GoogleURLConnFactory( 1368): Using platform SSLCertificateSocketFactory
,I/MultiDex( 4053): install done
,D/dalvikvm( 4053): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4053): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4053): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4053): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4053): VFY: unable to resolve instance field 46
,D/dalvikvm( 4053): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4053): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4053): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4053): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4053): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4053): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4053): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f8ba60
D/dalvikvm( 4053): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f8ba60
,D/dalvikvm( 4053): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f8ba60, skipping init
,D/dalvikvm( 4053): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f8ba60
D/dalvikvm( 4053): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f8ba60
,V/JNIHelp ( 4053): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 4053): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f8ba60
,D/dalvikvm( 4053): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f8ba60
D/dalvikvm( 4053): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f8ba60
,D/dalvikvm( 4053): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f8ba60
,D/WifiStateMachine( 1015): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
D/ConnectivityService( 1015): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1015):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,D/GetCommittedConfigurationOperation( 1368): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,I/ProviderInstaller( 4053): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1198): callingUid 10022, callindPid: 1198
,E/MDM     ( 1198): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/dalvikvm( 4053): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 4053): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1353): Restart initialization of location
D/AuthorizationBluetoothService( 1368): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1368): Proximity feature is not enabled.
I/dalvikvm( 4053): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4053): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x0220
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4053): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4053): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4053): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4053): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 4053): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4053): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4053): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4053): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4053): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,V/GmsCoreStatsServiceLauncher( 1353): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/dalvikvm( 4053): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1368): location=null
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  277): App is not loaded in QSEE
E/QSEECOMAPI: (  277): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  277): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  277): App is not loaded in QSEE
E/QSEECOMAPI: (  277): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  277): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  277): App is not loaded in QSEE
,I/dalvikvm( 4053): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 4053): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 4053): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4053): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4053): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/QSEECOMAPI: (  277): Loaded image: APP id = 3
I/dalvikvm( 4053): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5339000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5339000
W/dalvikvm( 4053): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4053): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 4053): Using platform SSLCertificateSocketFactory
D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/MMApiWSBase( 1522): doRequest(): v1/ns/list/messages resp length: 1465
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/CCE     ( 1522): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1522): AppWSProxy - sendAIDLWSResponse() sending reponse
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/Checkin ( 1522): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1522): handleGetNotificationsResponse(): got 0; more=false
D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DEBUG   ( 1522): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1522): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1522): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1522): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1522): unbindWebServices(): un-registering our AIDL callback...
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3275548938
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/CalendarProvider2( 4011): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4011): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3983): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/dalvikvm( 1015): GC_EXPLICIT freed 786K, 65% free 17929K/50348K, paused 4ms+9ms, total 96ms
,D/AlertService( 3983): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/NativeLibraryUtils( 4053): Install completed successfully. count=13 extracted=0
,W/Uploader( 1368):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1368): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/GetCommittedConfigurationOperation( 1368): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4053): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4232b850
D/dalvikvm( 4053): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4232b850
,D/dalvikvm( 4053): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4232b850, skipping init
,W/Settings( 4053): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 4053): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4094): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4053): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4053): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 71ms
,I/Adreno-EGL( 4053): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4053): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4053): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4053): Local Branch: 
I/Adreno-EGL( 4053): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4053): Local Patches: NONE
I/Adreno-EGL( 4053): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4053): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4053): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4053): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4053): Local Branch: 
I/Adreno-EGL( 4053): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4053): Local Patches: NONE
I/Adreno-EGL( 4053): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4053): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4053): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4053): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4053): Local Branch: 
I/Adreno-EGL( 4053): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4053): Local Patches: NONE
I/Adreno-EGL( 4053): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4053): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4053): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4053): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4053): Local Branch: 
I/Adreno-EGL( 4053): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4053): Local Patches: NONE
I/Adreno-EGL( 4053): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1112992786
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1353): Classify the device as Phone.
,I/CheckinTask( 1353): Sending checkin request (11646 bytes)
,I/CheckinRequestBuilder( 1353): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1353): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm( 1015): Jit: resizing JitTable from 8192 to 16384
,I/CheckinRequestBuilder( 1353): Classify the device as Phone.
,I/CheckinTask( 1353): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1353): Checking schedule, now: 1447852698417 next: 1448445768407
,I/CheckinService( 1353): active receiver: disabled
,D/CheckinService( 1353): Recording last checkin time for package unspecified as 1447852698432
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3928): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3983): no sender configured
,D/AlertService( 3983): Beginning updateAlertNotification
,D/AlertService( 3983): No fired or scheduled alerts
,D/AlertService( 3983): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3983): No events found starting within 1 week.
,I/ActivityManager( 1015): Killing 3888:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Killing 3915:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1015): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1015): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1015): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1015): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1015): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4108 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/Launcher( 1278): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/Launcher( 1278): Deferring update until onResume,
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1198): DISABLE
,I/GCoreNlp( 1198): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4108): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4108): MmsConfig.loadMmsSettings
I/Babel   ( 4108): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4108): MmsConfig.loadFromDatabase
,E/Babel   ( 4108): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4108): MmsConfig.loadFromResources
,E/Babel   ( 4108): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4108): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4108): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1015): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4139 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1015): Killing 3868:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Killing 3928:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4159 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2151): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4175 uid=10038 gids={50038, 3003, 1028, 1015}
,D/dalvikvm( 3508): GC_FOR_ALLOC freed 35K, 5% free 16421K/17224K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3508): Grow heap (frag case) to 19.805MB for 1821008-byte allocation
,D/dalvikvm( 3508): GC_FOR_ALLOC freed 8K, 5% free 18196K/19004K, paused 10ms, total 10ms
,I/ActivityManager( 1015): Killing 4011:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4139): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4175): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4175): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 1353): GC_CONCURRENT freed 2018K, 33% free 11672K/17224K, paused 4ms+14ms, total 48ms
,D/Finsky  ( 4175): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4175): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4175): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4175): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4175): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4175): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4175): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4175): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4175): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4175): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4175): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4175): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x013c
,I/InternalIcingCorporaPro( 2151): UpdateCorporaTask done [took 294 ms] updated apps [took 294 ms] 
,I/dalvikvm( 4175): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4175): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0392
I/dalvikvm( 4175): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4175): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0398
,I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4211 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/dalvikvm( 4175): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4175): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4175): Skipping gmscore version check
,D/Finsky  ( 4175): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4175): [1] 2.run: Finished loading 1 libraries.
I/dalvikvm( 4175): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4175): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1015): Killing 4000:com.android.deskclock/u0a15 (adj 15): empty #9
I/ActivityManager( 1015): Killing 4035:com.qualcomm.timeservice/u0a98 (adj 15): empty #10
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1353): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1353): Null package name or gms related package.  Ignoreing.
I/Icing   ( 1353): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4211): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f87350, skipping init
I/openssl ( 4211): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4211): Crypto mode 0 already enabled
,D/Finsky  ( 4175): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4175): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Attempting to connect to the test coordinator server
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Test app app.js loaded
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): LogCallback not set !!!!
I/jxcore-log( 3606): 
,I/Choreographer( 3606): Skipped 1274 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 3606): showStatusIcon on inactive InputConnection
,I/chromium( 3606): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect called
I/jxcore-log( 3606): 
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42028670 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{421d6730 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{4289b590 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 7,
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 6
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{43d86380 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":0}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1447852944180},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":1}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":2}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":3}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":3}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":4}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":5}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":6}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":6}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":7}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":8}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":9}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":9}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: JYzsYzAbN+SE+byjAdiOPg==;Matt
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":57250,"expected":57250,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"JYzsYzAbN+SE+byjAdiOPg==;Matt","expected":"JYzsYzAbN+SE+byjAdiOPg==;Matt","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":10}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":11}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":12}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":12}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":13}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: UJA5AHeDzcUBJavuFffELA==;Toby
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":48729,"expected":48729,"test":13,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"UJA5AHeDzcUBJavuFffELA==;Toby","expected":"UJA5AHeDzcUBJavuFffELA==;Toby","test":13,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":14}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":15}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":15}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: Eq9A+YSoNC5uet/fUFRVsw==;Luke
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":57204,"expected":57204,"test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Eq9A+YSoNC5uet/fUFRVsw==;Luke","expected":"Eq9A+YSoNC5uet/fUFRVsw==;Luke","test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":16}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":17}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":18}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":18}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: TzcHTtfn2h2uuTJdf95cZw==;Jukka
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":53822,"expected":53822,"test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"TzcHTtfn2h2uuTJdf95cZw==;Jukka","expected":"TzcHTtfn2h2uuTJdf95cZw==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":19}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":20}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":21}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":21}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: aFKVkbF9ayhtlhrQ0vrAgQ==;Doug
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":39331,"expected":39331,"test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"aFKVkbF9ayhtlhrQ0vrAgQ==;Doug","expected":"aFKVkbF9ayhtlhrQ0vrAgQ==;Doug","test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":22}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3606): {"type":"end","test":23}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":24}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3606): {"type":"end","test":24}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: EpHazT1u7u5ttqcDwwxkPQ==;David
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":53294,"expected":53294,"test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"EpHazT1u7u5ttqcDwwxkPQ==;David","expected":"EpHazT1u7u5ttqcDwwxkPQ==;David","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: EpHazT1u7u5ttqcDwwxkPQ==;David
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":53294,"expected":53294,"test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"EpHazT1u7u5ttqcDwwxkPQ==;David","expected":"EpHazT1u7u5ttqcDwwxkPQ==;David","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":25}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":26}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":27}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{43cc3f30 type 3 android}
,I/jxcore-log( 3606): {"type":"end","test":27}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":667968,"expected":667968,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":529792,"expected":529792,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":839744,"expected":839744,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":900544,"expected":900544,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":521600,"expected":521600,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":781440,"expected":781440,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":289984,"expected":289984,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":896256,"expected":896256,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":916928,"expected":916928,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":699584,"expected":699584,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: nq9KeKOBjAZ221CMkTkriw==;John
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":59159,"expected":59159,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"nq9KeKOBjAZ221CMkTkriw==;John","expected":"nq9KeKOBjAZ221CMkTkriw==;John","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO identityExchange We will advertise the following device name as we start: 6KrD5vmkujoyQ7shbsaMbg==;Srikanth
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":37198,"expected":37198,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","expected":"6KrD5vmkujoyQ7shbsaMbg==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/cb request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO smallerHash Making /identity/rnmine request to pkOther value 6KrD5vmkujoyQ7shbsaMbg==
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":815680,"expected":815680,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":28}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":29}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":30}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":30}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): {"type":"end","test":31}
I/jxcore-log( 3606): 
I/jxcore-log( 3606): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":32}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":33}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{4201efe0 type 2 android}
,I/jxcore-log( 3606): {"type":"end","test":33}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":34}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":35}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":36}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":36}
I/jxcore-log( 3606): 
,E/jxcore-log( 3606): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3606): 
,E/jxcore-log( 3606): Trace: 
E/jxcore-log( 3606):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3606):     at addListener@events.js:140:7
E/jxcore-log( 3606):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 3606):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3606):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 3606): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3606): 
,E/jxcore-log( 3606): Trace: 
E/jxcore-log( 3606):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3606):     at addListener@events.js:140:7
E/jxcore-log( 3606):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 3606):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3606):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3606):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":37}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":38}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":39}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":39}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"TH1pArpiwS6POo2EPupBDQ==","expected":"TH1pArpiwS6POo2EPupBDQ==","test":40,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":40}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":41}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":42}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3606): {"type":"end","test":42}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"glnIQTLyyw23A9FkPB/d1A==","expected":"glnIQTLyyw23A9FkPB/d1A==","test":43,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":43}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":44}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":45}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":45}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"to4H/sJ8EZvvvBGlpW/ADQ==","expected":"to4H/sJ8EZvvvBGlpW/ADQ==","test":46,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":46}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3606): {"type":"end","test":47}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":48}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":48}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"u9yNfaZGnIfgoBAWjALZpg==","expected":"u9yNfaZGnIfgoBAWjALZpg==","test":49,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":49}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":50}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":51}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3606): {"type":"end","test":51}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"PdIPHySSJGPkhFpNw3Ma6w==","expected":"PdIPHySSJGPkhFpNw3Ma6w==","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:53218/identity/cb","data":{"cbValue":"FpoyTzaea1ZDI3hSPt/EmHoSZMlxJXjfrjEK/DObtsU=","pkMine":"N+2eRSa7MVlBZ2fQm8Hb9w=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-5lpI8rMMFt9Uu3pc0dTfAA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"PdIPHySSJGPkhFpNw3Ma6w==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"PdIPHySSJGPkhFpNw3Ma6w==","expected":"PdIPHySSJGPkhFpNw3Ma6w==","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:44294/identity/rnmine","data":{"rnMine":"lUF7GL4qBSNBJjkJc/FCdg==","pkOther":"ozEoME2gEdRFURj0JLuu7A=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-5lpI8rMMFt9Uu3pc0dTfAA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"PdIPHySSJGPkhFpNw3Ma6w==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"PdIPHySSJGPkhFpNw3Ma6w==","expected":"PdIPHySSJGPkhFpNw3Ma6w==","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:40971/identity/cb","data":{"cbValue":"6veeBsRiSGhZhkMJZW+7CBgWib6uzz9CWAz/EJKKAL4=","pkMine":"KEYg8blueGS5fbaOwoCByg=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-5lpI8rMMFt9Uu3pc0dTfAA\"","date":"Wed, 18 Nov 2015 13:23:42 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"PdIPHySSJGPkhFpNw3Ma6w==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"PdIPHySSJGPkhFpNw3Ma6w==","expected":"PdIPHySSJGPkhFpNw3Ma6w==","test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":52}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":53}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":54}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":54}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"0v03KWPQRmgRfTqoinsF6w=="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"NiIf8b43iSB7JGaadYLhNA=="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"wF6UMt9SzDT8JEEyqXKaWJb+u7opLnxBGJpkIbrUU5IV","pkMine":"Bdul4tTAOM5Wna4TbV37Pg=="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"pkSyAHwD1rAt9WPMAVF/uJC0u9P/f45xLyMHS9syaQ==","pkMine":"h9XF387Mak30JrGIYTgXxA=="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"W9JNJ81Oimvs0UA7tYksY1nUKj3SJ9htT/jHAPqb1Uc=","pkMine":" "}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"f/VsBI/zT5Y4IuVw8PuLvw/S/6lpSZBu3+Da4yKZmdE=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"btdmBeQN+Exa10SCjgn/thLgRFBCWv4nwvaA1K6GAs0=","pkMine":"XHg2lKsTh2vYXu1mDx2S/Cw="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"ugv5VlZR/wJ1njsLZc9/4gR03WAsCNq86BoShDSZhHY=","pkMine":"5xNRn1MGUWaVYnzqF1Ot"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"XHg2lKsTh2vYXu1mDx2S/Cw="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"5xNRn1MGUWaVYnzqF1Ot"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"XHg2lKsTh2vYXu1mDx2S/Cw="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"5xNRn1MGUWaVYnzqF1Ot"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"wF6UMt9SzDT8JEEyqXKaWJb+u7opLnxBGJpkIbrUU5IV","pkMine":" "}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"wF6UMt9SzDT8JEEyqXKaWJb+u7opLnxBGJpkIbrUU5IV","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"wF6UMt9SzDT8JEEyqXKaWJb+u7opLnxBGJpkIbrUU5IV","pkMine":"XHg2lKsTh2vYXu1mDx2S/Cw="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"wF6UMt9SzDT8JEEyqXKaWJb+u7opLnxBGJpkIbrUU5IV","pkMine":"5xNRn1MGUWaVYnzqF1Ot"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"pkSyAHwD1rAt9WPMAVF/uJC0u9P/f45xLyMHS9syaQ==","pkMine":" "}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"pkSyAHwD1rAt9WPMAVF/uJC0u9P/f45xLyMHS9syaQ==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"pkSyAHwD1rAt9WPMAVF/uJC0u9P/f45xLyMHS9syaQ==","pkMine":"XHg2lKsTh2vYXu1mDx2S/Cw="}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"pkSyAHwD1rAt9WPMAVF/uJC0u9P/f45xLyMHS9syaQ==","pkMine":"5xNRn1MGUWaVYnzqF1Ot"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"+DN2blPpKNqV2EwZcylJEg==","expected":"+DN2blPpKNqV2EwZcylJEg==","test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":55}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":56}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"setup","id":57}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"end","test":57}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"II4R/uaInqjW7qRTsL8MdQ==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"oKW9hdFuhNjfQ3LsDwwPFQ==","expected":"oKW9hdFuhNjfQ3LsDwwPFQ==","test":58,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"II4R/uaInqjW7qRTsL8MdQ==","test":58,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"oKW9hdFuhNjfQ3LsDwwPFQ==","expected":"oKW9hdFuhNjfQ3LsDwwPFQ==","test":58,"type":"assert"}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3606): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"oKW9hdFuhNjfQ3LsDwwPFQ==","expected":"oKW9hdFuhNjfQ3LsDwwPFQ==","test":58,"type":"assert"}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"end","test":58}
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 3606): 
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{427ead18 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{43ce95e8 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{4408df88 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{438ec550 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
,I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42789588 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{435616f0 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{440c8158 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4201cbb0 type 2 android}
,D/ConnectivityService( 1015): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1015): sending alarm Alarm{4201c5a0 type 1 com.android.deskclock}
,I/ActivityManager( 1015): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4473 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1015): Done.
,D/ConnectivityService( 1015): Setting timer for 720seconds
,I/ActivityManager( 1015): Killing 3983:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1015): GC_CONCURRENT freed 2009K, 65% free 18073K/50348K, paused 28ms+9ms, total 129ms
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{427be088 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{447927f0 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match,
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{44702b58 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
,I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{446aa298 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
,I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{440be400 type 3 android}
,D/UdcCache:FPQuery( 1353): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1368): GC_CONCURRENT freed 1569K, 36% free 11063K/17224K, paused 3ms+6ms, total 63ms
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1252): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42211f10 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{4256cff8 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42862c70 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{41f99f48 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{425c1680 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42324278 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{440a6410 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{42855a70 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{4278c898 type 3 android}
,I/ProcessStatsService( 1015): Prepared write state in 35ms
,I/ProcessStatsService( 1015): Pruning old procstats: /data/system/procstats/state-2015-11-17-19-50-07.bin
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{41ffc0d8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{421fad48 type 2 android}
,D/ConnectivityService( 1015): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1015): sending alarm Alarm{421ee508 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{421e8108 type 3 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{421d3300 type 3 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{421bc220 type 0 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{4219d2b8 type 1 com.android.deskclock}
,D/ConnectivityService( 1015): Done.
,D/ConnectivityService( 1015): Setting timer for 720seconds
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1368): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1353): Aggregate from 1447852693951 (log), 1447851950591 (data)
,I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@447c9448 mBinding = false
,W/Settings( 1213): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1015): Message: 2
,W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1015): Sending off request.
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
,W/Settings( 1213): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 3662): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3662): Setting state to 13
I/BluetoothAdapterState( 3662): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3662): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3662): onBluetoothDisable()
I/BluetoothAdapterState( 3662): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3662): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3662): Scan Mode:21
D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3662): bta_jv_rfcomm_stop_server
E/bt-btif ( 3662): bta_jv_rfcomm_stop_server
E/bt-btif ( 3662): bta_jv_rfcomm_stop_server
E/bt-btif ( 3662): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 3662): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3662): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3662): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 3662): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3662): L2CAP - PSM: 0x0017 not found for deregistration
,D/btif_config_util( 3662): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
W/Settings( 1213): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1015): handleMessage: E msg.what=131084
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@447c9448 mBinding = false
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1015): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1015): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,W/Settings( 1213): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1015): Message: 60
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 12 -> 13
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): Message: 2
,D/BluetoothManagerService( 1015): Sending off request.
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 3662): onReceive
D/BluetoothMapService( 3662): STATE_TURNING_OFF removeTimeoutMsg:false
D/BluetoothMapService( 3662): MAP Service closeService in
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,D/CommandListener(  269): Clearing all IP addresses on wlan0
D/TCMD    (  456): NL - Read 60 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 21
,D/TCMD    (  456): Listening for incoming client connection request
,I/ActivityManager( 1015): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4583 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1015): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1015): connected time updated 1611672
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1015): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1015): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1079): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1015): Attempting to switch to ETHERNET
,D/WifiStateMachine( 1015): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1015): invokeExitMethods: DriverStartedState
,I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/BtOppRfcommListener( 3662): stopping Accept Thread
,I/BtOppRfcommListener( 3662): BluetoothSocket listen thread finished
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
,I/jxcore-log( 3606): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":59,"type":"assert"}
I/jxcore-log( 3606): 
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1015): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiP2pService( 1015): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
,D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiP2pService( 1015): P2pDisablingState
D/WifiP2pService( 1015): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): p2p socket connection lost
,D/WifiP2pService( 1015): P2pDisabledState
D/WifiStateMachine( 1015): handleMessage: E msg.what=131205
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,D/ConnectivityService( 1015): resetConnections(wlan0, 3)
D/NetUtils( 1015): android_net_utils_resetConnections in env=0x5fec96c8 clazz=0x9a900001 iface=wlan0 mask=0x3
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
V/NativeCrypto( 1368): Read error: ssl=0x6313b0a0: I/O error during system call, Connection timed out
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
V/NativeCrypto( 1368): SSL shutdown failed: ssl=0x6313b0a0: I/O error during system call, Broken pipe
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiP2pService( 1015): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
,D/CommandListener(  269): Clearing all IP addresses on wlan0
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/SBar.NetworkController( 1079): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
D/WifiStateMachine( 1015): stopping supplicant
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
,D/WifiStateMachine( 1015): setWifiState: disabling
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/WifiStateMachine( 1015): handleMessage: X
I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1079): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
W/XTWiFiOS( 1241): Active network info is not available
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
E/XTCC-3.0.0.2(  479): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  479): [WwanPosMgr] handleConnectivtyStatusChange failed
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
E/XTCC-3.0.0.2(  479): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  479): [CSMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
D/TCMD    (  456): NL - Read 68 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
I/wpa_supplicant( 3742): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  271):  STA Disconnected !!
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): get_property_value, Enter
I/MDMCTBK (  271): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  271): get_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  271): Event received = CTRL-EVENT-STATE-CHANGE 
I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine( 1015): handleMessage: E msg.what=147460
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
I/ModemStatsDSDetect( 1252): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=0
D/Tethering( 1015): InitialState.processMessage what=4
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
W/bt-btif ( 3662): ag scb idx 1 not allocated
E/bt-btif ( 3662): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3662): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3662): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3662): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3662): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3662): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3662): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_hwcfg( 3662): hw_epilog_process
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
I/ModemStatsDSDetect( 1252): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/ModemStatsDSDetect( 1252): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1252): onReceive() - done, currentInetCondition=0
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/wpa_supplicant( 3742): eap_proxy Deinitialzed
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  271): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
I/bt_hwcfg( 3662): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3662): bt_hc_worker_thread exiting
D/bt_userial_mct( 3662): userial_close
I/bt_userial_mct( 3662): exiting userial_read_thread
,D/bt_userial_mct( 3662): Leaving userial_evt_read_thread()
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothPbapService( 3662): action: android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42300068:true
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
,D/BluetoothManagerService( 1015): Message: 30
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
D/TCMD    (  456): Listening for incoming client connection request
I/wpa_supplicant( 3742): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  271): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  271): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  271):  Wpa Supplicant Exiting !!
D/MDMCTBK (  271): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  271): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  271): wifi_close_sockets: Exit
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
D/WifiStateMachine( 1015): handleMessage: E msg.what=147458
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): Supplicant connection lost
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): Message: 30
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4583): Adding local MAP profile
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothMap( 4583): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1015): Message: 30
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
,D/BluetoothManagerService( 1015): Message: 30
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
D/LocalBluetoothProfileManager( 4583): LocalBluetoothProfileManager construction complete
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
D/DockEventReceiver( 4583): finishStartingService: stopping service
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService( 1015): New client listening to asynchronous messages
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothInputDevice( 4583): Proxy object connected
D/HidProfile( 4583): Bluetooth service connected
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothPan( 4583): BluetoothPAN Proxy object connected
D/PanProfile( 4583): Bluetooth service connected
D/BluetoothMap( 4583): Proxy object connected
D/MapProfile( 4583): Bluetooth service connected
D/BluetoothMap( 4583): getConnectedDevices()
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMap( 4583): Bluetooth is Not enabled
V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
,I/ActivityManager( 1015): Killing 4053:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AuthorizationBluetoothService( 1368): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/BTSNOOP-DISP( 3662): btsnoop_close
I/bt_vendor( 3662): cleanup
I/bt_hwcfg( 3662): Starting hciattach daemon
,I/bt_hwcfg( 3662): try to set false
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
I/GKI_LINUX( 3662): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3662): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 3662): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3662): Received stop request...Stopping profile...
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothHeadset( 1015): Proxy object disconnected
D/BluetoothHeadset( 1230): Proxy object disconnected
D/BluetoothHeadset( 1230): Proxy object disconnected
D/BluetoothHeadset( 1230): Proxy object disconnected
D/A2dpService( 3662): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3662): Exit Disconnected: -1
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothA2dp( 1015): Proxy object disconnected
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterState( 3662): Stopping profile services that were post enabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
W/BluetoothHeadsetServiceJni( 3662): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3662): Cleaning up Bluetooth Handsfree callback object
D/HidService( 3662): Received stop request...Stopping profile...
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothInputDevice( 4583): Proxy object disconnected
D/HidProfile( 4583): Bluetooth service disconnected
D/HealthService( 3662): Received stop request...Stopping profile...
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/PanService( 3662): Received stop request...Stopping profile...
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1015): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1015): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4319eea8
D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected
D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 3662): handleDebugAction() action=null
D/BluetoothPan( 4583): BluetoothPAN Proxy object disconnected
D/PanProfile( 4583): Bluetooth service disconnected
D/BtGatt.GattService( 3662): Received stop request...Stopping profile...
D/BtGatt.GattService( 3662): stop()
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/GKI_LINUX( 3662): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/GKI_LINUX( 3662): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3662): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothMapService( 3662): Received stop request...Stopping profile...
D/BluetoothMapService( 3662): stop()
D/BluetoothMapService( 3662): MAP Service closeService in
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothMap( 4583): Proxy object disconnected
D/MapProfile( 4583): Bluetooth service disconnected
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3662): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3662): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3662): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3662): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3662): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3662): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3662): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3662): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3662): cleanup()
D/BluetoothMapService( 3662): MAP Service closeService in
D/BluetoothAdapterState( 3662): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3662): Setting state to 10
I/BluetoothAdapterState( 3662): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3662): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3662): Entering OffState
D/BluetoothManagerService( 1015): Message: 60
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1015): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=false
D/BluetoothPan( 1015): onBluetoothStateChange on: false
D/BluetoothHeadset( 1230): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1015): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
D/BluetoothPbap( 4583): onBluetoothStateChange: up=false
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothPan( 4583): onBluetoothStateChange on: false
D/BluetoothInputDevice( 4583): onBluetoothStateChange: up=false
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothMap( 4583): onBluetoothStateChange: up=false
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1015): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 9 receivers.
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@447c9448 mBinding = false
D/BluetoothManagerService( 1015): Sending unbind request.
D/BluetoothAdapterService( 3662): Cleaning up adapter native....
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 3662): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3662): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3662): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3662): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3662): Done cleaning up adapter native....
,D/BluetoothAdapter( 1079): 1108301592: getState() :  mService = null. Returning STATE_OFF
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService(1106826840)( 3662): ****onDestroy()********
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
D/BtGatt.GattService( 3662): cleanup()
W/bt-btif ( 3662): GATTC Module not enabled/already disabled
W/bt-btif ( 3662): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1198): 1109961976: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1198): 1109961976: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
D/WifiStateMachine( 1015): setWifiState: disabled
D/WifiStateMachine( 1015): transitionTo: destState=InitialState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine( 1015): invokeEnterMethods: InitialState
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1079): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1241): Active network info is not available
W/Settings( 4108): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/XTCC-3.0.0.2(  479): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  479): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/ContextImpl( 4583): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
W/Settings( 1198): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/DockEventReceiver( 4583): finishStartingService: stopping service
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapter( 4583): 1106868840: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
V/BluetoothFtpReceiver( 3662): BluetoothFtpReceiver Stop Service
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
E/XTCC-3.0.0.2(  479): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  479): [CSMgr] handleConnectivtyStatusChange failed
V/BluetoothFtpService( 3662): Ftp Service onDestroy
V/BluetoothFtpService( 3662): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3662): Shutdown
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/AuthorizationBluetoothService( 1368): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,I/ActivityManager( 1015): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4612 uid=10016 gids={50016, 3002}
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
I/ActivityManager( 1015): Killing 4108:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothAdapter( 4583): 1106868840: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
,D/Checkin ( 4612): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,I/ActivityManager( 1015): Killing 4139:android.process.acore/u0a10 (adj 15): empty #9
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/jxcore-log( 3606): The client has disconnected!
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Turning radios to false
I/jxcore-log( 3606): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3606): toggleBluetooth - 
I/jxcore-log( 3606): 
D/WifiService( 1015): setWifiEnabled: false pid=3606, uid=10383
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3606): toggleWiFi
I/jxcore-log( 3606): 
I/chromium( 3606): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
D/TCMD    (  456): NL - Read 444 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 17
D/TCMD    (  456): Listening for incoming client connection request
I/MDMCTBK (  271): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  271): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  456): NL - Read 1000 bytes from update socket.
D/TCMD    (  456): NL - message type is RTM_NEWLINK
,D/TCMD    (  456): Listening for incoming client connection request
,D/NetlinkEvent(  269): Unexpected netlink message. type=0x11
W/Netd    (  269): No subsystem found in netlink event
,D/TCMD    (  456): NL - Read 444 bytes from update socket.
D/TCMD    (  456): NL - ignore NL message, type = 17
D/TCMD    (  456): Listening for incoming client connection request
I/MDMCTBK (  271): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  271): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  271): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  271): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  271): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
I/MDMCTBK (  271): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  271): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  271): set_property_value, Enter
I/MDMCTBK (  271): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  271): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  271): set_property_value, Exit
E/MDMCTBK (  271): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196614
D/WifiStateMachine( 1015): processMsg: InitialState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
D/WifiStateMachine( 1015): processMsg: InitialState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/Checkin ( 2118): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs],
,I/MDMCTBK (  271): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  271): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
,I/MDMCTBK (  271): checkDefaultInst, pid match
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1015): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
W/XTWiFiOS( 1241): Active network info is not available
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/PollingManager( 1522): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,E/ActivityThread( 1522): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
D/Tethering( 1015): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
W/XTWiFiOS( 1241): No entry in secure settings for enhanced location services: false
D/PollingManager( 1522): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1522): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1522): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1522): [debug] > CusSM.onRadioDown
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1241): Active network info is not available
,I/SBar.NetworkController( 1079): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1079): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1079): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4646 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1230): Column apn id key is 'apn_id'
,V/MmsConfig( 4646): mnc/mcc: 
V/MmsConfig( 4646): tag: bool value: enabledMMS - true
V/MmsConfig( 4646): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 4646): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4646): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4646): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4646): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4646): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4646): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4646): tag: int value: recipientLimit - 20
V/MmsConfig( 4646): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 4646): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4646): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4646): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4646): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4646): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4646): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 4646): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4646): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1015): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4665 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1015): Killing 4159:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4665): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4665): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4665): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4665): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4678 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3508:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4692 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 4175:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4692): Binding Chromium to main looper Looper (main, tid 1) {41f7d188}
,I/LibraryLoader( 4692): Expected native library version number "",actual native library version number ""
,I/chromium( 4692): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4692): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4692): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4692): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4692): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4692): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4692): Local Branch: 
I/Adreno-EGL( 4692): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4692): Local Patches: NONE
I/Adreno-EGL( 4692): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4692): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4692): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  260): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  260): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4692): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4692): Starting up...
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4734 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1015): Killing 4473:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1015): GC_EXPLICIT freed 1897K, 65% free 18062K/50348K, paused 3ms+9ms, total 90ms
,I/ImageResourceManager( 4734): ImageResourceManager: uninitalized
,I/ActivityManager( 1015): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4753 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/iu.Environment( 4734): update battery state; isPlugged? true*
,I/iu.Environment( 4734): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4734): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1015): Killing 3662:com.android.bluetooth/1002 (adj 15): empty #9
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1015): Killing 4612:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
W/ContextImpl( 1213): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/iu.Environment( 1353): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/iu.UploadsManager( 1353): num queued entries: 0
I/iu.UploadsManager( 1353): num updated entries: 0
I/iu.SyncManager( 1353): NEXT; no task
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
D/MobileConnectivityChangeReceiver( 4665): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4665): onReceive CONNECTIVITY_CHANGE networkType=1
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
,I/jxcore-log( 3606): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3606): 
I/iu.Environment( 4734): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
D/DEBUG   ( 1522): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/ContextImpl( 1522): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1522): bindWebServices(): registering our AIDL callback...
I/SundryService( 1522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1522): ServiceHandler.handleMessage: mWaitCount=0
D/EmailService.MarketingOptInSetter( 1522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1522): onServiceConnected()
D/GetNotificationsWS( 1522): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 1522): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 370K, 5% free 16401K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 4734): Grow heap (frag case) to 19.786MB for 1821008-byte allocation
,I/iu.UploadsManager( 4734): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 4734): GC_FOR_ALLOC freed 14K, 5% free 18187K/19004K, paused 12ms, total 12ms
,I/iu.UploadsManager( 4734): End new media; added: 0, uploading: 0, time: 48 ms
,I/iu.FingerprintManager( 4734): Start processing all media
,I/iu.FingerprintManager( 4734): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4734): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4734): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4734): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4734): Finished generating fingerprints; 0.017 seconds
,I/iu.FingerprintManager( 4734):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 4753): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/WifiP2pService( 1015): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,V/AlarmManager( 1015): sending alarm Alarm{4409f260 type 2 com.android.keyguard}

```
