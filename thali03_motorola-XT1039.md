#### Test 50650278654db8c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1022): sending alarm Alarm{43db4900 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3411): 
D/AndroidRuntime( 3411): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3411): CheckJNI is OFF
D/dalvikvm( 3411): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3411): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3411): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3411): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3411): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3411): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3411): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3411): failed to load memtrack module: -2
D/AndroidRuntime( 3411): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3411
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3427 uid=10104 gids={50104, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3411): Shutting down VM
D/dalvikvm( 3411): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3427): Binding Chromium to main looper Looper (main, tid 1) {41f85ae8}
I/LibraryLoader( 3427): Expected native library version number "",actual native library version number ""
I/chromium( 3427): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3427): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ccd0f0:true
D/BluetoothAdapter( 3427): 1106879320: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3427): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3427): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3427): Local Branch: 
I/Adreno-EGL( 3427): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3427): Local Patches: NONE
I/Adreno-EGL( 3427): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3427): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3427): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3427): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3427): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3427): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3427): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3427): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3427): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3427): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3427): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3427): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3427): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3427): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3427): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3427): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3427): CordovaWebView is running on device made by: motorola
,D/dalvikvm( 1022): GC_EXPLICIT freed 22327K, 65% free 17705K/50196K, paused 4ms+9ms, total 135ms
,D/OpenGLRenderer( 3427): Enabling debug mode 0
,W/AwContents( 3427): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3427): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,520
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +492ms (total +520ms)
,D/JsMessageQueue( 3427): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3427): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8a1f8
,D/dalvikvm( 3427): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8a1f8
,D/jxcore_app_log( 3427): JniHelper::setJavaVM(0x415d6fa8), pthread_self() = 1614333104
,D/JX-Cordova( 3427): jxcore cordova android initializing
,D/dalvikvm( 3427): GC_CONCURRENT freed 2815K, 17% free 14361K/17224K, paused 3ms+2ms, total 60ms
,D/dalvikvm( 3427): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 113K, 17% free 14362K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 304K, 17% free 14427K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 16.260MB for 144892-byte allocation
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 268K, 17% free 14464K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 16.365MB for 217334-byte allocation
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 370K, 18% free 14538K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 16.541MB for 325996-byte allocation
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 572K, 19% free 14660K/17904K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 16.815MB for 488990-byte allocation
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 870K, 20% free 14836K/18384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 17.221MB for 733480-byte allocation
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 1292K, 21% free 15094K/19104K, paused 26ms, total 26ms
,D/dalvikvm( 3427): GC_CONCURRENT freed 1676K, 20% free 15466K/19104K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 3427): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3427): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 375K, 20% free 15430K/19104K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 18.675MB for 1650320-byte allocation
,D/dalvikvm( 3427): GC_CONCURRENT freed 1583K, 23% free 15983K/20716K, paused 2ms+3ms, total 35ms
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 1490K, 23% free 16083K/20716K, paused 30ms, total 31ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 20.100MB for 2475476-byte allocation
,D/dalvikvm( 3427): GC_CONCURRENT freed 241K, 21% free 18377K/23136K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 3427): GC_CONCURRENT freed 4406K, 27% free 17057K/23136K, paused 2ms+7ms, total 43ms
,D/dalvikvm( 3427): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/dalvikvm-heap( 3427): Grow heap (frag case) to 22.231MB for 3713210-byte allocation
,D/dalvikvm( 3427): GC_CONCURRENT freed 363K, 24% free 20556K/26764K, paused 5ms+7ms, total 49ms
,D/dalvikvm( 3427): GC_FOR_ALLOC freed 3160K, 33% free 17999K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 3427): Initializing JXcore engine
,W/jxcore-log( 3427): JXcore engine is ready
,D/dalvikvm( 3427): GC_CONCURRENT freed 361K, 23% free 20616K/26764K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3427): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 3427): Starting JXcore engine
,W/jxcore-log( 3427): Platform android
W/jxcore-log( 3427): 
,W/jxcore-log( 3427): Process ARCH arm
W/jxcore-log( 3427): 
,I/jxcore-log( 3427): JXcore Cordova bridge is ready!
I/jxcore-log( 3427): 
,W/jxcore-log( 3427): JXcore engine is started
,I/chromium( 3427): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3427): Toggling radios to true
I/jxcore-log( 3427): 
,D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1022): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1022): Message: 1
,D/BluetoothManagerService( 1022): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1220): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1248): Active network info is not available
,I/ActivityManager( 1022): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3472 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1220): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1022): New client listening to asynchronous messages
D/WifiService( 1022): setWifiEnabled: true pid=3427, uid=10104
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1022): setting operational mode to 1
D/WifiStateMachine( 1022): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1022): processMsg: InitialState
,W/Settings( 1220): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3427): Radios toggled
I/jxcore-log( 3427): 
,W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3427): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3427): 
W/XTWiFiOS( 1248): Active network info is not available
,W/Settings( 1220): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3427): Perf Test app loaded loaded
I/jxcore-log( 3427): 
,I/jxcore-log( 3427): check test folder
I/jxcore-log( 3427): 
,I/jxcore-log( 3427): found test : ./testFindPeers.js
I/jxcore-log( 3427): 
,I/jxcore-log( 3427): found test : ./testSendData.js
I/jxcore-log( 3427): 
D/AdapterServiceConfig( 3472): Adding HeadsetService
D/AdapterServiceConfig( 3472): Adding A2dpService
D/AdapterServiceConfig( 3472): Adding HidService
D/AdapterServiceConfig( 3472): Adding HealthService
D/AdapterServiceConfig( 3472): Adding PanService
D/AdapterServiceConfig( 3472): Adding GattService
,D/AdapterServiceConfig( 3472): Adding BluetoothMapService
,D/BluetoothAdapterService( 3472): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1022): Message: 20
,D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42434060:true
,D/BluetoothAdapterState( 3472): make
,I/BluetoothAdapterState( 3472): Entering OffState
,I/bluedroid( 3472): init
,I/bte_conf( 3472): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3472): get_profile_interface socket
,D/BluetoothManagerService( 1022): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1022): Message: 40
,D/BluetoothManagerService( 1022): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3472): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3472): config_hci_snoop_log
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1022): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1022): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterProperties( 3472): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1022): Bluetooth Adapter name changed to XT1039
,D/BluetoothAdapterProperties( 3472): Name is: XT1039
,D/BluetoothManagerService( 1022): Stored Bluetooth name: XT1039
,D/BluetoothAdapterState( 3472): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3472): Setting state to 11
I/BluetoothAdapterState( 3472): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3472): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1022): Message: 60
,D/BluetoothManagerService( 1022): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothBondStateMachine( 3472): make
,D/BluetoothManagerService( 1022): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3472): StableState(): Entering Off State
,I/ActivityManager( 1022): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3504 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1022): Proxy object connected
D/HeadsetService( 3472): Received start request. Starting profile...
D/BluetoothHeadset( 1238): Proxy object connected
D/BluetoothHeadset( 1238): Proxy object connected
D/BluetoothHeadset( 1238): Proxy object connected
I/BluetoothHeadsetServiceJni( 3472): classInitNative: succeeds
D/HeadsetStateMachine( 3472): Version 1.6
D/HeadsetStateMachine( 3472): make
,I/BluetoothAdapterState( 3472): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3472): get_profile_interface handsfree
,D/BluetoothA2dp( 1022): Proxy object connected
D/A2dpService( 3472): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3472): classInitNative: succeeds
,V/Avrcp   ( 3472): make
,I/bluedroid( 3472): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3472): classInitNative: succeeds
,D/A2dpStateMachine( 3472): make
,I/bluedroid( 3472): get_profile_interface a2dp
,I/GKI_LINUX( 3472): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3472): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3472): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3472): classInitNative: succeeds
D/HidService( 3472): Received start request. Starting profile...
,I/bluedroid( 3472): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3472): classInitNative: succeeds
,D/HealthService( 3472): Received start request. Starting profile...
,I/bluedroid( 3472): get_profile_interface health
,I/BluetoothPanServiceJni( 3472): classInitNative(L105): succeeds
,D/PanService( 3472): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3472): initializeNative(L110): pan
,I/bluedroid( 3472): get_profile_interface pan
,D/BluetoothTethering( 1022): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1022): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@42062d48
,I/BtGatt.JNI( 3472): classInitNative(L684): classInitNative: Success!
,D/BluetoothPan( 1022): BluetoothPAN Proxy object connected
,D/BtGatt.DebugUtils( 3472): handleDebugAction() action=null
D/BtGatt.GattService( 3472): Received start request. Starting profile...
D/BtGatt.GattService( 3472): start()
,I/bluedroid( 3472): get_profile_interface gatt
,D/BluetoothMapService( 3472): Received start request. Starting profile...
,D/BluetoothMapService( 3472): start()
,D/HeadsetPhoneState( 3472): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3472): onSignalStrengthsChanged..for signal  prevSignal=0
D/HeadsetPhoneState( 3472): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3472): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3472): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3472): enable
,I/bt_hci_bdroid( 3472): init
I/bt_vendor( 3472): bt-vendor : init
I/bt_hci_bdroid( 3472): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3472): userial_init
I/bt_hwcfg( 3472): Starting hciattach daemon
I/bt_hwcfg( 3472): try to set false
,I/bt_hci_bdroid( 3472): bt_hc_worker_thread started
I/bt_hwcfg( 3472): Starting hciattach daemon
,I/bt_hwcfg( 3472): try to set true
,I/chromium( 3427): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 1022): Killing 3212:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/qcom-bluetooth( 3533): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1022): New client listening to asynchronous messages
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
D/TCMD    (  442): NL - Read 1004 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/MDMCTBK (  274): send SAR ctrl over QMI
D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1022): InitialState.processMessage what=4
D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/qcom-bluetooth( 3542): /system/etc/init.qcom.bt.sh: Transport : smd 
D/TCMD    (  442): NL - Read 1004 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
I/qcom-bluetooth( 3543): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QsoftapCmd(  27,2): Got softap fwreload command we are passing on
D/SoftapController(  272): Softap fwReload - Ok
,I/qcom-bluetooth( 3545): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
V/BluetoothFtpReceiver( 3472): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/qcom-bluetooth( 3547): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring down wlan0
,D/AuthorizationBluetoothService( 1373): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 3548): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiHW  ( 1022): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1022): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1022): setWifiState: enabling
,D/WifiStateMachine( 1022): Supplicant start successful
,W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
E/Diag_Lib( 3550): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3550): Setting internal use port to rmnet0
E/Diag_Lib( 3550):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3550): Failed on DIAG init
D/WifiMonitor( 1022): startMonitoring(wlan0) with mConnected = false
E/Diag_Lib( 3550): linux_qmi_qmux_if_client_get_proc_name: pid=3550, proc_name=hci_qcomm_init
E/Diag_Lib( 3550): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3550): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
,E/Diag_Lib( 3550): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3550): qmi_client [3550]: successfully connected to server, attempt=1
E/Diag_Lib( 3550): linux_qmi_qmux_if_client_get_client_id [3550]: qmux_client_id=13
E/Diag_Lib( 3550): qmi_client [3550] 13: qmux_client ID is initialized
E/Diag_Lib( 3550): qmi_client [3550] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3550): qmi_client [3550] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3550): qmi_client [3550] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3550): Sending signal ...... to read cmd data 
E/Diag_Lib( 3550): qmi error code.........:0
E/Diag_Lib( 3550): qmi sys error code.........:0
E/Diag_Lib( 3550): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3550): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3550): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3550): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3550): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3550): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3550): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3550): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3550): qmi_init:  Created client handle b7a2d788
E/Diag_Lib( 3550): qmi_client [3550] 13: sending 880 bytes on fd = 8
,W/XTWiFiOS( 1248): Active network info is not available
E/Diag_Lib( 3550): qmi_client [3550] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3550): Sending signal ...... to read cmd data 
E/Diag_Lib( 3550): qmi error code.........:0
,E/Diag_Lib( 3550): qmi sys error code.........:0
E/Diag_Lib( 3550): Setting the api flag to : 1
,E/Diag_Lib( 3550): qmi_client [3550] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3552): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3552): rfkill: Cannot open RFKILL control device
I/rmt_storage(  373): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84621d0
I/rmt_storage(  373): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  373): wakelock acquired: 1, error no: 42
I/rmt_storage(  373): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1203363272)
E/Diag_Lib( 3550): qmi_client [3550] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3550):  API Flag .............. 1 
E/Diag_Lib( 3550):  Message ID ............... 92 
D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
,E/Diag_Lib( 3550): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3550): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3550): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3550): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3550): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3550): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3550): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3550): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3550): qmi_client [3550] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3550): qmi_client [3550] 13: Received 880 bytes on fd = 8
,E/Diag_Lib( 3550): Sending signal ...... to read cmd data 
E/Diag_Lib( 3550): qmi error code.........:0
E/Diag_Lib( 3550): qmi sys error code.........:0
E/Diag_Lib( 3550): qmi_release: Released client handle ff
E/Diag_Lib( 3550): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/,Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3550): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3550): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3550): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3550): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3550): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3550): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3550): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3550): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3550): qmi_client [3550] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3550): qmi_client [3550] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3550): Sending signal ...... to read cmd data 
E/Diag_Lib( 3550): qmi error code.........:0
E/Diag_Lib( 3550): qmi sys error code.........:0
E/Diag_Lib( 3550): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3550] 13
E/Diag_Lib( 3550): qmi_client [3550] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3550): qmi_client [3550] 13: failed to locate client data
E/Diag_Lib( 3550): qmi_client [3550] 13: calling release of fd=8
,E/Diag_Lib( 3550): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  373): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  373): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
E/Diag_Lib( 3552): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3552): Setting internal use port to rmnet0
,I/rmt_storage(  373): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1203363272) wakelock released: 1, error no: 0,
I/rmt_storage(  373): 
,I/rmt_storage(  373): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb84621d0
,E/wpa_supplicant( 3552): baseband property is set to [msm]
,I/qcom-bluetooth( 3556): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,E/wpa_supplicant( 3552):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 3552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3552): card_info[i].card_state: 0x2
E/wpa_supplicant( 3552): card_info[i].error_code: 0x3
E/wpa_supplicant( 3552): SIM/USIM not ready
E/wpa_supplicant( 3552): Error while reading SIM card status
,I/qcom-bluetooth( 3557): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
I/bt_hwcfg( 3472): bluetooth satus is on
I/GKI_LINUX( 3472): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3472): btu_task pending for preload complete event
D/bt_userial_mct( 3472): userial_open(port:0)
,I/bt_userial_vendor( 3472): Done intiailizing UART
I/bt_userial_vendor( 3472): Done intiailizing UART
I/bt_userial_mct( 3472): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3472): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3472): Entering userial_read_thread()
I/bt-btu  ( 3472): btu_task received preload complete event
E/wpa_supplicant( 3552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3552): card_info[i].card_state: 0x2
,E/wpa_supplicant( 3552): card_info[i].error_code: 0x3
E/wpa_supplicant( 3552): SIM/USIM not ready
,I/wpa_supplicant( 3552): eap_proxy: Card not ready
I/        ( 3472): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3472): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3472): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3472): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3472): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3472): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3472): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3472): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3472): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3472): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3472): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 3472): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3472): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3472): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3472): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3472): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f119049 
,E/bt-btm  ( 3472): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f119049 ,
,E/bt-btif ( 3472): Calling BTA_HhEnable
E/bt-btif ( 3472): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3472): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3472): Name is: XT1039
,D/BluetoothManagerService( 1022): Bluetooth Adapter name changed to XT1039
I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService( 1022): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3472): Scan Mode:21
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3472): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3472): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3472): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
,I/bte_conf( 3472): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3472): hci lib postload completed
,I/bte_conf( 3472): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 3472): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3472): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3472): ScanMode =  21
D/BluetoothAdapterProperties( 3472): State =  11
D/BluetoothAdapterProperties( 3472): Setting state to 12
,I/BluetoothAdapterState( 3472): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3472): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1022): Message: 60
D/BluetoothManagerService( 1022): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1022): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,I/BluetoothAdapterState( 3472): Entering On State
,D/BluetoothAdapterService(1106867024)( 3472): Get Bonded Devices being called
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3472): Discoverable Timeout:120
,D/BluetoothAdapterService(1106867024)( 3472): Get Bonded Devices being called
D/BluetoothPan( 1022): onBluetoothStateChange on: true
,D/BluetoothA2dp( 1022): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1022): onBluetoothStateChange: up=true
,D/BluetoothManagerService( 1022): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1022): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService(1106867024)( 3472): Get Bonded Devices being called
D/BluetoothManagerService( 1022): Message: 40
,D/BluetoothManagerService( 1022): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3472): onReceive
,D/BluetoothMapService( 3472): STATE_ON
,D/BluetoothMapService( 3472): Map Service startRfcommSocketListener
,D/BluetoothMapService( 3472): Map Service initSocket
,D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3472): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3472): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3472): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothMapService( 3472): Accepting socket connection...
,I/qcom-bt-wlan-coex( 3571): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/BluetoothAdapterProperties( 3472): Scan Mode:21
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothManagerService( 1022): Message: 20
,D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42133d60:true
,D/BluetoothPbapService( 3472): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3472): Handler(): got msg=1
,D/LocalBluetoothProfileManager( 3504): Adding local A2DP profile
,D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1022): Message: 30
,W/BluetoothAdapter( 3472): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3472): SOCK FLAG = 1 ***********************
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3504): Adding local HEADSET profile
I/wpa_supplicant( 3552): Long line in configuration file truncated
D/BluetoothManagerService( 1022): Message: 30
,I/wpa_supplicant( 3552): rfkill: Cannot open RFKILL control device
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
,D/BluetoothManagerService( 1022): Message: 30
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1022): Message: 30
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3504): Adding local MAP profile
D/BluetoothMap( 3504): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1022): Message: 30
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
E/wpa_supplicant( 3552): COUNTRY Code Recived
D/BluetoothManagerService( 1022): Message: 30
E/wpa_supplicant( 3552): COUNTRY Code Recived -COUNTRY PL
,W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
E/wpa_supplicant( 3552): baseband property is set to [msm]
D/LocalBluetoothProfileManager( 3504): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3504): finishStartingService: stopping service
E/wpa_supplicant( 3552):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3552): card_info[i].card_state: 0x2
E/wpa_supplicant( 3552): card_info[i].error_code: 0x3
E/wpa_supplicant( 3552): SIM/USIM not ready
E/wpa_supplicant( 3552): Error while reading SIM card status
D/BluetoothAdapterService(1106867024)( 3472): Get Bonded Devices being called
E/wpa_supplicant( 3552): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3552): card_info[i].card_state: 0x2
E/wpa_supplicant( 3552): card_info[i].error_code: 0x3
E/wpa_supplicant( 3552): SIM/USIM not ready
I/wpa_supplicant( 3552): eap_proxy: Card not ready
D/BluetoothA2dp( 3504): Proxy object connected
D/A2dpProfile( 3504): Bluetooth service connected
D/BluetoothHeadset( 3504): Proxy object connected
D/HeadsetProfile( 3504): Bluetooth service connected
D/WifiStateMachine( 1022): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1022): invokeExitMethods: InitialState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1022): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131144
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): deferMessage: msg=131144
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131085
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): deferMessage: msg=131085
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131149
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1022): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131145
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131146
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147457
D/WifiStateMachine( 1022): processMsg: SupplicantStartingState
D/WifiStateMachine( 1022): Supplicant connection established
D/WifiStateMachine( 1022): setWifiState: enabled
D/BluetoothInputDevice( 3504): Proxy object connect,ed
D/HidProfile( 3504): Bluetooth service connected
I/SBar.NetworkController( 1083): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1248): Active network info is not available
D/BluetoothPan( 3504): BluetoothPAN Proxy object connected
D/PanProfile( 3504): Bluetooth service connected
D/WifiConfigStore( 1022): Loading config and enabling all networks
D/BluetoothMap( 3504): Proxy object connected
D/MapProfile( 3504): Bluetooth service connected
D/BluetoothMap( 3504): getConnectedDevices()
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1083): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/BluetoothPbap( 3504): Proxy object connected
D/PbapServerProfile( 3504): Bluetooth service connected
E/WifiConfigStore( 1022): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/wpa_supplicant( 3552): COUNTRY Code Recived -COUNTRY PL
D/WifiStateMachine( 1022): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1022): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine( 1022): invokeEnterMethods: SupplicantStartedState
D/WifiStateMachine( 1022): invokeEnterMethods: DriverStartedState
D/WifiStateMachine( 1022): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3552): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3552): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1022): Attempting to reconnect to wifi network ..
V/BluetoothFtpReceiver( 3472): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3472): BluetoothFtpReceiver Start Service
D/WifiStateMachine( 1022): transitionTo: destState=DisconnectedState
D/AuthorizationBluetoothService( 1373): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1373): Proximity feature is not enabled.
V/BluetoothFtpService( 3472): Ftp Service onCreate
I/BluetoothFtpService( 3472): FFFFFtp Service onCreate
V/BluetoothFtpService( 3472): Starting FTP service
V/BluetoothFtpService( 3472): Ftp Service onStartCommand
V/BluetoothFtpService( 3472): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3472): Handler(): got msg=1
V/BluetoothFtpService( 3472): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3472): Ftp Service initSocket
,D/WifiP2pService( 1022): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): moveDeferredMessageAtFrontOfQueue; what=131085
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine( 1022): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1022): invokeEnterMethods: DisconnectedState
W/BluetoothAdapter( 3472): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 3472): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3472): SOCK FLAG = 3 ***********************
E/BluetoothServiceJni( 3472): SOCK FLAG = 0 ***********************
V/BluetoothFtpService( 3472): Succeed to create listening socket on channel 20
I/BtOppRfcommListener( 3472): Accept thread started.
V/BluetoothFtpService:RfcommSocketAcceptThread( 3472): Run Accept thread
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131144
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131085
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/CommandListener(  272): Setting iface cfg
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): handleMessage: X
D/CommandListener(  272): Trying to bring up p2p0
D/WifiStateMachine( 1022): handleMessage: E msg.what=131152
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): set country code PL
E/wpa_supplicant( 3552): COUNTRY Code Recived
E/wpa_supplicant( 3552): COUNTRY Code Recived
,D/WifiMonitor( 1022): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1022): P2pEnablingState
D/WifiP2pService( 1022): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2p socket connection successful
D/WifiP2pService( 1022): P2pEnabledState
,D/WifiP2pService( 1022): sending p2p connection changed broadcast
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131162
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): set frequency band 2
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131167
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1022): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=143371
D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiP2pService( 1022): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1022): MCC mode enabled 0
D/WifiP2pService( 1022): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1022): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1022): InactiveState
D/WifiP2pService( 1022): InactiveState{ when=-24ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-24ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): InactiveState{ when=-25ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-25ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3552): COUNTRY Code Recived
,E/wpa_supplicant( 3552): COUNTRY Code Recived
D/WifiP2pService( 1022): InactiveState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): wifi_connect_to_supplicant, current pid is = 274
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  274): wifi_close_sockets: Exit
,E/MDMCTBK (  274): Attach monitor thread
I/MDMCTBK (  274): createWifiMonitorThread: Started the wifi monitor thread -1208311088
,D/MDMCTBK (  274): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
,D/TCMD    (  442): Listening for incoming client connection request
,D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1022): InactiveState{ when=0 what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledStateupdate channel list
,D/Checkin ( 2026): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/TCMD    (  442): NL - Read 56 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
I/wpa_supplicant( 3551): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3551): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 06:7c:34:12:7f:81
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 06:7c:34:12:7f:81
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81,
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81,
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5,
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5,
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:96
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 a0:c5:62:7a:49:96
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 64:7c:34:b0:03:6e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 64:7c:34:b0:03:6e
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 b8:bc:1b:5a:18:00
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 b8:bc:1b:5a:18:00,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
,I/wpa_supplicant( 3552): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1022): processMsg: DisconnectedState,
,E/wpa_supplicant( 3552): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,I/wpa_supplicant( 3552): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3552): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  442): NL - Read 312 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 192 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 68 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
,D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3552): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
,D/TCMD    (  442): NL - Read 80 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 80 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/TCMD    (  442): NL - Read 68 bytes from update socket.
,D/TCMD    (  442): NL - message type is RTM_NEWLINK,
,D/TCMD    (  442): Listening for incoming client connection request,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: DisconnectedState
,D/WifiStateMachine( 1022): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 3552): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 3552): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  442): NL - Read 1000 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
,D/TCMD    (  442): Listening for incoming client connection request
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19,
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23,
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1208315192
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter,
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19,
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
,E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147459
D/WifiStateMachine( 1022): processMsg: DisconnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): Network connection established
,D/WifiStateMachine( 1022): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1022): transitionTo: destState=ObtainingIpState
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1022): invokeExitMethods: DisconnectedState
,D/Tethering( 1022): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1022): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1022): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-41ms what=147462 obj=android.net.wifi.StateChangeResult@420b5ed0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131101
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
,D/WifiStateMachine( 1022): ObtainingIpState{ when=-21ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@43e360e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1022): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4471db80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4471db80 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/WifiStateMachine( 1022): handleMessage: E msg.what=147461
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/TCMD    (  442): NL - Read 56 bytes from update socket.
D/TCMD    (  442): NL - message type is RTM_NEWLINK
D/TCMD    (  442): Listening for incoming client connection request
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 a0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 a0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 b8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 b8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiP2pService( 1022): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4228ff70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1022): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4228ff70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4228ff70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): handleMessage: X
,D/TCMD    (  442): NL - Read 60 bytes from update socket.
D/TCMD    (  442): NL - ignore NL message, type = 20
,D/TCMD    (  442): Listening for incoming client connection request
,D/WifiStateMachine( 1022): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=196613
D/WifiStateMachine( 1022): processMsg: ObtainingIpState
D/WifiStateMachine( 1022): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,D/WifiStateMachine( 1022): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1022): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1022): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1022): DHCP successful
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): Calling ARP set with IP = 192.168.1.127
,D/WifiStateMachine( 1022): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1022): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
,D/WifiStateMachine( 1022): invokeEnterMethods: VerifyingLinkState
,D/WifiStateMachine( 1022): VerifyingLinkState enter
,D/WifiStateMachine( 1022): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=151572
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1022): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1022): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=135190
D/WifiStateMachine( 1022): processMsg: VerifyingLinkState
D/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1022): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1022): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1022): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1022): CaptivePortalCheckState enter
,D/WifiStateMachine( 1022): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1022): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1022): handleMessage: X
D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
D/WifiStateMachine( 1022): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1022): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1022): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1083): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1022): WiFi NOT Tethered!
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1022): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1022): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1022): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1022): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1022): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1022): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1022): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1022): handleMessage: X
,D/WifiStateMachine( 1022): handleMessage: E msg.what=131092
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@42083e68
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
D/WifiStateMachine( 1022): processMsg: DefaultState
D/WifiStateMachine( 1022): handleMessage: X
D/Checkin ( 1022): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1260): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1260): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1260): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1083): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1022): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1022): WiFi NOT Tethered!
,E/ConnectivityService( 1022): Unexpected mtu value: android.net.wifi.WifiStateTracker@42083e68
I/SBar.NetworkController( 1083): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1260): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1260): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1260): onReceive() - done, currentInetCondition=0
,I/jxcore-log( 3427): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3427): 
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 3671
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 3672
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 3677
,W/ProcessCpuTracker( 1022): Skipping unknown process pid 3680
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1022): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1022): Setting time of day to sec=1450201777
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/        ( 1022): Unable to set rtc to 1450201777: Invalid argument
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/PollingManager( 1530): now: 229291 ,futureTime: 6867887
,D/PollingManager( 1530): Polling alarm set to expire at: 6867887 Current Time: 229292
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/Tethering( 1022): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1248): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1530): registerApp(): CCE
I/CCE     ( 1530): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1530): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/MMApiWebService( 1530): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1530): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
,D/PollingManager( 1530): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1530): now: 229364 ,futureTime: 6867887
,D/PollingManager( 1530): Polling alarm set to expire at: 6867887 Current Time: 229364
,D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1530): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1530): generating token using payload instead of using session token
,E/ActivityThread( 1530): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1530): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1530): isRequestAllowed(): already have outstanding request ... ignoring request
,D/OtaApp  ( 1530): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/openssl ( 3314): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3314): Crypto mode 0 already enabled
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
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1530): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1530): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1022): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3715 uid=10056 gids={50056, 3003, 1028, 1015}
,D/dalvikvm( 1373): GC_EXPLICIT freed 1245K, 40% free 10340K/17224K, paused 21ms+8ms, total 105ms
,I/ActivityManager( 1022): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3731 uid=10030 gids={50030, 3003, 1028, 1015}
,I/dalvikvm( 1352): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1352): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1352): VFY: replacing opcode 0x6e at 0x003d
,V/MmsConfig( 3731): mnc/mcc: 
,V/MmsConfig( 3731): tag: bool value: enabledMMS - true
V/MmsConfig( 3731): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3731): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3731): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3731): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 3731): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3731): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3731): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3731): tag: int value: recipientLimit - 20
,V/MmsConfig( 3731): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3731): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3731): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3731): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3731): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3731): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3731): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3731): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3731): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1022): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3755 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1022): Killing 3243:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+5ms, total 24ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,D/MobileConnectivityChangeReceiver( 3755): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3755): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3755): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3755): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/dalvikvm( 1022): GC_EXPLICIT freed 1701K, 65% free 17870K/50196K, paused 4ms+11ms, total 140ms
I/ActivityManager( 1022): Killing 2841:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3771 uid=10076 gids={50076, 3003, 1028, 1015}
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
I/CheckinService( 1352): Checkin interval check for package: unspecified last checkin: 1450198974007 min interval config: 0 actual interval: 2804457
,I/CheckinService( 1352): Checking schedule, now: 1450201778474 next: 1450199003973
,I/CheckinService( 1352): active receiver: enabled
,I/CheckinService( 1352): Preparing to send checkin request
,I/EventLogService( 1352): Accumulating logs since 1450201702778
,E/Auth.Api.Credentials( 1352): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm( 1238): GC_EXPLICIT freed 1387K, 45% free 9515K/17224K, paused 4ms+5ms, total 54ms
,I/CheckinRequestBuilder( 1352): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1022): New client listening to asynchronous messages
,E/ActivityThread( 1352): Failed to find provider info for com.google.android.wearable.settings
,E/ActivityThread( 1352): Failed to find provider info for com.android.contacts.metadata
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,V/WebViewChromiumFactoryProvider( 3771): Binding Chromium to main looper Looper (main, tid 1) {41f80960}
,I/LibraryLoader( 3771): Expected native library version number "",actual native library version number ""
,I/chromium( 3771): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3771): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3771): BLUETOOTH permission is missing!
,D/DelayedSyncController( 3715): Delaying sync.
,I/Adreno-EGL( 3771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3771): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3771): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3771): Local Branch: 
I/Adreno-EGL( 3771): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3771): Local Patches: NONE
I/Adreno-EGL( 3771): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/GpsLocationProvider( 1022): NTP server returned: 1450201775010 (Tue Dec 15 18:49:35 CET 2015) reference: 226282 certainty: 8 system time offset: -3628
,E/LocSvc_ApiV02( 1022): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/SyncManager( 1022): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 229935, reason: UserStart
,W/chromium( 3771): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/ActivityManager( 1022): Killing 3269:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/GAV2    ( 3771): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3771): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1022): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3821 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 3821): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3821): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3821): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3821): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3821): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 3821): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3821): install
,I/MultiDex( 3821): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/PhenotypeConfigurator( 1202): Scheduling Phenotype for one-off execution 11660 seconds from now (1450201778897)
,I/NSApplication( 3771): Starting up...
,I/MultiDex( 3821): loading existing secondary dex files
,I/MultiDex( 3821): load found 3 secondary dex files
,I/MultiDex( 3821): install done
,I/ImageResourceManager( 3296): ImageResourceManager: uninitalized
,I/iu.Environment( 3296): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/GetConfigurationSnapshotOperation( 1202): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/iu.SyncManager( 3296): SYNC; picasa accounts
,D/DelayedSyncController( 3715): Delaying sync.
,I/iu.UploadsManager( 3296): num queued entries: 0
I/ActivityManager( 1022): Killing 2818:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/iu.UploadsManager( 3296): num updated entries: 0
I/iu.SyncManager( 3296): NEXT; no task
D/dalvikvm( 3821): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3821): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3821): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3821): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3821): VFY: unable to resolve instance field 36
D/dalvikvm( 3821): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3821): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3821): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3821): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3821): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3821): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 3821): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f86e28
D/dalvikvm( 3821): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f86e28
D/dalvikvm( 3821): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f86e28, skipping init
D/dalvikvm( 3821): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f86e28
D/dalvikvm( 3821): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f86e28
V/JNIHelp ( 3821): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/iu.SyncManager( 1352): SYNC; picasa accounts
,D/NetworkLogImpl( 1352): Loaded NetworkSpeedPredictor
,I/PhenotypeFlagCommitter( 1202): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/iu.Environment( 1352): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
D/dalvikvm( 3821): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f86e28
,D/dalvikvm( 3821): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f86e28
D/dalvikvm( 3821): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f86e28
,D/dalvikvm( 3821): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f86e28
I/openssl ( 3314): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3314): Crypto mode 0 already enabled
W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1202): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x00bb
,I/iu.UploadsManager( 1352): num queued entries: 0
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,I/iu.UploadsManager( 1352): num updated entries: 0
,I/iu.SyncManager( 1352): NEXT; no task
,D/MobileConnectivityChangeReceiver( 3755): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3755): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3296): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1022): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3854 uid=10007 gids={50007, 3003}
,D/dalvikvm( 1352): GC_CONCURRENT freed 1511K, 32% free 11836K/17224K, paused 6ms+5ms, total 52ms
,D/ExtensionsFactory( 3854): No custom extensions.
,I/ProviderInstaller( 3821): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1022): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3871 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1022): Killing 2892:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3881 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3504:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GCM     ( 1373): GCM config loaded
,D/WifiService( 1022): Client connection lost with reason: 4
,D/dalvikvm( 1202): GC_CONCURRENT freed 1491K, 35% free 11331K/17224K, paused 4ms+29ms, total 73ms
,V/AlarmClock( 3871): AlarmInitReceiver android.intent.action.TIME_SET
I/dalvikvm( 3821): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 3821): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3821): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 3821): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 3821): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3821): VFY: replacing opcode 0x6e at 0x000d
,I/CalendarProvider2( 3881): Created com.android.providers.calendar.CalendarAlarmManager@41f9e018(com.android.providers.calendar.CalendarProvider2@41f95bd0)
,I/dalvikvm( 3821): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3821): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3821): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3821): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 3821): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3821): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 3821): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3821): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 3821): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3821): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 3821): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 1530): GC_CONCURRENT freed 2060K, 38% free 10763K/17224K, paused 4ms+4ms, total 37ms
,I/AlarmClock( 3871): Displaying next alarm time: ''
,V/AlarmClock( 3871): AlarmInitReceiver finished
,I/ActivityManager( 1022): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3906 uid=10098 gids={50098}
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  278): App is not loaded in QSEE
,D/MMApiWSBase( 1530): doRequest(): v1/ns/list/messages resp length: 1465
,D/QSEECOMAPI: (  278): Loaded image: APP id = 3
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5128000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5128000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1530): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=740470406
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 1022): GC_EXPLICIT freed 827K, 65% free 17810K/50196K, paused 5ms+17ms, total 132ms
,D/dalvikvm( 1373): GC_EXPLICIT freed 677K, 41% free 10298K/17224K, paused 13ms+5ms, total 58ms
,D/Checkin ( 1530): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/MMApiProvisionService( 1530): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"71402","deviceId":"1135300315450105856"}
,D/SundryService( 1530): handleGetNotificationsResponse(): got 0; more=false
,D/MMApiProvisionService( 1530): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1530): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1530): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/dalvikvm( 3906): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f8a180, skipping init
D/TimeService( 3906): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201779571
D/        ( 3906): TimeServiceNative: User Time to be set is 1450201779572
D/QC-time-services( 3906): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3906): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3906): Lib:time_genoff_operation: pargs->ts_val = 1450201779572
,D/QC-time-services(  361): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3906): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  361): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450201779572
D/QC-time-services(  361): Daemon:genoff_opr: Base = 2, val = 1450201779572, operation = 0
,D/QC-time-services(  361): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/15/115 17:43:44
D/QC-time-services(  361): Daemon:Value read from RTC seconds = 1450201424000
D/QC-time-services(  361): Daemon:new time 1450201779572 
D/QC-time-services(  361): Daemon: delta 355572 genoff 355572 
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 355572 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
W/DriveInitializer( 1352): Awaiting to be initialized
,W/DriveInitializer( 1352): Background init thread started
D/QC-time-services(  361): Updating the TOD offset
D/QC-time-services(  361): Daemon:genoff_persistent_update: Writing genoff = 355572 to memory
D/QC-time-services(  361): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  361): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  361): Daemon:Update to modem bit set
D/QC-time-services(  361): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  361): Daemon: Base = 2, Value being sent to MODEM = 18446743757745107188
,E/QC-time-services(  361): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  361): Daemon: Time-services: Waiting to acceptconnection
,D/MMApiProvisionService( 1530): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 16 14:39:41 CET 2015
D/MMApiProvisionService( 1530): _setMMApiCredInfo: storing credential info 
,E/QC-time-services( 3906): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager( 1022): Killing 3314:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1352): Checkin interval check for package: unspecified last checkin: 1450198974007 min interval config: 0 actual interval: 2805595
,E/MMApiProvisionService( 1530): handleResponse(): no settings sent by the server:
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1352): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,D/MMApiWebService( 1530): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/dalvikvm( 3821): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42179350
D/dalvikvm( 3821): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42179350
,D/dalvikvm( 3821): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42179350, skipping init
,W/DriveInitializer( 1352): Background init thread ended
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DEBUG   ( 1530): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1530): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/NativeLibraryUtils( 3821): Install completed successfully. count=14 extracted=0
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1530): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1530): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1022): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1530
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/IInputConnectionWrapper( 3427): showStatusIcon on inactive InputConnection
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1260): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1260): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1260): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1260): onReceive() - done, currentInetCondition=100
I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1022): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,125
,D/WifiStateMachine( 1022): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1022): handleMessage: E msg.what=131215
D/WifiStateMachine( 1022): processMsg: ConnectedState
D/WifiStateMachine( 1022): processMsg: L2ConnectedState
D/WifiStateMachine( 1022): processMsg: ConnectModeState
D/WifiStateMachine( 1022): processMsg: DriverStartedState
D/WifiStateMachine( 1022): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1022): processMsg: DefaultState
,D/WifiStateMachine( 1022): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1022): handleMessage: X
,I/OtaApp  ( 1530): [info] > Updatetime from metadata: 10
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
D/ConnectivityService( 1022): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1022):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
,D/OtaApp  ( 1530): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1530): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1530): publish the event [tag = MOT_OTA event name = LOG]
,D/ConnectivityService( 1022): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1022): requiresClat: netType=1, hasIPv4Address=true
D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1530): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/WearableService( 1202): callingUid 10022, callindPid: 1202
I/ActivityManager( 1022): Activity reported stop, but no longer stopping: ActivityRecord{427b8fb0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/LocationInitializer( 1352): Restart initialization of location
,D/AuthorizationBluetoothService( 1373): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1373): Proximity feature is not enabled.
,E/MDM     ( 1202): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1202): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x003d
,D/DEBUG   ( 1530): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1530): onHandleIntent(): isWaitEnabled=false
W/GCoreFlp( 1202): No location to return for getLastLocation()
D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
,W/FusedLocationProvider( 1202): location=null
,D/DEBUG   ( 1530): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1530): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1530): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1530): onServiceConnected()
D/GetNotificationsWS( 1530): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1530): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1530): Received shoulder tap
,D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1530): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1530): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1530): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1530): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1530): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3821): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 3949): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3821): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3821): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 1ms, rewrite 72ms
,I/Adreno-EGL( 3821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3821): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3821): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3821): Local Branch: 
I/Adreno-EGL( 3821): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3821): Local Patches: NONE
I/Adreno-EGL( 3821): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3821): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3821): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3821): Local Branch: 
I/Adreno-EGL( 3821): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3821): Local Patches: NONE
I/Adreno-EGL( 3821): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
I/CalendarProvider2( 3881): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3881): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3854): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3854): 0 Action = android.intent.action.PROVIDER_CHANGED
,W/Settings( 3821): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 3821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3821): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3821): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3821): Local Branch: 
I/Adreno-EGL( 3821): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3821): Local Patches: NONE
I/Adreno-EGL( 3821): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3821): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3821): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3821): Local Branch: 
I/Adreno-EGL( 3821): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3821): Local Patches: NONE
I/Adreno-EGL( 3821): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/MMApiWSBase( 1530): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1530): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1530): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1530): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1530): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1530): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1530): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1530): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1530): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1530): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1530): unbindWebServices(): un-registering our AIDL callback...
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=2638638465
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1352): Classify the device as Phone.
,I/CheckinTask( 1352): Sending checkin request (13527 bytes)
,I/CheckinRequestBuilder( 1352): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1352): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1352): Classify the device as Phone.
,I/CheckinTask( 1352): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1352): Checking schedule, now: 1450201782054 next: 1450794852046
,I/CheckinService( 1352): active receiver: disabled
,D/CheckinService( 1352): Recording last checkin time for package unspecified as 1450201782068
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1352): GC_CONCURRENT freed 1776K, 31% free 12040K/17224K, paused 4ms+6ms, total 41ms
,I/GAV2    ( 3771): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3854): no sender configured
,D/AlertService( 3854): Beginning updateAlertNotification
,D/AlertService( 3854): No fired or scheduled alerts
,D/AlertService( 3854): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3854): No events found starting within 1 week.
I/ActivityManager( 1022): Killing 3731:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Killing 3755:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1022): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1022): Checking http://216.58.209.46/generate_204
,W/ActivityThread( 1022): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1022): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1022): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1022): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1022): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1022): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=3995 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/Launcher( 1279): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/Launcher( 1279): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,I/Babel   ( 3995): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3995): MmsConfig.loadMmsSettings
,I/Babel   ( 3995): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 3995): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1202): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel   ( 3995): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3995): MmsConfig.loadFromResources
,E/Babel   ( 3995): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3995): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 3995): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4033 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1022): Killing 3715:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4052 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3771:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2059): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4071 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1022): Killing 3881:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3296): GC_CONCURRENT freed 609K, 5% free 16453K/17224K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 3296): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/dalvikvm-heap( 3296): Grow heap (frag case) to 19.836MB for 1821008-byte allocation
,I/ContactLocale( 4033): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4071): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4071): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4071): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4071): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4071): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4071): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4071): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4071): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4071): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0032
,D/dalvikvm( 1022): GC_EXPLICIT freed 1791K, 65% free 17941K/50196K, paused 3ms+11ms, total 93ms
,W/Settings( 4071): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4071): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4071): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4071): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4071): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4071): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0385
,I/InternalIcingCorporaPro( 2059): UpdateCorporaTask done [took 338 ms] updated apps [took 338 ms] 
I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4105 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4071): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4071): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/Finsky  ( 4071): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4071): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4071): Skipping gmscore version check
,I/dalvikvm( 4071): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4071): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1022): Killing 3906:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
D/PackageBroadcastService( 1352): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1352): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1352): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4105): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f910b8, skipping init
I/openssl ( 4105): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4105): Crypto mode 0 already enabled
,D/Finsky  ( 4071): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1022): Killing 3871:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4071): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1352): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/dalvikvm( 1352): GC_CONCURRENT freed 1966K, 31% free 12042K/17224K, paused 5ms+6ms, total 46ms
,I/Icing   ( 1352): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450201790
,V/AlarmManager( 1022): sending alarm Alarm{427e1cd0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427d9fd0 type 2 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43cd0318 type 2 android}
,E/ActivityThread( 1352): Failed to find provider info for com.android.contacts.metadata
D/SyncManager( 1022): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 289859, reason: UserStart
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43cd8320 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43a48cc8 type 2 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{438c47d0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5,
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8,
,I/dalvikvm( 1022): Jit: resizing JitTable from 8192 to 16384
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42915528 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3427): Connected to the server!
I/jxcore-log( 3427): 
,I/chromium( 3427): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = ,
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4246a7f0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42151560 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4217bdc8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43e0e288 type 3 android}
,I/jxcore-log( 3427): --- start :testFindPeers.js---
I/jxcore-log( 3427): 
,I/jxcore-log( 3427): testFindPeers created [object Object]
I/jxcore-log( 3427): 
,I/jxcore-log( 3427): serverPort is 8876
I/jxcore-log( 3427): 
,I/dalvikvm( 3427): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 3427): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 3427): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 3427): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3427): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 3427): Shutting down VM
,W/dalvikvm( 3427): threadid=1: thread exiting with uncaught exception (group=0x416b5d40)
E/AndroidRuntime( 3427): FATAL EXCEPTION: main
E/AndroidRuntime( 3427): Process: com.test.thalitest, PID: 3427
E/AndroidRuntime( 3427): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 3427): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 3427): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 3427): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 3427): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 3427): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 3427): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 3427): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 3427): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 3427): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 3427): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3427): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3427): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 3427): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 3427): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3427): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3427): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 3427): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 3427): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 3427): Sending signal. PID: 3427 SIG: 9
,I/WindowState( 1022): WIN DEATH: Window{4462fbd8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1022): Client connection lost with reason: 4
,I/ActivityManager( 1022): Process com.test.thalitest (pid 3427) has died.
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4292db18 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4278e218 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{446969b0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427d0988 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{427cef80 type 1 com.android.deskclock}
,D/ConnectivityService( 1022): Done.
,I/ActivityManager( 1022): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4187 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1022): Setting timer for 720seconds
,I/ActivityManager( 1022): Killing 3854:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{420e17b8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{445d2f08 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{422a1918 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4292bba0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{427cefd0 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1260): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1260): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1260): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1022): sending alarm Alarm{427b2a30 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4217cce0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43a0db88 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43a54398 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4284b8d8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{427c93c8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42886a70 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{440520d8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{420ee248 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{4285cd10 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43cc5d58 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428fe958 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{427b2b08 type 1 com.android.deskclock}
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43a4d370 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{43980d90 type 3 android}
,I/ProcessStatsService( 1022): Prepared write state in 16ms
,I/ProcessStatsService( 1022): Prepared write state in 15ms
,I/ProcessStatsService( 1022): Prepared write state in 20ms
,I/ProcessStatsService( 1022): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-41-29.bin
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42fe8ee8 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{433d6000 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4225): 
D/AndroidRuntime( 4225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4225): CheckJNI is OFF
D/dalvikvm( 4225): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4225): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4225): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4225): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4225): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4225): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4225): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4225): failed to load memtrack module: -2
D/AndroidRuntime( 4225): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10104 user=-1: uninstall pkg
I/ActivityManager( 1022):   Force finishing activity ActivityRecord{44678818 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1022): Skipping PackageSetting{42247d98 com.example.hello/10479} due to missing metadata
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10104 user=0: pkg removed
D/dalvikvm( 1352): GC_EXPLICIT freed 443K, 32% free 11800K/17224K, paused 3ms+5ms, total 40ms
D/dalvikvm( 3296): GC_FOR_ALLOC freed 35K, 5% free 18195K/19004K, paused 31ms, total 31ms
W/SQLiteConnectionPool( 1352): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2026): GC_EXPLICIT freed 6282K, 44% free 9738K/17224K, paused 2ms+6ms, total 44ms
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
D/VoicemailCleanupService( 4033): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1279): GC_EXPLICIT freed 2653K, 33% free 11589K/17224K, paused 2ms+5ms, total 84ms
D/dalvikvm( 2059): GC_EXPLICIT freed 2909K, 42% free 10057K/17224K, paused 2ms+36ms, total 134ms
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
I/Launcher( 1279): Deferring update until onResume
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
D/dalvikvm( 1022): GC_EXPLICIT freed 2127K, 65% free 18023K/50196K, paused 5ms+11ms, total 127ms
D/dalvikvm( 1022): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/dalvikvm( 1022): GC_EXPLICIT freed 173K, 65% free 17850K/50196K, paused 4ms+9ms, total 85ms
I/Launcher( 1279): Deferring update until onResume
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450203575
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/InternalIcingCorporaPro( 2059): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/ActivityManager( 1022): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4254 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450203575
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10104 #1
D/AndroidRuntime( 4225): Shutting down VM
D/dalvikvm( 4225): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
I/InternalIcingCorporaPro( 2059): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
W/ActiveOrDefaultContextProvider( 4254): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4279 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4254): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4071): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4071): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4071): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1352): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1352): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1352): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1352): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1352): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1352): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1352): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1352): disk I/O error (code 3850)
E/DriveAsyncService( 1352): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1352): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1352): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1352): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1352): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1352): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1352): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1352): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1352): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1352): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1352): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1352): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 1352): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1373): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1373): Shutting down VM
W/dalvikvm( 1373): threadid=1: thread exiting with uncaught exception (group=0x416b5d40)
W/dalvikvm( 1352): threadid=37: thread exiting with uncaught exception (group=0x416b5d40)

```
